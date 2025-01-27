# sinc-algo-study

모 기업 신입들의 염원을 담아 만든 알고리즘 스터디입니다..

## 📌 스터디 진행 방식
1. 매주 월요일 오후 9시까지 문제들을 풀어와 스터디를 진행합니다.
2. 문제당 한 명씩 랜덤하게 골라 발표합니다.
    * 저번에 발표한 사람은 확률이 낮아질지도?
    * 문제는 `구현` 카테고리의 문제들을 주로 풀 예정입니다.
    * `문제 접근 과정`과 `문제 풀이 흐름`을 위주로 설명해주시면 됩니다.
3. 매 주 문제는 랜덤으로 한 명을 뽑아 출제합니다.

## 💻 풀 문제들 목록
<details markdown="1">
<summary>21.01.10 월요일</summary>

### 1. [[BOJ] 2615 오목](https://www.acmicpc.net/problem/2615)
* 구현, 브루트포스
* ![실버 2](https://img.shields.io/badge/%EB%B0%B1%EC%A4%80-SILVER%20II-lightgrey)
### 2. [[PGS] 81301 숫자 문자열과 영단어](https://programmers.co.kr/learn/courses/30/lessons/81301)
* 구현, 시뮬레이션
* ![LV. 1](https://img.shields.io/badge/%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%A8%B8%EC%8A%A4-Lv.%201-brightgreen)
* 2021 카카오 채용연계형 인턴십 - 1번 문제
### 3. [[PGS] 64061 크레인 인형뽑기 게임](https://programmers.co.kr/learn/courses/30/lessons/64061)
* 구현, 문자열 다루기
* ![LV. 1](https://img.shields.io/badge/%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%A8%B8%EC%8A%A4-Lv.%201-brightgreen)
* 2019 카카오 개발자 겨울 인턴십 - 1번 문제

</details>

<details markdown="1">
<summary>21.01.17 월요일</summary>

### 1. [[BOJ] 16926 배열 돌리기 1](https://www.acmicpc.net/problem/16926)
* 구현
* ![실버 2](https://img.shields.io/badge/%EB%B0%B1%EC%A4%80-SILVER%20II-lightgrey)
### 2. [[BOJ] 15685 드래곤 커브](https://www.acmicpc.net/problem/15685)
* 구현, 시뮬레이션
* ![골드 4](https://img.shields.io/badge/%EB%B0%B1%EC%A4%80-GOLD%20IV-yellow)
### 3. [[PGS] 60057 문자열 압축](https://programmers.co.kr/learn/courses/30/lessons/60057)
* 구현, 문자열 다루기
* ![LV.2](https://img.shields.io/badge/%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%A8%B8%EC%8A%A4-Lv.%202-yellow)
* 2020 KAKAO BLIND RECRUITMENT - 1번 문제

</details>

## ✅ Pull Requests 하는 방법

1. 이 repository를 본인의 github repository로 Fork합니다.
![1](https://user-images.githubusercontent.com/38418028/148671883-fbc924b8-8a8f-4c61-9f33-ae95bd4d7a23.png)

2. Fork받은 repository를 로컬에 clone합니다.
```shell
$ cd {clone받을 directory}
$ git clone https://github.com/{본인 계정}/algorithm.git
```

3. 문제를 풀고 본인 repository의 Fork받은 repository에 commit 및 push합니다.
    * 디렉토리 컨벤션은 `{본인 이름 or 하고 싶은 아이디}/{날짜(YYMMDD)}`로
    * 커밋 메시지는 적절히 작성해주세요. (예) [BOJ] 2615 오목
    * branch는 귀찮으니 master 그대로 하는걸로 합시다.

4. Pull Requests를 클릭합니다.
![2](https://user-images.githubusercontent.com/38418028/148672270-354af0c8-dfae-4317-8d8b-7ce5aee23647.png)

5. Create pull request를 클릭합니다.
![3](https://user-images.githubusercontent.com/38418028/148672308-f5fba2a9-6ffd-4ffd-9fb4-1b99c2c51421.png)
    * `base repository`와 `head repository`를 확인해주세요!
        * base repository는 `sinc-algo-study/algorithm`입니다.
        * head repository는 `{본인 계정}/algorithm`입니다.

6. Comment를 작성하여 Create pull request를 클릭하면 끝!
![4](https://user-images.githubusercontent.com/38418028/148672395-b3fc722c-a443-4df4-870f-50262dcd2e13.png)
    * Comment는 문제에 대한 `문제 접근 과정`과 `문제 풀이 흐름`에 대해 작성해주세요!

7. 본인이 작성한 Pull Requests를 merge 해주시면 됩니다.
    * 스터디원분들을 Maintainer로 등록했습니다. 직접 해주시거나 제가 머지 할게요😊
