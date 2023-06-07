# SW project

ViT + GPT  를 이용하여 image captioning 및 image to text Model 향상 기여

이 기술을 활용하고자 하는 APP 개발자들에게 서비스를 제공할 수 있음.

----------

# 목적
 
 1. 시각장애인 혹은 노인분들을 위한 주어진 상황 설명
 2. 시야가 제한된 상황 속에서 환경 설명 가능
 3. 이 기술을 활용하고자 하는 APP 개발자들에게 서비스를 제공할 수 있음.

----------
# 활용되는 기술 혹은 모델

 1. Transformer model
 2. Vision Transformer
 3. GPT
 4. GTTS
 
----------

# 실행 방법

1. image_captioning.ipynb(gentlem.ipynb) 의 한-영 모델 번역 부분을 실행 후 Fine-tuning Model 학습
2. Final.ipynb 에서 model_dir 을 앞서 학습 시킨 후 생성된 result 파일로 경로 지정
3. 실행
 * 학습 과정 생략 필요시 https://drive.google.com/drive/folders/14zkQWD33JpHAnc4r7MgNqF8gZQawzTb9?usp=sharing 위 링크에서 result2 파일 다운로드 후 경로 설정 수정.
 * https://drive.google.com/file/d/1OXyWbQ_nJ_DTh3qo1KDF5GZ2Z7fqfdk4/view?usp=sharing
 * -> 학습 과정 생략 필요시 다운로드 받는 링크를 통해 폴더 다운로드 후 경로 추가
















____
### Citation

- vit-gpt : https://huggingface.co/nlpconnect/vit-gpt2-image-captioning
- transformer : https://metamath1.github.io/blog/posts/gentle-t5-trans/gentle_t5_trans.html
