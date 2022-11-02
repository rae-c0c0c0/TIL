### ✔️ 에러명
A JNI error has occurred, please check your installation and try again
***
### ✔️ 에러 화면
![화면 캡처 2022-11-02 165557](https://user-images.githubusercontent.com/113354023/199468626-465dd579-ab93-418a-9b04-987db2bb44d9.png)
***
### ✔️ 에러 원인
Java 언어 버전과 SDK의 버전이 달라서 발생하는 에러이다.
***
### ✔️ 해결
인텔리제이에 접속해서

**파일 ➡️ 프로젝트 구조 ➡️ SDK**

를 누른 후 SDK를 Java 언어에 맞는 버전으로 변경해 준다.

</br>

나는 현재 프로젝트를 Java 11로 개발중이라 SDK를 11로 바꾸어 주었다.

</br>

![화면 캡처 2022-11-02 170447](https://user-images.githubusercontent.com/113354023/199468766-8d909e03-2326-4460-b4f5-1ef5bd15ca17.png)

SDK 변경 이후 스프링부트가 정상적으로 작동하는 것을 확인할 수 있다.
