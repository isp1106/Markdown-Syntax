# Markdown-Syntax

# 제목(Header)

# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6


# 문장(Paragraph)

동해물과 백두산이 마르고 닳도록 
하느님이 보우하사 우리나라 만세

# 줄바꿈(Line Breakes)
동해물과 백두산이 마르고 닳도록   
하느님이 보우하사 우리나라 만세<br/>
무궁화 삼천리 화려 강산

# 강조(Emphasis)
_이탤릭_   
**두껍게** 
**_**이탤릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u>

# 목록(List)
1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록
1. 순서가 필요한 목록  
</br>

- 순서가필요하지 않은 목록
- 순서가필요하지 않은 목록
  - 순서가필요하지 않은 목록
- 순서가필요하지 않은 목록


# 링크(links)
<a href="https://google.com">GOOGLE</a>

[GOOGLE](https://google.com)

<a href="https://naver.com" title="NAVER로 이동!">NAVER</a>

[NAVER](https://naver.com "NAVER로 이동!")

# 이미지(Images)

![CHUNSIK](https://item.kakaocdn.net/do/b5d3d6a7b67fbf5afdaffb79fffbf8b18f324a0b9c48f77dbce3a43bd11ce785)

[![CHUNSIK](https://item.kakaocdn.net/do/b5d3d6a7b67fbf5afdaffb79fffbf8b18f324a0b9c48f77dbce3a43bd11ce785)](https://www.google.com/)

# 인용문(BlockQuote)
> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.
> 인용문을 작성하세요!
>> 중첩된 인용문
>>> 중중첩된 인용문 1
>>> 중중첩된 인용문 2
>>> 중중첩된 인용문 3

# 인라인(inline) 코드 강조
CSS에서 `background` 혹은 `background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.

# 블록(block) 코드 강조

```html
<a href="https://naver.com" target="_blank">NAVER</a>
```

```css
.list > li {
  position: absolute;
  top: 40px;
}
```

```javascript
function func() {
  var a = 'AAA'
  return a;
}
```

```bash
$ git comit -m 'Study Markdown'
```

```plaintext
동해물과 백두산이
```

# 표(table)

position 속성
값 | 의미 | 기본값
--|:--:|:--:
static | 기준 없음 | O
relative | 요소 자신 | X


# 원시 HTML(Raw HTML)
동해물과 <span style="text-decoration: underline;">백두산</span>


# 수평선(Horizotal Rule)

---
***
___
