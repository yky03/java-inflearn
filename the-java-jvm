
### 더 자바, 코드를 조작하는 다양한 방법

## JVM 이해하기
- 자바 가상 머신으로 자바 바이트 코드(.class)를 OS에 특화된 코드로 변환(인터프리터와 JIT 컴파일러)하여 실행.  
- 바이트 코드를 실행하는 표준이자 구현체  
- JVM 벤더사 : 오라클,아마존,Azul 등...  
- 특정 플랫폼에 종속적  
- JDK(jconsole,javap 등.. + JRE) 안에 JRE(필수 라이브러리(rt.jar등) + JVM) 가 포함됨.  
- java11부터는 JDK만제공(JRE 따로 제공하지 않음)    
- JVM 구조  
-> 클래스 로더 시스템(바이트코드 로딩, 링크-레퍼런스연결, 초기화-static값들 초기화 및 변수에 할당)  
-> 메모리(스택(스레드마다 만들어짐 메소드 호출 스택 익셉션로그생각), PC(해당 스레드가 어느 위치를 가리키고 있는지), 네이티브 메소드 스택, 힙, 메소드! )  
-> 실행엔진(인터프리터(바이트코드를 한줄씩 실행), JIT컴파일러-인터프리터를 효율적으로 활용 가능(중복코드 등 네이티브 코드로 미리 바꿔둠), GC)  

-JNI  
C,C++,어셈블리로 만든 메소드 java에서 사용 가능 ex) Thread.currentThread(); // JNI(Java Native Intergace) 이나 직접 만들일 아마 없음 , 구현체는 네이티브 메소드 라이브러리라 칭함  

-GC 발생시마다 객체 이동  
Young Generation-MinorGC(Eden -> From Spac -> To Space) -> Old Generation - Major GC  

- [GC 이해하기 Young Generations](https://www.holaxprogramming.com/2013/07/20/java-jvm-gc/)  
- [백기선님 인프런 강의](https://www.inflearn.com/course/the-java-code-manipulation/lecture/)  
- [백기선님 강의 자료](https://docs.google.com/document/d/11zgALhqn3igwfs4xc9cYdRPlyS84M6ba_6xz0I2M-Ik/edit)   


## 바이트 코드 조작
코드 커버리지 측정
: 테스트 코드가 확인한 소스 코드를 %로 나타냄.


## 리플렉션

## 다이나믹 프록시

## 애노테이션 프로세서




