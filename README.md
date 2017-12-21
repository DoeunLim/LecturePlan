오빠 RC카 뽑았다
================

개요
----

### 교육 개요

-	주제 : 아두이노
-	대상: 프로그래밍과 아두이노에 관심이 많은 중학생
-	난이도: 중 ~ 중상

### 수업 개요

-	강의자: 김도훈, 임도은, 이승화, 이인규 (서울) / 김현우, 박상민, 송근재, 이수민(대전)
-	예상 차시: 8차시
-	소요 시간: 3시간(미정)
-	수업 목표
	-	RC카 프로젝트에 필요한 아두이노 지식을 습득한다.
	-	프로그래밍, 코딩이 무엇인지 알고 어떻게 작동하는지 경험한다.
	-	각종 센서와 모듈의 기능과 사용법을 습득한다.
	-	기본적인 회로의 구성방법을 습득한다.
	-	차시를 진행하기 전에 이전 차시에 대한 복습을 진행
	-	강의자료는 각 강의차시 담당자(대전/서울 각각 1명)가 만듬
	-	강의는 n차시의 강의자와 n+1차시의 강의자가 진행
		-	ex)1차시의 경우 - 1차시 강의자(김도훈, 송근재)와 2차시 강의자(임도은, 박상민)이 함께 진행

차시별 기획
-----------

### 1차시 : 아두이노 맛보기

-	강의차시 담당자 : 김도훈(서울), 송근재(대전)
-	강의자 : 김도훈(서울), 송근재(대전), 임도은(서울), 박상민(대전) 
-	강의 목표: 하나의 LED를 ON/OFF하고 모터를 정/역회전 해본다.
-	강의 내용
	-	커리큘럼 진행방향 설명
	-	소프트웨어 설명
		-	소프트웨어의 역사
		-	소프트웨어의 현주소, 일상생활의 적용된 사례
	-	아두이노의 구조, 브레드보드, LED, 저항에 대해 설명
	-	브레드 보드 사용법 설명
		-	Fritzing, 회로도 등을 사용하여 학생들의 회로 설명
	-	전자회로 기초(전원, 접지, 전류 방향 설명)
	-	setup(), loop(), pinMode(), digitalWrite() 설명
		-	Hour of Code 방식의 실습을 진행
		-	함수내의 인자를 <보기>형식으로 제시, 학생들이 인자를 직접 매칭해보는 방식
			-	예시)
			-	□번 핀을 □랑 연결하기
			-	□번 핀을 □으로 설정하기
			-	□번 핀 겨기 / 끄기
	-	실습 진행 내용
		-	LED 켰다 끄기 반복하기
		-	모터 회전 시켜보기
			-	모터 드라이버 사용하지 않음
			-	5차시에서는 모터드라이버에 대해서 설명
			-	모터드라이버는 5차시, 모터에 대해서 집중 설명할 때 사용
			-	digitalWrite()함수를 사용하여 핀에 직접 연결

### 2차시 : 프로그래밍은 어떻게 해요?

-	강의차시 담당자 : 임도은(서울), 박상민(대전)
-	강의자 : 임도은(서울), 박상민(대전), 이승화(서울), 이수민(대전)
-	강의 목표: 1부터 100까지 짝수만 더하는 프로그램을 작성한다.
-	강의 내용
	-	변수에 대해 설명
		-	배열의 개념은 제외
		-	학생들에게 과제를 제시할 때, 배열 개념 없이 해결할 수 있는 과제를 선정
		-	변수의 산술 연산 설명
		-	직접 눈에 보이는 실물을 가지고 설명
			-	상자에 숫자가 프린트 된 종이를 넣는 식의 설명(변수에 자료를 대입)
			-	모양이 다른 종이는 상자에 들어가지 않는 다는 식의 설명(자료형)
	-	if문에 대해 설명
		-	조건이라는 개념 설명
		-	논리 연산자, 비교 연산자 설명
	-	실습 진행 내용	
		-	버튼으로 LED, Buzzer 제어하기
		-	버튼을 5번 누르면 LED가 켜지고 2초 있다가 꺼지기 반복하는 예제 수행하기

### 3차시: 아날로그와 디지털의 차이

-	강의차시 담당자 : 이승화(서울), 이수민(대전)
-	강의자 : 이승화(서울), 이수민(대전), 이인규(서울), 김현우(대전)
-	강의 목표: 푸시 버튼으로 LED를 제어하고 CDS로 LED의 밝기를 조절한다.
-	강의 내용
	-	아날로그 신호와 디지털 신호의 차이
		-	연속(아날로그), 이산(디지털)
		-	주변에서 아날로그와 디지털 찾아보기
	-	반복문
		-	while 문 설명
		-	for 문 설명
		-	실물 위주의 설명(반복문의 탈출 포인트, 변수의 변화)
		-	과자 여러개를 가지고 와서, 3개 이상 먹으면 그만 먹기! 이런식으로 반복 조건 설정 후 직접 먹여주면서 설명
		-	for문 조건 보여주고, 이 조건만큼 먹으라고 하기  
		-	첫 한시간은 반복문 설명, 두번째 시간은 아날로그와 디지털, LED 밝기 조절, 세번째 시간은 CDS를 이용
	-	실습 진행 내용
		-	LED 밝기 조절 (Dimming 제어, 반복문 제어)
		-	CDS 밝기 threshold (문턱 값 On/Off)
		-	CDS 밝기 → LED 밝기 (밝기에 따라 LED 밝기 조절하기)

### 4차시: 센서 값 확인하기

-	강의차시 담당자 : 이인규(서울), 김현우(대전)
-	강의자 : 이인규(서울), 김현우(대전), 김도훈(서울), 송근재(대전)
-	강의 목표: CDS와 온습도 센서 값을 LCD로 출력한다.
-	강의 내용
	-	온습도 센서 설명, LCD사용법 설명
	-	온습도 센서, LCD 라이브러리 활용

### 5차시: 바퀴를 굴려보자

-	강의차시 담당자 : 김도훈(서울), 송근재(대전)
-	강의자 : 김도훈(서울), 송근재(대전), 임도은(서울), 박상민(대전)
-	강의 목표: 모터를 모터 드라이버로 제어하고, PWM신호로 가감속을 해본다.
-	강의 내용
	-	RC카의 기본 구조를 갖고 있는 모형을 배부, 이후 진행할 차시에서 모듈 업그레이드 식으로 활용
	-	모터 드라이버 설명 및 활용
	-	PWM 개념 설명 및 활용(매우 상세히 설명을 준비할 것!)

### 6차시: 블루투스 통신을 해보자

-	강의차시 담당자 : 임도은(서울), 박상민(대전)
-	강의자 : 임도은(서울), 박상민(대전), 이승화(서울), 이수민(대전)
-	강의 목표: 미리 제작해놓은 안드로이드 앱을 통해 아두이노와 안드로이드 간 블루투스 통신을 하고, 블루투스 통신을 통해 회로를 제어해본다.
-	강의 내용
	-	블루투스 모듈의 이해와 활용

### 7차시: 나만의 기능을 제작해보자 1부

-	강의차시 담당자 : 이승화(서울), 이수민(대전)
-	강의자 : 이승화(서울), 이수민(대전), 이인규(서울), 김현우(대전)
-	강의 목표 : 나만의 RC카에 나만의 기능을 구현해보자!
-	강의 내용
	- 설리번이 준비해놓은 기능들 + 헬렌들이 직접 구현하고 싶은 기능
	- 깜빡이 (비상등, 차선 변경 등)
	- 어두운 곳에서 헤드라이트 켜기
	- 후진 시 "엘리제를 위하여" 연주
	- 기존에 있던 초음파 센서 내용을 삭제함.
	- +Alpha

### 8차시: 나만의 기능을 제작해보자 2부

-	강의차시 담당자 : 이인규(서울), 김현우(대전)
-	강의자 : 이인규(서울), 김현우(대전), 김도훈(서울), 송근재(대전)
-	강의 목표: 자신만의 자동차 프레임을 통해 자동차를 이동시킨다.
-	강의 내용
	-	7차시 내용을 이어 진행.