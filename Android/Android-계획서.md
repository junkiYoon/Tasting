# Android

# 첫번째 시간
## 언어
**<u>안드로이드에서 사용하는 언어 설명</u>**  
안드로이드는 주로 Java 또는 Kotlin이라는 프로그래밍 언어를 사용하여 개발합니다.  
먼저, XML이라는 언어를 이용하여 레이아웃, 쉽게 말해 화면을 만들고 Java와 Kotlin을 이용하여 화면을 동작시킬 기능들(각 요소의 터치, 스와이프, 탭 이동 등과 같은 이벤트 대응 코드)를 개발합니다.

#### Java
**<u>C 언어와 Java 문법의 차이 설명</u>**  
Java는 썬마이크로시스템즈에서 개발한 언어입니다.  
C 언어와 자바의 문법은 약간의 차이가 있을뿐 대체적으로 비슷합니다.

* String: 문자열 자료형으로 C언어의 char배열과 대응됩니다.
* 변수 선언 
* 함수 선언
* 클래스

## 안드로이드란?
**<u>안드로이드를 간단하게 설명, 스튜디오 코드 설명</u>**  
안드로이드는 구글에서 만든 스마트폰 모바일 운영체제로 리눅스를 기반으로 만들었습니다.  
안드로이드 앱은 안드로이드 운영체제 위에서 동작하는 어플이며 주로 안드로이드 스튜디오를 이용해서 개발합니다.  
우선, 안드로이드 스튜디오에서 프로젝트를 만드시고 나면 MainActivity라고 하는 클래스와 onCraete()라고 하는 콜백함수가 있습니다.

* MainActivity: 프로젝트 생성시 기본으로 만들어지는 액티비티 클래스입니다.
* onCraete(): 앱이 동작하는 중에 액티비티가 생성될 때 자동 호출되는 콜백함수입니다.

# 두번째 시간
## JavaCode
**<u>자바코드에서 자주 쓰이는 간단한 객체 설명</u>**  
#### 인텐트
인텐트는 안드로이드 컴포넌트간 데이터를 전달하기 위한 객체입니다.
#### 토스트
토스트는 간단한 메시지를 짧은 시간에 팝업형태로 띄우기 위한 객체입니다. 
## XmlCode
**<u>xml파일에서 자주 쓰이는 간단한 뷰 설명</u>**  
* 텍스트뷰: 화면에 텍스트를 띄우는 뷰
* 에디트텍스트: 텍스트를 입력받는 뷰
* 버튼: 클릭 이벤트를 감지하는 뷰

# 세번째 시간
## 앱 만들기
**<u>만들어볼 어플을 간단하게 설명</u>**  
* 음성인식 앱
* 개요: 버튼 클릭시 인텐트를 이용해서 구글 기본 앱 중에 음성인식을 자동으로 불러와 음성을 문자열로 받은 후 텍스트 뷰에 띄우는 앱
* 사용할 코드: 텍스트 뷰, 인텐트, 버튼
