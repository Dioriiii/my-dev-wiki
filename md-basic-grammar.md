마크다운(Markdown) 기본 문법 빠른 가이드
아래 예시는 GitHub, VS Code 미리보기 기준으로 잘 동작하는 문법입니다. 바로 복붙해서 참고해도 됩니다.

제목(Headings)

# 개수로 레벨 지정(H1~H6)

text

# 제목 1

## 제목 2

### 제목 3

#### 제목 4

##### 제목 5

###### 제목 6

강조(Emphasis)
text
기울임: _text_ 또는 _text_
굵게: **text** 또는 **text**
굵게+기울임: **_text_** 또는 **_text_**
취소선: ~~text~~
목록(Lists)
순서 없는 목록: -, \*, + 중 하나 사용

순서 있는 목록: 1. 2. 3. …

text

- 항목 A
- 항목 B
  - 하위 항목 B-1

* 항목 C

- 항목 D

1. 단계 1
2. 단계 2
   1. 하위 단계 2-1
      체크박스(Tasks)
      text

- [ ] 할 일 1
- [x] 완료한 일 2
      인용문(Blockquote)
      text
  > 인용문 1줄
  > 인용문은 여러 줄도 가능합니다.
  >
  > > 중첩 인용문
  > > 코드(Code)
  > > 인라인 코드: 백틱 1개

코드 블록: 백틱 3개 + 언어명

text
인라인 `console.log('hi')`

function add(a, b) {
return a + b;
}

text
undefined
링크(Links)
text
[표시 텍스트](https://example.com)
[표시 텍스트](https://example.com "툴팁")
<https://example.com> <!-- 자동 링크 -->
이미지(Images)
text
![대체텍스트](https://example.com/image.png)
![대체텍스트](https://example.com/image.png "툴팁")
이미지에 링크 걸기:

text
[![alt](https://example.com/thumb.png)](https://example.com)
수평선(Horizontal Rule)
text

---

---

---

표(Tables)
text
| 열1 | 열2 | 열3 |
| --- | --- | --- |
| A | B | C |
| 1 | 2 | 3 |

정렬:
| 좌 | 중 | 우 |
| :-- | :-: | --: |
| a | b | c |
줄바꿈(Line Break)
문장 끝에 스페이스 2칸 후 엔터, 또는 빈 줄 삽입

text
한 줄  
다음 줄
각주(Footnotes) – GitHub Flavored Markdown 지원
text
문장에 각주를 달아요[^1].

[^1]:
    여기 각주 내용입니다.
    접기/펼치기(details) – GitHub 지원
    text

<details>
  <summary>더보기</summary>
  숨겨진 내용입니다.
</details>
이모지(Emoji)
GitHub 스타일: :sparkles: :rocket: :memo: 처럼 콜론 사용

또는 OS 이모지 직접 입력

수식(Math) – 확장 플러그인/플랫폼별 상이
GitHub 이슈/PR 코멘트에서 일부 지원, VS Code는 확장으로 미리보기 가능

text
인라인: $E = mc^2$
블록:

$$
\int_0^1 x^2 dx = \frac{1}{3}
$$

주석(HTML 주석)
text

<!-- 렌더링에 보이지 않는 주석 -->

경고/정보 박스(Admonitions) – 정적 사이트/확장 플러그인에서 주로 지원
일반 Markdown 표준은 아님. GitHub에서는 인용문+이모지로 대체:

text

> ⚠️ 주의: 중요한 안내문
> ℹ️ 정보: 참고 사항
> 깔끔한 학습 노트 템플릿 예시
> text

# [주제/강의명] - YYYY-MM-DD

## 요약

- 핵심1:
- 핵심2:
- 핵심3:

## 개념 정리

- 용어/개념:
- 포인트:
- 주의할 점:

## 코드/실습

// 예제 코드

text

## 트러블슈팅

- 현상:
- 원인:
- 해결:

## 참고/링크

- 문서/글 제목

## 회고

- 오늘 배운 점:
- 내일 할 일:
