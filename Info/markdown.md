# 마크다운(MarkDown) 정리

[ 마크다운 장점 ]

문법이 간결하고 쉽다.
마크다운은 모든 것에 사용할 수 있습니다. (웹 사이트, 문서, 메모, 기술 문서 등)
마크다운은 지원하는 플랫폼이 많습니다. ( Github, Discord 등)
마크다운은 대부분의 환경에서 편집, 작성이 가능합니다. (메모장에서도 가능)
텍스트로 저장되기 때문에 용량이 적어 보관이 용이합니다.
 

[ 마크다운 단점 ]

모든 HTML의 문법을 대신하지 못합니다.
표준이 없기 때문에 도구에 따라 변환방식 또는 생성물이 다릅니다.
마크다운으로 파일 업로드하는 경우 저장한 다음 파일 경로를 입력해야되는 불편함
tistory, naver blog, notion과는 다르게 문법들을 하나하나 입력해야되는 경우가 있어 귀찮음이 조금 있습니다.

# Headers 헤더
This is an H1
===
This is an H2
---

# This is an H1
## This is an H2
### This is an H3
#### This is an H4
##### This is an H5
###### This is an H6

# Horizontal Rules 수평선

* * *
***
*****
- - -
-------------------

# Line Breaks 줄바꿈
aaaaaaa
rrrrrrrrr <br>
cccccccc
bbbbb

asdasdasdasd <br>
dbdbdbdbdbdb


# Emphasis 강조

_This will also be italic_

**This will also be bold**

~~This is canceled~~

_You **can** ~~combine~~ them_


# Blockquotes 인용

As Grace Hopper said:
> I’ve always been more interested in the future than in the past.    
> This is a first blockquote.
> > This is a second blockquote.
> > > This is a third blockquote.

> # this is h1!
> * list
> `textbox`

# Lists 목록

## Unordered lists 순서가 없는 목록
* 머리
  * 코
    * 입
      

+ 머리
  + 코
    + 입
      * 입

- 머리
- 코
- 입

## Ordered lists 순서가 있는 목록

1. 머리
2. 다리
3. 뚝배기
5. 팔 <!-- 5번을 썻는데도 4번으로 표시된다. -->

--- 

1. 리스트 1번 
    1. 리스트 1-1번
2. 리스트 2번 
3. 리스트 3번 
    1. 리스트 3-1번 <!-- 리스트 안 리스트를 사용하려면 tab과 함꼐 숫자 1번 서부터 -->
    2. 리스트 3-2번

1. 머리
   * 머리카락
   * 뚝배기
      + 털
2. 다리
   - 다리털
   - 발가락
      1. 허벅지


# Backslash Escapes

* 특수문자 출력안됨
- 특수문자 출력안됨

\* 특수문자 출력

\- 특수문자 출력

\*literal asterisks\*

\#hash mark\#

\[squre brackets\]

# 이미지 

![텍스트](이미지파일경로.jpg)
![텍스트](이미지파일URL)

## 이미지 파일에 마우스를 올렸을 때 커서 옆에 나오는 텍스트 설정

![텍스트](이미지파일경로.jpg "이미지이름") 
![텍스트](이미지파일URL "이미지이름")


## 링크와 이미지를 합친 문법 (이미지를 링크로 사용)

[ ![텍스트](이미지URL) ]( 링크URL )

[![텍스트](https://t1.daumcdn.net/cfile/tistory/2444873B57E257821F)](https://unity3d.com/kr)

## <img>태그를 이용한 이미지 크기 조절
<img src="https://i1.sndcdn.com/avatars-000639959556-jhitcq-t500x500.jpg" width="200" height="200" />

<!-- a태그를 이용한 이미지 링크 생성법-->
<a href="#">
	<img src="https://github.com/images/markdown_syntax.jpg" width="400px" alt="sample image">
</a>

## Links (Anchor) 링크

### 외부 링크
[Google](http://www.google.com "구글")

[Naver](http://www.naver.com "네이버")

[Github](http://www.github.com "깃허브")

구글 www.google.com

네이버 <www.naver.com>

My mail <jinkyukim.dev@gmail.com>






### 출처  
https://inpa.tistory.com/entry/MarkDown-%F0%9F%93%9A-%EB%A7%88%ED%81%AC%EB%8B%A4%EC%9A%B4-%EB%AC%B8%EB%B2%95-%F0%9F%92%AF-%EC%A0%95%EB%A6%AC#%EB%A7%88%ED%81%AC%EB%8B%A4%EC%9A%B4_(MarkDown)_%EC%9D%B4%EB%9E%80