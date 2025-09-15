# flutter-
flutter 초보 상태 -> 개념 공부

라이브러리 뜯어쓰려니까 하나도 몰겠음. 충격 먹음.
1. 기본적인 flutter 작동 메커니즘.
2. stream, controller, listen, aysnc, final 등의 개념 암묵지 상태.

how I should do
1. 강의를 본다
2. 유튜브를 본다
3. 외운다
4. 라이브러리를 차근차근 읽어본다.
5. 이를 폭탄 목걸이가 내 목에 걸려있다 생각하고 하라.
-
-
-
개념 정리
-
a. class 
when using)
-> consist with variable and function
-
-
-
b. instance 
when using)
-> able to using class by naming
-
-
-
c. const 
when using)
-> before compiling, it should clarify
key point: 
if same information instance in the class, computer will aware same class and using same memory.
-
-
-
d. final 
-> while file running on the compiler, variable compiled
key point)
asame like static & dynamic concept
-
-
-
e. using getter between classes
-
-
-
f. function in function
form)
( ( ) { } ) callback function
why using?: 
parameter transform at the function -> conclutionly parent function get and work.
-
-
-
**important: if i have to coding whenever, just find at the inflearn video.
I fogot so many basic function..
-
-
-
g. controller
when using)
1. user gesture
2. user data
3. ui update
4. condition update
**5. data communicating**
-
-> just clarify contorller and handling them.
-
h. future
form)
Future <generic type> name async{ }
-> something will save at name with what I selected type at the future(usually case, server)
-
-
-
i. await
when using)
-> keep await method and return back find homework that cpu should calculate. 
if await method information arrive, next method start.
-
key point)
Using in the [Future< > name { }]form
-
-
-
j) stream
when using)
-> listen all update variable
-
form)
stream<generic type> name async { yield } (as same as return)
수신부는 name.listen( (ref) { } )
-
key point)
*yield -> should finish *yield method and next gogo
.
