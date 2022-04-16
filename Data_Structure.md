# 데이터 형, 데이터 구조, 추상 데이터형

1. Variable
	- 자료 구조의 데이터가 저장될 단위(Primitive Type, User Defined Type)
	- 데이터를 보관하는 공간, 이름
	- 컴퓨터 과학에서 변수형이 가질 수 있는 값의 종류를 뜻하며, 컴퓨터 과학에서 이를 데이터 형이라 함
	- Primitive Type(원시 자료형)과 User Defined Type(사용자 정의 자료형)으로 나뉨
	- Primitive Type은 System Defined Type으로 시스템에 의해 정의된 데이터를 의미하며, 따라서 OS, 컴파일러 등에 따라 원시 자료형의 크기가 달라짐.
	- Primitive Type으로 충분하지 않을 때, 사용자는 User Defined Type을 정의(클래스, 구조체 등)
	- 사용자 정의 자료형을 통해, 연관된 데이터를 묶고, 이름붙여 사용할 수 있음

2. Data Structure
	> 데이터를 효율적으로 사용하기 위해 컴퓨터에 데이터를 저장, 정리하는 방법으로 정리 방법에 따라 선형/비선형 구조로 나뉨

	- 선형 데이터 구조: 항목들이 순차적 차례에 따라 '접근', 연결 리스트처럼 순차적으로 저장될 필요는 없음
	- 비선형 데이터 구조: 비선형의 순서로 저장, 접근되는 자료구조(트리, 그래프)

3. Abstract Data Type
	Abstract:
		n) A statement summarizing the important points of a text
		v) to take away; remove something
	
	Abstract Type: In programming languages, an abstract type is a type in a nominative type system that cannot be instantiated directly

	Abstract Data Type: In computer science, an abstract data type (ADT) is a mathematical model for data types. ***An abstract data type is defined by its behavior (semantics) from the point of view of a user***, of the data, specifically in terms of possible values, possible operations on data of this type, and the behavior of these operations.

	즉, 추상 데이터 형이란 사용자의 관점(상위 레벨)에서 특정 문제 해결을 위한 데이터와 연산의 선언으로 구성되며, 추상 데이터 형(ADT)의 정의 단계에서는 구체적 구현은 신경 쓰지 않는다.

	> 예를 들어 스택이라는 추상적 자료 구조를 다룰 때, 구체적 구현과 무관하게 나중에 들어온 데이터가 먼저 pop 된다는 사용자의 관점의 관심사만 존재함.
	
4. Summary
	- 데이터를 담는 단위가 변수(System Defined, User Defined)
	- 변수가 모아 관리하는 방식이 자료구조(Data Structure)
	- 자료구조와 추상적 연산에 포함된 것이 추상 자료구조 (Abstract Data Type)

