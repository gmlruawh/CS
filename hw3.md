# CS
---
## 제어공학 과제 2
#### 2020732038 조겸희

---
### p3.1
![KakaoTalk_20241015_103249987_04](https://github.com/user-attachments/assets/a83fe850-6330-48a0-987c-caca1fe099f4)   

### p3.3
![KakaoTalk_20241015_103249987_05](https://github.com/user-attachments/assets/b04ff2a7-a0e9-4848-995d-1cdd68f3be72)

### p3.5
![KakaoTalk_20241015_103249987_06](https://github.com/user-attachments/assets/270215c4-9dcc-4211-a556-32d37594193b)

### p3.12
![KakaoTalk_20241015_103249987_07](https://github.com/user-attachments/assets/8897dc0c-661b-4b20-ba85-3a4495d10871)
![KakaoTalk_20241015_103249987_08](https://github.com/user-attachments/assets/fbd48217-878e-48af-b23a-05bde7093cb4)   
이어서 매트랩을 통한 라플라스 역변환으로 상태천이 행렬을 구하는 과정과 결과는 다음과 같다.
![image](https://github.com/user-attachments/assets/10fef046-53c6-47c0-a064-9f456f4b1421)   

$$
\
\begin{bmatrix}
3e^{-2t} - 3e^{-4t} + e^{-6t} & \frac{5e^{-2t}}{4} - 2e^{-4t} + \frac{3e^{-6t}}{4} & \frac{e^{-2t}}{8} - \frac{e^{-4t}}{4} + \frac{e^{-6t}}{8} \\
12e^{-4t} - 6e^{-2t} - 6e^{-6t} & 8e^{-4t} - \frac{5e^{-2t}}{2} - \frac{9e^{-6t}}{2} & e^{-4t} - \frac{e^{-2t}}{4} - \frac{3e^{-6t}}{4} \\
12e^{-2t} - 48e^{-4t} + 36e^{-6t} & 5e^{-2t} - 32e^{-4t} + 27e^{-6t} & \frac{e^{-2t}}{2} - 4e^{-4t} + \frac{9e^{-6t}}{2}
\end{bmatrix}
\
$$   

### p3.17
![KakaoTalk_20241015_103249987_09](https://github.com/user-attachments/assets/802e1bd8-0cea-4ec5-996a-f1b7fb2d4d85)

이어서 매트랩을 통해 Φ(s)를 구하면 다음과 같다   

$$
\begin{bmatrix}
\frac{(s - 3)(s - 10)}{s^3 - 14s^2 + 37s + 20} & \frac{s - 11}{s^3 - 14s^2 + 37s + 20} & \frac{-(s - 3)}{s^3 - 14s^2 + 37s + 20} \\
\frac{4(s - 10)}{s^3 - 14s^2 + 37s + 20} & \frac{s^2 - 11s + 8}{s^3 - 14s^2 + 37s + 20} & \frac{-4}{s^3 - 14s^2 + 37s + 20} \\
\frac{-2(s - 5)}{s^3 - 14s^2 + 37s + 20} & \frac{s - 3}{s^3 - 14s^2 + 37s + 20} & \frac{-(-s^2 + 4s + 1)}{s^3 - 14s^2 + 37s + 20}
\end{bmatrix}
$$   

따라서 식 3.78을 사용해 G(s)를 구하면 다음과 같다.   

$$
\frac{-4(s - 3)}{s^3 - 14s^2 + 37s + 20}
$$

