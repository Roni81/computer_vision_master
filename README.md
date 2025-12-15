
## OpenCV 얼굴 인식 프로젝트 (Face Detection)

### 이 프로젝트는 Python과 OpenCV 라이브러리를 활용하여 이미지 속의 사람 얼굴을 자동으로 인식하고, 얼굴 영역에 사각형 박스를 그려 표시하는 예제입니다.

OpenCV의 사전 학습된 Haar Cascade Classifier 모델을 사용하여 빠르고 효율적으로 얼굴을 탐지합니다.

#### 📋 주요 기능
이미지 전처리: 원본 이미지를 불러와 처리 속도 향상을 위해 크기를 조정(Resizing)하고, 탐지 정확도를 위해 흑백(Grayscale)으로 변환합니다.

얼굴 탐지: haarcascade_frontalface_default.xml 분류기를 사용하여 이미지 내의 얼굴 좌표를 찾아냅니다.

결과 시각화: 탐지된 얼굴 위치에 초록색 사각형(Bounding Box)을 그리고 결과를 창으로 띄워 보여줍니다.

#### 🛠 개발 환경 (Requirements)
이 코드는 다음 환경에서 테스트되었습니다.

OS: macOS (M3 Silicon)

Python: 3.10

Libraries:

opencv-python (OpenCV)

numpy
