# Go

## main.go
컴파일을 하기위해서는 필수인 파일이다  
만약 공유를 위한 목적이라면 꼭 main.go 파일이 필요한 것은 아니다.  

## package main
C나 JAVA와 같이 public static void main 처럼 컴파일을 하기 위해서는 main함수가 필요로 하다.   
이를 위해 package main 을 해주고, func main(public static void main)을 사용해 준다.

```
다른 package에 있는 함수를 사용하고 싶을 때 import를 하고   
그 함수는 package에서 함수명의 맨 첫번째 자리는 대문자로 표시되어야
export할 수 있다. (소문자는 private으로 친다.)
```
