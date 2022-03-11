# 제목(Header)

# 제목1

## 제목2

### 제목3

#### 제목4

##### 제목5

###### 제목6

# 문장(paragraph)

동해물과 백두산이 마르고 닳도록

# 강조(Emphasis)

_이텔릭_  
**두껍게**
**_이텔릭+두껍게_**

# 목록(List)

1. 순서가 필요한 목록
   1. 순서가 필요한 목록
1. 순서가 필요한 목록

- 순서가 필요하지않는 목록
- 순서가 필요하지않는 목록
  - 순서가 필요하지않는 목록
- 순서가 필요하지않는 목록


# 링크(Links)

<a href = "https://google.com">GOOGLE</a>  
[GOOGLE](https://google.com)  
[GOOGLE](https://google.com "구글 홈페이지로 이동")

[!GOOGLE_IMAGE](https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png)

[[!GOOGLE_IMAGE](https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png)](https://google.com)


# 인용문

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
> (네이버 국어 사전)


# 인라인 코드 강조

css에서 `background` 혹은 `background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.

# 블록 코드 강조
```html
<a href = "https://google.com">GOOGLE</a> 
```
```css
.list > li {
  position: absolute;
  top:40px;
}
```

```javascript
function func() {
  const a = 'AAA';
  return a;
}
```

```plaintext
동해물과 백두산이 마르고 닳도록
```

```bash
$ git commit -m 'Study Markdown'
```


# 표(Table)

position
값 | 의미 | 기본값
:--:|:--:|:--:
static | 기준 없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X

# 원시 HTML(Rav HTML)

동해물과 <span style = "text-decoration: underline;">백두산</span>이 마르고 닳도록<br>
하느님이 보우하사 우리나라 만세

1. <a href = "https://naver.com" title = "NAVER로 이동" target = "_blank">NAVER</a> 

```plaintext
원시 HTML을 쓰면 Markdown의 링크 문법에서 사용하지 못한 target속성을 사용할 수 있다.(그외 다양한 프로퍼티사용가능)
```


2. <img src = "https://google.com" alt = "Google_Logo"/> 
```plaintext
원시 HTML을 쓰면 Markdown의 이미지 문법에서 사용하지 못한 width 속성을 사용할 수 있다.(그외 다양한 프로퍼티사용가능)
```
# 수평선(Horizontal Rule)

---

***

___