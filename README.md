# Header

# title 1

## title 2

### title 3

- '#' 은 6개까지 가능
- '\#' 다음에 띄어쓰기 꼭 쓰자
-

# Paragraph

동해물과 백두산이 마르고 닳도록 하느님이 보우하사 우리나라 만세

### 줄바꿈

1. 띄어쓰기 두번 (해석되지 않는 경우도 있다.)
2. \<br/> 사용

# 강조

_이텔릭_  
**두껍게**  
**_이텔릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u>

# 목록

1. 순서가 필요한 목록
2. 순서가 필요한 목록
   1. 순서가 필요한 목록
3. 순서가 필요한 목록
   <br/> <br/>

- 순서가 필요치 않은 목록
  - 순서는 필요치 않은 목록
- 순서가 필요치 않은 목록

# Links

<a href="https://google.com" title="구글로 이동">Google</a>

[Google](https://google.com '구글로 이동')

# Image

이미지
![대체텍스트](https://cdn.pixabay.com/photo/2020/07/06/01/33/sky-5375005_1280.jpg)

이미지 클릭 시, 링크 이동
[![대체텍스트](https://cdn.pixabay.com/photo/2020/07/06/01/33/sky-5375005_1280.jpg)](https://pixabay.com/images/id-5375005/)

# 인용문

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.(네이버 국어사전)

- \> 다음에 띄어쓰기
- 중첩 기능 가능

  > 첫 째
  >
  > > 둘 째
  > >
  > > > 셋 째

# 인라인 코드 강조, Inline Code

CSS의 `background-color`는 색상을 지정할 수 있어요.

- backtick(\`)사용

# 블록 코드 강조, Block Code

```html
<a href="https://google.com" title="구글로 이동">Google</a>
```

```shell
$ git commit -m 'Study markdown'
```

# 표, Table

### position 속성

| 값       |      의미       | 기본값 |
| -------- | :-------------: | -----: |
| static   |    기준 없음    |      O |
| relative |    요소 자신    |      X |
| absolute | 위치상 부모요소 |      X |
| fixed    |    viewport     |      X |

- cell text align : default(왼쪽 정렬)
  - 변경 '\:' (콜론) 사용

# Raw HTML(원시 HTML)

markdown은 원시 html로 변환된다.

- `<br/>`
- `<u></u>`
- `<span style="text-decoration: underline;" >밑줄</span>`

# 수평선 (Horizontal Rule)

---

---
