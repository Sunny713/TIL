# Markdown
```
마크다운은(markdown)은 일반 텍스트 기반의 경량 마크업 언어다.
```

쉽게 풀어서 일반 텍스트로 서식이 있는 문서를 작성하기 용이한 언어! <br>
마크다운의 확장자 명은 `.md` 로 되어있으며, 소프트웨어에 배포되는 README 파일에 주로 사용된다. <br>

## 마크다운 문법(syntax)
<br>

### 1. 제목(Header)
---
`<h1>`부터 `<h6>` 까지 사용할 수 있다.
<br>
```
# 제목1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6
```

제목1과 제목2는 아래와 같이 표현도 가능하다.

```
제목 1
======

제목 2
------
```
<br>

### 2. 강조(Emphasis)
---

`<em>`, `<strong>`, `<del>` 태그
밑줄은 `<u></u>` 태그
```
이텔릭체 :  *별표* 혹은 _언더바_
두껍게 : **별표** 혹은 __언더바__
**_이텔릭체_와 두껍게**를 같이 사용할 수 있다.
취소선 : ~~물결표시~~
<u>밑줄</u> 은 `<u></u>`
```

이텔릭체 :  *별표* 혹은 _언더바_ <br>
두껍게 : **별표** 혹은 __언더바__ <br>
**_이텔릭체_와 두껍게**를 같이 사용할 수 있다. <br>
취소선 : ~~물결표시~~ <br>
<u>밑줄</u> 은 `<u></u>`

<br>

### 3. 목록(List)
---

`<ol>`, `<ul>` 목록 태그로 변환된다.

```
1. 첫 번째 글
2. 두 번째 글
3. 세 번째 글
* 1번 글 얘기
   + 1-1 글
   + 1-2 글
* 2번 글 얘기
```

<br>

1. 첫 번째 글
2. 두 번째 글
3. 세 번째 글
* 1번 글 얘기
   + 1-1 글
   + 1-2 글
* 2번 글 얘기

<br>

### 4. 인용문구
---

```
> 인용1
> > 인용2
```
<br>

> 인용1
> > 인용2

<br>

### 5. 코드(Code) 삽입
---
`<pre>`, `<code>`로 변환된다. <br>
`"```"` 로 삽입할 수 있다.
```
 '```'
    코드내용1
    코드내용2
 '```'
```
<br>

### 6. 링크(Links)
---
1. 참조링크 

```
[link keword][id]

[id] : URL

// example
link : [google][googlelink]
[googlelink]: https://google.com "Go google"
```
link : [Google][googlelink] 

[googlelink]: https://google.com "Go google"

<br>

2. 외부링크

```
사용문법 : [Title](link)
적용예 : [Google](https://google.com,"google link")
```

link : [Google](https://google.com, "google link")

<br>

3. 자동연결
```
일반적인 URL 혹은 이메일주소인 경우 적절한 형식으로 링크를 형성한다.

* 외부링크: <http://example.com/>
* 이메일링크: <address@example.com>
```
* 외부링크: <http://example.com/>
* 이메일링크: <address@example.com>

<br>

### 7. 이미지
---
```
![Alt text](/path/to/img.jpg)
![Alt text](/path/to/img.jpg "Optional title")
```

사이즈 조절은 없기에 `<img width="" height""></img>`를 이용한다.

```
<img src="/path/to/img.jpg" width="450px" height="300px" title="px(픽셀) 크기 설정" alt="RubberDuck"></img><br/>
<img src="/path/to/img.jpg" width="40%" height="30%" title="px(픽셀) 크기 설정" alt="RubberDuck"></img>
```

