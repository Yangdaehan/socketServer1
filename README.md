## SocketProgram1

아래의 기능을 수행하는 C/S 방식의 소켓 프로그램

* 클라이언트에서는 사칙연산 수식을 텍스트로 입력
* 서버는 클라이언트로부터 받은 수식을 해석하여 연산을 하고 그 결과를 클라이언트에 반환
* 클라이언트는 전송된 연산 결과를 출력
  
* 서버는 수식의 형식이 잘못된 경우에는 에러메시지를 보낸다
    * 예시
      * ( 3 + 5  ) + 7 * 4   -> 36
      * ( 2 + 5 ? 3 - 7 * 4   -> Error:Invalid expression       

&nbsp;

&nbsp;
## 결과 창
<img width="1470" alt="스크린샷 2024-05-20 오후 11 58 55" src="https://github.com/Yangdaehan/socketServer2/assets/68599095/0152eff5-9731-42c6-95e2-7c27e696b5a8">

































