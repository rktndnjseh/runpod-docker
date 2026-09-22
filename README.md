# runpod-docker

runpod
rtx pro 4500

150기가, 50기가 선택후 deploy
ssh 키생성
ssh 접속

nvidia-smi로 gpu 연결 확인

git clone --branch v0.1.0 https://github.com/NICESONY/panda-sorting-docker.git
cd panda-sorting-docker

docker 설치
apt update

apt install -y docker.io

docker --version
mkdir -p /workspace/docker-data

docker login

docker tag panda-local-vlm-grasp:0.1.0 sungyeon1/panda-local-vlm-grasp:0.1.0

docker images | grep panda

docker push sungyeon1/panda-local-vlm-grasp:0.1.0

<img width="232" height="253" alt="image" src="https://github.com/user-attachments/assets/cb30c460-bd0d-4c1a-b802-4d8c201805c2" />
