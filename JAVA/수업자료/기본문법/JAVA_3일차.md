### 배열을 사용하는 이유
    만약 변수를 100번 만들어야 한다고 가정하자.
    int a = 10, int b = 10 .... (98번 더 작업해야함.)
    배열을 사용하면 한번 선언으로 여러 데이터를 넣을 수 있다.

### 배열이란
    배열은 인덱스와 인덱스에 대응하는 일련의 데이터로 이루어짐.

### 배열 문법
    int(배열 데이터타입) array(배열 변수이름) []()배열 선언
    ex) int array [] = {10, 7, 9} 
    0번째 인덱스에는 10 데이터 // 배열은 0번째 부터 시작한다.(주의)
    1번째 인덱스에는 7 데이터
    2번째 인덱스에는 9 데이터

    배열의 총 길이는 3!

### 배열 예제
    - 배열은 반복문이랑 같이 사용하므로, 반복문이 어려웠다면 다시 공부하고 오자!
```java
    int 배열[] = {10,3,5};
    System.out.println(배열[2]); //2번째 인덱스 데이터 호출
    System.out.println(배열.length); //배열 길이 호출
    System.out.println(배열[4]); //에러 발생! 인덱스 길이는 총 3인데 4를 호출! 
```

```java
    int 배열[] = {10,3,5};
    배열[0] = 5; // 0번째 배열에 5 대입!
    배열[1] = 배열[1] * 3; // 1번째 인덱스 값 3을 3곱합 그 결과를 1번째 인덱스 값에 다시 대입
    배열[1] = 배열[0] + 배열[2]; // 0번째 인덱스값과 2번째 인덱스값을 더한 결과를 1번째 인덱스 값에 대입
```

```java
    int 배열[] = {10,3,5};
    int x = 20;
    배열[1] = x; // x값 20을 배열 1번째 인덱스에 대입
```

```java
    int 배열[] = {10,3,5};
    if(배열[0] == 10){
        System.out.println("Hello World"); //0번째 인덱스 값과 10일 맞다면 Hello World 출력!
    }
```

```java
    int 배열[] = {10,3,5};
    for(int i=0; i<배열.length; i++){ //배열 길이만큼 반복해라!
        System.out.println(배열[i]); //0번째부터 배열길이만큼 인덱스 값을 출력!
    }
```