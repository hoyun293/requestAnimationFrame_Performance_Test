# requestAnimationFrame을 이용한 렌더링 최적화

640개의 div태그에 기하학적 변경을 주어 렌더링 소요시간을 확인

**비교방식**

- With layout thrash 레이아웃 스레싱 발생 방식
- Without layout thrash 레이아웃 스레싱 방지 방식
- Done at vDOM 가상돔을 사용한 방식

**퍼포먼스 속도**

1.가상돔 방식

2.레이아웃 스레싱 방지 방식

3.레이아웃 스레싱 발생 방식

![image](https://user-images.githubusercontent.com/23381445/214271360-e1f4488e-a592-4d52-bdb0-a3afe0d70946.png)
