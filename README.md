# 1008_homework


클라우드 테크 코스 2기
1주차 2일차(화요일) 과제 - 241008

1. Downward API 사용하여 POD 생성
- github에 신규 repo 생성
- flask 사용하여 python 파일생성 (POD_NAME, NODE_NAME, POD_NAMESPACE --> app.py)
- Dockerfile 생성.
- Github Action으로 github에 이미지 push (multiplatform으로 github action 수행)
- downward_api.yaml에 생성한 도커 이미지로 수정하고 default namespace에 배포
- downward-env 접속하여 5000포트 확인.

2. K9S 설치

3. 과제1에서 생성한 도커 이미지를 helm chart로 구성하여 다른 사람이 설치할 수 있게 함.
- Deployment 설정 (replicas 1), container port -> app.py port와 동일 설정.
- Service, Service Account, ingress 생성하지 않기.

  
