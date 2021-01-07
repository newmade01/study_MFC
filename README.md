# MFC_study



##### MessageDriven방식
-  GetMessage()
함수를 통해 메시지 큐(Message Queue)에서 메시지(Message)를 가져옴

- OnCreate() 
WM_CREATE 메시지 발생 시 자동으로 호출되는 메시지 핸들러 함수

- public:  CWnd m_wndChild;
솔루션의 헤더의 클래스 내부의 재정의 부분
CWnd는 창 클래스의 기본 기능을 사용하기 위한 클래스
		TEXT("임시 테스트 화면"),  //윈도우 텍스트
		WS_CHILD |     // 자식 윈도우 생성 
		WS_VISIBLE |    // 보이게 함
		WS_BORDER |    // WINDOW STYLE
		WS_CAPTION |    // 제목표시줄 창(타이틀 바) 생성
		WS_SYSMENU |    // 시스템 메뉴 추가
		WS_MINIMIZEBOX |    // 최소화 버튼
		WS_MAXIMIZEBOX |    // 최대화 버튼 
		//WS_OVERLAPPED |// 겹치는 윈도우
		WS_HSCROLL |    // 수직 
		WS_VSCROLL |    // 수평 윈도우에 스크롤 바 붙임,
		//WS_MAXIMIZE |    // 최대 창으로 연다
		//WS_MINIMIZE |    // 최소 창으로 연다
		WS_SIZEBOX,    // 윈도우 생성 크기 변경 위한 테두리 넣음
		CRECT(0, 0, 300, 300), // LEFT TOP(0,0), RIGHT BOTTOM(300,300)
		THIS,        // 부모 윈도우

		1234);         // 윈도우 리소스 ID


![](https://t1.daumcdn.net/cfile/tistory/19530E3B4D5AE3AD1F)


<img src="https://t1.daumcdn.net/cfile/tistory/1360C3424D5AE3AD21" alt="">
