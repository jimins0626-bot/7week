# 🤖 MediaPipe 예지 모음 (인공지능 기초)

이 저장소는 Google MediaPipe의 다양한 컴퓨터 비전 기능(손 인식, 얼굴 인식, 셀피 배경 분할 등)을 Python으로 구현한 실습 예제 모음입니다.

---

## 📁 파일 구조 및 설명

* **`hand_detector.py`**: 웹캠 또는 동영상(`.mp4`)을 활용하여 손의 21개 관절 키포인트와 뼈대를 실시간으로 감지하는 코드
* **`hand_detector_youtube.py`**: 유튜브 동영상 링크를 입력받아 영상 속 손 랜드마크를 감지하는 확장 실습 코드 (`yt-dlp` 사용)
* **`face_detector.py`**: 얼굴의 위치와 눈·코 등의 키포인트를 감지하는 얼굴 인식 코드
* **`selfie_segmentation.py`**: 인물과 배경을 픽셀 단위로 분리하여 배경에 블러(Blur) 효과를 주는 셀피 세그멘테이션 코드
* **`requirements.txt`**: 프로젝트 실행에 필요한 파이썬 패키지 목록 (`opencv-python`, `mediapipe` 등)

---

## 🛠️ 개발 환경 및 실행 방법

1. **Python 버전:** `Python 3.12` 권장
2. **가상환경 생성 및 활성화:**
   ```powershell
   py -3.12 -m venv .venv
   .\.venv\Scripts\activate