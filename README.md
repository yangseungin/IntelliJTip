# IntelliJ Tip 모음
### 단축키
- 디렉토리, 패키지, 클래스 등 생성목록 보기  
   맥: Command + n  
   윈도우: Alt+ Insert  
- 실행환경 실행  
  1. 현재 포커스 실행 
    Ctrl + Shift + R  
  2. 이전 포커스 실행  
    Ctrl + R      
- 라인수정하기 
  1. 라인 복사하기  
    Command +D      
  2. 라인 삭제하기  
    Command + 백스페이스         
  3. 라인 합치기  
    Ctrl + Shift + J      
- 라인 단위로 옮기기  
  1. 구문이동  
  	Shift + Command +↑↓  	
  2. 라인이동  
  	Shift + Option +↑↓  
- Element 단위로 옮기기  
	Option + Shift + Command + ←→  	
- 코드 즉시보기  
	1. 인자값 확인하기  
		Command + p  
	2. 메소드 구현코드 확인하기  
		option+space  
	3. docs 미리보기  
		F1  
- 포커스 변경하기  
	1. 포커스 범위 늘리기  
		 Option + ↑↓  
	2. 포커스 앞/뒤 이동
		command + [,]  
	3. 멀티 포커스  
		Option+ Option(누른 상태에서) + ↓  
	4. 오류난곳으로 자동 포커스  
		F2  
- 검색 텍스트  
	1. 텍스트 검색  
		command + f  
	2. 변경하기
		command + r  
	3. 파일검색  
		Shift + Command + O
	4. 메소드 검색  
		Alt + Command + O  
	5. Action 검색
		Shift + Command + A  
	6. 최근 열었던 파일목록 보기  
		Command + E  
	7. 최근 수정했던 파일 목록 보기  
		Command + Shift +E  
- 자동완성
	1. 기본 자동완성  
		Ctrl + space  
	2. 스마트 자동완성  
		Ctrl + Shift + space  
	3. 스태틱 메소드 자동완성  
		Ctrl + space * 2  
	4. Getter/Setter/ 생성자 자동완성  
		Command + N  
	5. Override 메소드 자동완성  
		Ctrl + I  
- Live template
	1. 현재 위치에서 사용가능한 라이브 템플릿 보기  
		Command + j    
	2. 나만의 라이브 템플릿 등록하기(등록할예정)  
	
- 리팩토링 - Extract  
	1. 변수 추출하기  
		Option + Command + v  
	2. 파라미터 추출하기  
		Option + Command + p  
	3. 메소드 추출하기  
		Option + Command + m  
 	4. InnerClass 추출하기  
		F6  
	5. 변수들 한번에 변경  
		Shift + F6  
	6. 타입 변경  
		Command + Shift + F6  
	7. 사용하지 않는 Import 정리  
		Ctrl + Option + o  
	8. 자동으로 Import정리하기  
		(find action에서 optimize import 검색 후 Auto import를 On으로 변경)  
	9. 자동 줄맞춤  
		Command + Option + l  
		
- 디버깅  
![디버그이미지](https://github.com/yangseungin/intellijTip/blob/master/images/%EB%94%94%EB%B2%84%EA%B9%85.png)
    
	1. 현재위치의 메소드에서 Debug모드 실행  
		Ctrl + Shift + D  
	2. 이전 실행 메소드 Debug모드 실행  
		Ctrl + D  
	3. Resume(다음 브레이크포인트로 이동  
		Command + Option +R  
	4. Step Over(현재 브레이크에서 다음 한줄로 이동  
		F8  
	5. Step Into(현재 브레이크의 다음 메소드로 이동  
		F7  
	6. Step Out (현재메소드의 밖으로 이동)  
		Shift + F8  
	7. Evaluate Expression (브레이크 상태에서 코드 사용하기)  
		Option + F8  
	8. Watch(브레이크 이후 코드 변경 확인하기)  
		단축키 없음  

- git  
	1. view - Tool Windows - Version Control (안보일시 command+shift+a후 Enable Version Control Integration - git설정하면 된다.)  		- class들이 빨간색으로 변하는데 unstaged file로 git stage에 올라오지 않은 파일이라는 의미이다  
	2. local changes 탭에서 파일을 show diff해서 변경된부분을 바로 확인가능하고 팝업창에서 바로 코드수정도 가능하다.  
	3. log 탭: 현재 프로젝트의 전반적인 git 상태를 볼수있음
	4. 우클릭시 commit에 관련된 모든 기능을 사용할수 있음(  revert, tag, branch, cherry pick..)
	5. console탭: 실제로 인텔리제이에서 git명령을 날리면 어떤 커맨드들이 실행이 됬는지 git console log를 보여준다

- git popup  
	- 파일안에서 ctrl + v 를 입력시 git popup이뜸  
	- commit, history보기 , push, branch등 모든기능을 사용할 수 있음  
	 
	1. git view on  
		Command + 9  
	2. git option popup  
		Ctrl +v  
	3. git history  
		Ctrl + v => 4  
	4. branch  
		Ctrl + v => 7  
	5. Commit  
		Command + k  
	6. Push  
		Command + Shift + k  
	7. pull  
		Command + shift + A  
 
- github 연동하기  
	Command + shift +A => share github  

- git clone
	Check out from Version Control - git 선택후 github에서 가져온 url을 입력하고 clone하면된다.
	![git clone](https://github.com/yangseungin/intellijTip/blob/master/images/github%20clone.png)

    







### 코드 템플릿
메인 메소드: psvm  
System.out.println(): sout
if문 자동 생성(상단의변수활용) : ifn
