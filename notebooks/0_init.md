
# 0. docker 설치 
* docker 설치 환경 구축을 위한 다운로드(윈도우즈는 버전의 문제로 docker toolbox를 설치해야 할 수 있다)
  - https://www.docker.com/

# 1. 바벨파이 실습을 위한 image pulling & container 실행
* 실습을 위한 이미지는 다음과 같다. 
  - babelpish/babelphi:0.1 (실습이 진행됨에 따라 버전이 올라갈 수 있음)
  - 이를 직접 pulling(다운로드)해도 된다.
  - (터미널에서 이 명령 실행) docker pull babelpish/babelphi:0.1
* 그리고 contatiner를 생성하여 실행시켜야 되지만...
* 편하게 docker-compose를 써보자.

# 2. 실습을 위한 바벨파이 깃헙 레파지토리 cloning 
* 저장소 주소 
  - https://github.com/babelPish/babelphi.git
* 자기 컴퓨터로 가져온다. 
  - 직접 터미널에서 명령어로 : git clone https://github.com/babelPish/babelphi.git
  - 혹은 관련 클라이언트로 
  - 혹은 그냥 소스 다운로드 
  - 어떤 방식으로 해도 상관없지만, 기왕이면 명령어로 해보자.
