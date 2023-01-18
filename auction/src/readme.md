<p align="center">
    <img src="img/auctionmain.png" alt="우아한테크코스" width="250px">
</p>

# 자바 1번째 프로젝 - 타임 옥션 

---

![Generic badge](https://img.shields.io/badge/precourse-week1-green.svg)
![Generic badge](https://img.shields.io/badge/test-2_passed-blue.svg)
![Generic badge](https://img.shields.io/badge/version-1.0.1-brightgreen.svg)

> 자바 자바 첫번째 프로젝트

<br>

<img src="./operation.gif">

# 목차

- [시작하기](#시작하기)
- [기능 목록](#기능-목록)
    - [문제 출제](#문제-출제)
    - [문제 풀기](#문제-풀기)
    - [정답 이후 처리](#정답-이후-처리)

## 시작하기

---

레포지토리를 Clone 하고 IDE에서 애플리케이션을 실행합니다.

```git
git clone -b as --single-branch https://github.com/hj-rich/java-baseball-precourse
```

---

## 기능 목록

### 문제 출제

- 1부터 9까지 서로 다른 임의의 수로 이루어진 3자리의 수가 생성된다

### 문제 풀기

- `숫자를 입력해주세요 : ` 가 콘솔에 출력된다
- 사용자로부터 서로 다른 3자리의 수를 입력 받는다
    - 잘못 입력된 경우 `IllegalArgumentException`을 발생시키고 애플리케이션을 종료시킨다
    - 정상 입력된 경우 입력에 따른 결과를 판정한다
        - `1볼 1스트라이크` 와 같이 볼과 스트라이크 갯수를 표기한다
        - 하나도 맞추지 못했을 때에는 `낫싱` 을 표기한다

### 정답 이후 처리

- 정답을 맞췄을 때에는 `3스트라이크`에 추가로 게임 종료 메시지 출력 및 재시작 분기를 시작한다