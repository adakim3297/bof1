Buffer Overflow
# bof1
gets 함수나 strcpy함수는 입력받은 값을 버퍼에 저장할때 데이터 길이와 상고나없이 stack에 복사한다.


## Buffer Overflow 예시
<img src=https://www.imperva.com/learn/wp-content/uploads/sites/13/2018/01/buffer-overflow.png width ="400" height="120"/>

#bof1.c의 코드 내용

<img src = https://user-images.

* 코드내의 innocent와 key의 값 중점
* key값이 0x61616161
* call에서 gets 함수를 찾는다


<과정 1>
![img](https://github.com/adakim3297/bof1/blob/main/bof1.c%20%EC%BD%94%EB%93%9C%20%EB%82%B4%EC%9A%A9.png?raw=true)


<과정 2>
![img](https://github.com/adakim3297/bof1/blob/main/bof1-1.png?raw=true)


<과정 3>
![img](https://github.com/adakim3297/bof1/blob/main/bof1-2.png?raw=true)