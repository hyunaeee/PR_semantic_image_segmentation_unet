

# 🧠 U-Net 기반 뇌 영상 세그멘테이션 실습

이 리포지토리는 U-Net 아키텍처를 활용하여 뇌 MRI 영상의 의미론적 세그멘테이션(Semantic Segmentation)을 실습한 개인 프로젝트입니다. Keras와 TensorFlow를 기반으로 하며, 의료 영상 처리에 대한 이해를 돕기 위한 실험과 코드 구현을 포함하고 있습니다.

---

## 📁 주요 파일 구성

* **Unet\_model.ipynb**: U-Net 모델을 구현하고 학습 및 평가를 수행하는 메인 노트북입니다.
* **keras\_dataset\_Test.ipynb**: Keras의 `ImageDataGenerator`를 활용하여 데이터셋을 불러오고 전처리하는 과정을 실습한 노트북입니다.
* **keras\_tensorflow\.ipynb**: Keras와 TensorFlow를 활용한 기본적인 모델 구현 및 실습 내용을 담고 있습니다.
* **BNCS401\_PCA\_vs\_NN.ipynb**: PCA와 신경망을 비교 분석한 실험 노트북으로, 세그멘테이션과 직접적인 관련은 없지만 보조 학습 자료로 활용됩니다.

---

## 🧪 주요 실험 내용

* U-Net 아키텍처를 활용한 뇌 MRI 영상의 의미론적 세그멘테이션
* Keras의 `ImageDataGenerator`를 활용한 데이터 전처리 및 증강
* 모델 학습 및 평가를 통한 성능 분석
* PCA와 신경망을 활용한 차원 축소 및 분류 성능 비교

---

## 🛠️ 사용된 기술 스택

* Python
* Keras
* TensorFlow
* NumPy
* Matplotlib

---

## 🚀 실행 방법

1. 리포지토리 클론:

   ```bash
   git clone https://github.com/hyunaeee/PR_semantic_image_segmentation_unet.git
   cd PR_semantic_image_segmentation_unet
   ```
2. 필요한 패키지 설치:

   ```bash
   pip install -r requirements.txt
   ```

   *`requirements.txt` 파일이 없는 경우, 각 노트북 상단의 패키지 설치 안내를 참고하세요.*
3. Jupyter Notebook 실행:

   ```bash
   jupyter notebook
   ```

   원하는 노트북 파일을 열어 실행합니다.

---

## 📄 참고 자료

* U-Net: Convolutional Networks for Biomedical Image Segmentation ([https://arxiv.org/abs/1505.04597](https://arxiv.org/abs/1505.04597))
* Keras 공식 문서 ([https://keras.io/](https://keras.io/))
* TensorFlow 공식 문서 ([https://www.tensorflow.org/](https://www.tensorflow.org/))

