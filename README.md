# H_onboard
체스판 위에 알파벳 H를 놓기

## 사용법
1. 체스판 영상을 찍습니다.
2. camera_calibration을 실행해 Camera matrix와 Distortion coefficient을 구합니다.
```python
K = np.array([[1.12241645e+03, 0.00000000e+00, 6.37018034e+02],
              [0.00000000e+00, 1.12130767e+03, 3.55886359e+02],
              [0.00000000e+00, 0.00000000e+00, 1.00000000e+00]])
dist_coeff = np.array([ 2.21102312e-01, -1.33000482e+00, -1.66826341e-03, -7.58440262e-05, 2.73252238e+00])
```
3. chessboard 코드에 그 값을 넣고 실행합니다.
4. 다른 모양이나 숫자를 출력하고 싶다면 box_lower과 box_upper을 수정합니다.

## 결과(alphabet H)
![image](https://user-images.githubusercontent.com/113033780/234796129-9619f982-007d-4862-b266-ee0c3b5bbe03.png)
