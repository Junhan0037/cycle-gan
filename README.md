# cycle-gan

Cycle-GAN을 이용한 딥러닝

cmd창에서 conda activate keras-cyclegan


이미지들은 256 * 256 픽셀로 고정!


datasets의 압축 및 폴더이름은 apple2orange로 고정!


[keras 사용 시 환경설정]


conda create -n keras-cyclegan tensorflow-gpu git opencv keras pillow matplotlib numpy scipy pillow scikit-image


[keras 사용 시 필요한 라이브러리]


pip install git+https://www.github.com/keras-team/keras-contrib.git
