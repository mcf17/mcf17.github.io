---
title: "Sample Post (시험용 페이지)"                                 
excerpt: "This is a sample post. 마크다운 시험용 페이지입니다."       
categories:                                                          
  - Sample Post
tags:                                                              
  - [Sample, Blog]

toc: true
toc_sticky: true

date: 1970-01-01
last_modified_at: 2023-02-05

sidebar:
    nav: "categories"
---

포스팅 규칙:

1. 포스팅 파일 명은 `YYYY-MM-DD-{post_name}.md` 형식으로 해야 하며, `post_name`의 경우 대문자를 소문자로 변환한 뒤 띄어쓰기를 `-`로 붙여서 써야한다. 
2. 포스팅 파일의 YAML 헤더에는 permalink가 불필요 하나, category 페이지에서는 permalink를 명시해야함. 


# 테스트

시험용 헤더입니다. 

## MathJax 테스트

- 인라인 수식 : \\( \int_0^x f(t) dt = \sin x \\)
- 인라인 수식이지만 디스플레이 모드 : \\( \displaystyle \int_0^x f(t) dt = \sin x \\)
- 디스플레이 수식 : 

\\[
    \int_0^x f(t) dt = \sin x \implies f(t) = \cos t.
    \\]

또 다른 수식

$$
f(x) = 3
$$

$v+2 = \alpha$. 

## 텍스트 정렬

Left aligned text.
{: .text-left}

Center aligned text.
{: .text-center}

Right aligned text.
{: .text-right}

## 텍스트 색깔 (HTML)

- 색깔 : <span style="color: #088A68"> 색깔 </span>
- 색깔 + 굵게 : <span style="color:#088A68"><b>글자색 입히기</b></span>

## 텍스트 블록

{% capture notice-2 %}
**Definition**. 주어진 집합 $X$ 상의 **위상** (topolopgy on $X$)은 다음 조건을 만족하는 $X$의 부분집합족 $\mathcal O$이다. 
1. $\emptyset, X \in \mathcal O$.
2. $\mathscr U \subseteq \mathcal O \implies \bigcup \mathscr U \in \mathcal O$,
3. $U,V \in \mathcal O \implies U\cap V \in \mathcal O$.
{% endcapture %}

<div class="notice">{{ notice-2 | markdownify }}</div>

## 이미지
![image](https://mcf17.github.io/assets/images/xxx.xxx){: width="20%" height="20%" .align-center}   
