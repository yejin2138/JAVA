# JAVA
### 1장 
#### 프로그래밍 언어의 종류

+ 기계어 - 0,1로 구성된 언어 / 컴퓨터의 CPU는 기계어만 이해, 처리

+  어셈블리어 - 기계어를 표현하기 쉬운 상징적인 단어로 일대일 대응 시킨 언어

+ 고급언어 - 사람이 이해하기 쉽고 자료구조, 알고리즘을 표현하기 위해 고안된 언어


#### 프로그래밍과 컴파일
컴파일 - 소스 프로그램을 기계어로 변환하는 것
컴파일러 - 이런 소프트웨어를 말함

    .C -> .obj -> .exe

      컴파일   링크

* * *
#### JDK JRE
+ JDK - 자바 응용 개발 환경
+ JRE - 자바 실행 환경
<br>

#### 자바 API
+ 자바 패키지 - 서로 관련된 클래스들을 분류하여 묶어놓은것
+ 자바 API - 개발자가 쉽고 빠르게 자바 프로그램을 개발할 수 있는 자바 라이브러리
<br>

#### 자바 통합 개발 환경-이클립스
+ IDE - 통합 개발 환경, 편집 컴파일 디버깅을 한번에 할 수 있다.
+ 이클립스 - 자바 응용프로그램 개발을 위한 통합 개발 환경
<br>

 * * *
 
#### Open Challenge 자기소개하기
```java

public class MyInFoApp {
	public static void main(String[] args) {	
		System.out.println("Lee Yejin\n22 years old\nComputer Engineering");	
	}
}
```

#### HelloWorld
```java
public class Hello {
	public static void main(String[] arg) {
		System.out.println("Hello World");
	}
}
```
* * *
### 2장 
#### 식별자
클래스, 변수, 상수, 메소드에 붙이는 이름이다<br>
특수문자 공백은 식별자로 사용할 수 없다 하지만 _ $는 가능하다<br>
_ $는 첫번재 문자로는 잘 쓰지 않는다.<br>
대소문자 구분한다.<br>

