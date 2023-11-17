# machine_learn_class
기계학습 프로그래밍 기말 프로젝트 파일입니다.

코드: 전체코드, lstm코드(전체코드에서 나이브베이지 모델을 썼기에 주석처리 하여 실제 구동가능한 코드를 첨부했습니다.)
데이터: train_data.csv를 제외하고 나머지는 전체코드를 돌릴 시 자동으로 만들어집니다.

파일 경로로 인해 데이터와 코드를 같은 폴더에 두시고 코드를 실행하시면 됩니다.

뉴스 긍부정 판별 모델에서 라이브러리 임포트가 많아 해당 라이브러리 설치 명령어입니다.
pip install gensim
pip install transformers
pip install torch==1.10
conda install -c conda-forge ipywidgets
conda install pytorch torchvision torchaudio cudatoolkit=10.2 -c pytorch
