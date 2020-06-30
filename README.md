# pygame_project 필독사항

- 2019250063 길효민
- 한경대학교 컴퓨터공학입문과파이썬 기말고사 
- 게임 프로젝트 제작하기

-------------------------------------------------------------------------------------------------------
  
***** 게임 진행 방법 및 설명 *******

1. 압축폴더를 해체
2. 그 안에 있는 PySpaceShip.py를 실행
3. 마우스나 s키를 이용하여 게임시작
4. 마우스로 자신의 비행선을 움직여서 암석을 피해야하는 게임
5. 시간이 지나갈수록 난이도가 올라가며, 무작위로 생성하는 워프 아이템을 억을 수 있다,
6. 게임 중 마우스 클릭을 하여 아이템을 사용할 수 있다 -> 바위들이 사라진다. 
7. 암석에 닿을 경우 게임 종료 -> 점수를 화면에 띄워준다.


-------------------------------------------------------------------------------------------------------


********************* 아래의 조건들 충족시켜도 안되거나 에러가 날 경우 *******************

마지막 방법입니다. 아래의 중요 요건을 먼저 봐주세요 !

https://goor.me/kr4rq

구름 ide 가상 프로젝트 공유 링크입니다.

1. 링크로 들어간다
2. 왼쪽 상단에 프로젝트 -> 빌드 실행/설정 클릭
3. 컴파일러 -> python3로 설정, 실행 화면 크기를 800x600으로 설정 -> 적용 및 확인
4. 하단에 터미널을 클릭 -> pip3 install pygame 을 입력하여 pygame 라이브러리를 설치
5. index.py에서 shift + F5를 눌러서 실행한다.
6. 아래의 터미널창에 우측에 서버 링크가 생성이 된다.
7. 링크를 클릭한다.
8. 새로운 페이지에서 게임이 실행된다.

-------------------------------------------------------------------------------------------------------




*************************  중요 아래 요건들을 충족시켜야 합니다 ****************************

-------------------------------------------------------------------------------------------------------
1.

***** pygame 라이브러리 설치 *****

- pygame 라이브러리를 사용했기에 사용하는 컴퓨터에 따라 오류가 발생할 수 있습니다.
- pygame 이 반드시 사용자 컴퓨터에 설치되어 있어야합니다
- cmd창에 pip install pygame을 입력하여 설치를 진행


-------------------------------------------------------------------------------------------------------
2.


***** pygame 동작 확인 ******

cmd창에서 다음과 같은 명령어를 차례대로 입력하자

1. python
2. import pygame
3. pygame.init()

를 차례대로 입력하여 실행하여 정상적으로 pygame이 작동하는지 cmd 창에서 확인하여
자신의 컴퓨터에 pygame 라이브러리가 문제가 없는지 꼭 확인이 필요하다.
이 부분에서 오류가 나는 것은 코드 문제가 아닌 것을 말씀드립니다,.


-------------------------------------------------------------------------------------------------------
3.


****** vscode에서 pygame.init() 오류 발생 시 ******

vscode에서만 발생하는 고질적인 문제인 pylint 에러, 이것 역시 사용자가 설정을 해줘야한다.
pygame.init() 단계에서 발생한다.

- 해결방안

1. 설치된 파이썬을 반드시 자신의 컴퓨터에 환경 변수 path를 잡아주어야 한다.
	-> 파이썬을 설치하면서 자동적으로 path가 설정되므로 굳이 하지 않아도 된다.
	-> 다만 path가 안된 사용자들은 이것을 해줘야합니다.
	-> 파이썬 환경 변수 path는 인터넷상에 자세하게 나와있습니다.

2. 수동으로 pip 명령을 통해서 pylint를 설치한다.
	1. python -m pip install --upgrade pip 
	2. python -m pip install pylint
	3. 2가지 명령어를 cmd창에서 실행하여 pylint를 설치를 완료하자

위 2가지를 충족한다면 문제 없이 vscode에서 pygame이 돌아갑니다.
vscode에서 빨간줄로 밑줄이나, 노란줄은 신경쓰지 않아도 됩니다.


-------------------------------------------------------------------------------------------------------
