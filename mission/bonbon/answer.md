1. 컨테이너 기술이란 무엇입니까? (100자 이내로 요약)

컨테이너란 '모듈화되고, 격리된 컴퓨팅 환경'을 의미한다.
기존의 VM은 가상화를 위해 하이퍼바이저와 게스트OS가 필요했는데, 컨테이너는 운영체제를 제외하고 어플리케이션 실행에 필요한 모든 파일만 패키징한 형태이므로 VM보다 훨씬 가볍고 빠르게 동작이 가능

2. 도커란 무엇입니까? (100자 이내로 요약)

도커란 리눅스 컨테이너에 리눅스 어플리케이션을 프로세스 격리기술을 사용하여 더 쉽게
컨테이로 실행하고 관리할 수 있게 하는 오픈소스 프로젝트다.
즉, 컨테이너 기반의 오픈소스 가상활 플랫폼


3. 도커 파일, 도커 이미지, 도커 컨테이너의 개념은 무엇이고, 서로 어떤 관계입니까?

도커 파일)
도커이미지를 생성하기 위한 텍스트 파일이며, 빌드 명령어를 포함한다.
컨테이너에 설치해야하는 패키지, 소스콛, 명령어, 환경변수 등을 기록.
어플리케이션 빌드 및 배포를 자동화 할 수 있다.

도커이미지)
컨테이너를 만들때 사용되는 읽기전용 템플릿이다. 도커컨테이너를 생성할때 필요한 요소이며 iso 파일과 비슷한 개념이다.
도커이미지와 도커컨테이너는 1:N의 관계이다.

도커 컨테이너)
도커 이미지로 생성되는 인스턴트이다.
 가상화된 공간을 생성할때 리눅스 자체기능을 사용하여 프로세스 단위의 격리환경을 만드므로 성능손실이 없음


4. [실전 미션] 도커 설치하기 (참조: 도커 공식 설치 페이지)

5. 아래 도커 설치부터 실행 튜토리얼을 참조하여 도커를 설치하고, 도커 컨테이너를 실행한 화면을 캡쳐해서 Pull Request에 올리세요.



