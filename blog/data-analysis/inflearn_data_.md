---
layout: post
title:  "인프런 지식 공유자는 이런 데이터가 궁금해요!"
subtitle: "알고 싶은 데이터부터 활용 방안까지"
type: "Data Analysis"
blog: true
text: true
author: S
post-header: 
header-img: 
order: 0
---

<br>

<p id = "top-section">
안녕하세요, 데이터리안 강의 기획자 S 입니다.
</p>


데이터리안이 '*[백문이불여일타] 데이터 분석을 위한 기초 SQL*'로 인프런에서 강의를 시작한 지도 벌써 1년이 넘었습니다. <br>
그동안 데이터리안 강의는 총 여섯 개가 되었고, 총 수강생은 삼천 명을 넘었네요. <br>
데이터리안 강의를 수강해주신 모든 분, 앞으로 수강해주실 모든 분, 그리고 항상 많은 도움을 주시는 인프런 관계자분들께 감사의 말씀을 전합니다.

<br>

감사 인사로 글을 시작하게 되었는데, 오늘은 지식 공유자로서 👩‍💻<b><ins>인프런 강의 데이터</ins></b>👩‍💻에 관한 이야기를 해보려고 합니다. <br>
인프런에서 활동하는 지식 공유자들은 대시보드 기능을 통해 `수강생 수`, `수익 현황` 등 강의 결제 관련 지표를 확인할 수 있습니다. 

<br>

> **참고** <p>
아래 화면은 실제 대시보드에서 `판매액` 등의 민감 정보를 제외한 화면입니다.

<p align = center>
<img src = "./img/inflearn_dashboard.png" alt = "인프런 대시보드" width = 400>
</p>

<br>

이번 달에는 `어떤 강의에서 어느 정도의 수익이 발생`했는지, `지난 1년간 수익 현황`은 어땠는지 등 많은 정보를 살펴볼 수 있습니다. <br>
현황을 보다보니, 수강생들의 이용 현황 등 더 다양한 종류의 지표를 보면 좋겠다는 생각이 들었습니다. <br>
데이터리안이 데이터 분석가 커뮤니티인 만큼, <b><ins>지식 공유자로서 확인하고 싶은 지표</ins></b>와 <b><ins>이를 통해 할 수 있는 액션</ins></b>에 대해 고민한 내용을 공유합니다. <br>



<br><br>

## *next..*
[<span style = "color:#537ec5"><b><ins>1. 데이터리안 강의를 어떻게 알게 되었을까?</ins></b></span>](#paragraph-1)

- 1-A. 강의 유입 경로 비중
- 1-B. 강의 구매 ~ 실제 수강 사이의 기간과 실제 수강 비중


[<span style = "color:#537ec5"><b><ins>2. 강의 수강 중 어려운 점은 무엇일까?</ins></b></span>](#paragraph-2)

- 2-A. 영상별 반복 재생 횟수
- 2-B. 음량, 재생 속도 변경 횟수 및 전체 재생 수 대비 그 비중
- 2-C. 완강률 & (완강하지 않은 채 이탈한 경우) 이탈한 지점



[<span style = "color:#537ec5"><b><ins>3. 이후에도 다른 데이터리안 강의를 계속 수강할까?</ins></b></span>](#paragraph-3)

- 3-A. '*[백문이 불여일타] 시리즈*' 내의 다음 강의를 이용하는 수강생 비중 
- 3-B. '*[백문이 불여일타] 시리즈*' 완강 이후 '*추천 시스템*' 강의 등록 비중 (혹은 그 반대 경우의 비중)


<br><br>

---

<br>

<h3 id = "paragraph-1">
 <b>1. 데이터리안 강의를 어떻게 알게 되었을까?</b>
</h3>

<br>

> **<ins>1-A. 강의 유입 경로 비중</ins>**

데이터리안 강의를 수강해주신 분들은 저희 강의를 어떻게 알게 되었을까요? <br>
지금 이 글이 올라와 있는 데이터리안 블로그를 통해 알게 되었을 수도, 혹은 인프런 내에서 `SQL`, `데이터 분석` 등의 키워드를 검색하여 알게 되었을 수도 있을 것입니다. 

<br>

<p align = center>
<img src="./img/inflearn_sql_search_result.PNG" alt="인프런 내 SQL 검색 결과" width="500">
</p>

<br>

수강생의 유입 경로를 데이터로 파악할 수 있다면, 데이터리안은 이런 액션을 해볼 수 있겠네요. 
1. 인프런 내에서 검색을 통한 유입이 많다면? 
    - 강의에 여러 키워드를 추가하여, 지금 보다 더 다양한 검색 결과에서 데이터리안 강의가 노출될 수 있도록 한다.
2. [<span style = "color:#537ec5"> 데이터리안 블로그 </span>](https://datarian-kr.github.io/) 혹은 [<span style = "color:#537ec5"> 인프런 블로그 </span>](https://www.inflearn.com/users/@datarian/blogs)를 통한 유입이 많다면?
    - 블로그에 더 자주 글을 업로드 한다.
    - 블로그 글이 더 많이 퍼질 수 있도록 여러 커뮤니티에 홍보한다.

현황을 확인하고 액션을 했다면 실제 효과를 확인해볼 차례겠네요. 액션 이후에 해당 경로를 통한 유입이 늘었는지를 계속 확인하며 효과를 분석해볼 수도 있을 것입니다.



<br><br>

> **<ins>1-B. 강의 구매 ~ 실제 수강 사이의 기간과 실제 수강 비중</ins>**

수강생분들이 강의를 구매하고 실제로 공부를 시작하기까지의 기간은 얼마나 될까요? 그리고 실제 수강 비중은 전체 구매 고객의 몇 퍼센트일까요? <br>
AARRR 방법론에 따라 나눠보자면, 강의 구매는 `Acquisition`, 실제 수강은 `Activation` 이라고 할 수 있습니다. 이 `Activation`이 일어나기까지 얼마나 걸리는지, 즉 공부하고자 하는 마음이 들었을 때 강의를 구매해서 바로 수강을 하는지 혹은 미리 구매하고 나중에 시간이 될 때 수강을 시작하는지 궁금하네요.<br>
이 데이터는 확인할 수 없지만, 인프런측에서 제공해주시는 결제 데이터를 보며 발견한 한 가지 패턴이 있습니다. <br>
강의 할인을 하지 않을 때보다, <u>강의 할인이 진행되는 특정 기간에 구매가 증가한다는 점</u>입니다.
<br> 

<p align = center>
<img src="./img/inflearn_promo_example.PNG" alt="인프런 프로모션 예시" width="300">
</p>

<br>

더욱더 재미있는 부분은, 할인이 종료되는 마지막 날에 가장 많이 구매한다는 것입니다. <br>
이런 데이터를 보면, 할인 기간에 미리 강의를 구매하고 강의 수강은 나중에 하지 않을까 하는 생각이 드네요 :) <p>


<br><br>

<h3 id = "paragraph-2">
 <b>2. 강의 수강 중 어려운 점은 무엇일까?</b>
</h3>

<br>

> **<ins>2-A. 영상별 반복 재생 횟수</ins>**

인프런 강의는 여러 섹션으로 묶인 영상으로 구성되어 있습니다. 이 중에서 `어떤 영상을 가장 많이 반복 재생`하며, `반복 재생을 많이 하는 영상은 어떤 섹션에` 가장 많을까요? <br>
반복 재생이 많은 영상 혹은 섹션이 있다면, 해당 영상의 난이도와 관련 질문 등록 수 등을 확인하여 영상 하단에 보충 설명을 추가하는 등의 액션을 해볼 수 있을 것입니다. 현재는 영상 재생 관련 데이터를 확인할 수 없으므로, 질문 주신 내용을 바탕으로 특별히 질문이 많이 들어오는 영상에 보충 설명을 덧붙이기도 했습니다.


<br><br>

> **<ins>2-B. 음량, 재생 속도 변경 횟수 및 전체 재생 수 대비 그 비중</ins>**

데이터리안 SQL 강의 수강평에는 음량이나 설명 속도 등에 대한 피드백이 종종 있는데요, 영상마다 촬영 시점이나 환경이 다를 수 있으므로 불편을 느끼시는 부분을 데이터로 더욱 정확하게 확인할 수 있으면 좋겠다는 생각이 들었습니다. 

<br><br>

<p align = center>
<img src="./img/speed_volume_section.png" alt="속도, 음량 변경 기능" width="500">
</p>


1. 어떤 영상에서 음량이나 재생 속도를 조정하는 횟수가 많은지 ( = 영상별 조정 횟수)
2. 작게/느리게 조정을 하는지 혹은 크게/빠르게 조정을 하는지 ( = 변경 내역 )

와 같은 데이터를 확인할 수 있다면, `해당 영상의 전체 재생 수 대비 변경 횟수` 등을 집계하여 영상별 변경 비율을 알아볼 수 있을 것입니다. 수치를 확인한 후에는 변경 비중이 높았던 영상을 직접 확인해보고, 강의의 음량이나 속도가 다른 강의와 어떻게 다른지 확인해볼 수 있겠네요. <br>
이런 식으로 데이터를 활용할 수 있다면, 앞으로 새로운 강의를 준비할 때는 많은 분이 원하는 음량 혹은 재생 속도로 편집하여 제공할 수 있지 않을까 생각합니다.

<br><br>

> **<ins>2-C. 완강률 & (완강하지 않은 채 이탈한 경우) 이탈한 지점</ins>**

강의를 처음부터 끝까지 모든 영상을 시청한, 즉 완강한 비율은 얼마나 될까요? 만약 완강하지 않고 이탈했다면, 어떤 지점에서 이탈했을까요? 각 수강생이 수강한 영상과 그 날짜를 확인할 수 있다면, 완강한 고객 및 그렇지 않은 고객을 확인할 수 있을 것입니다. <br>
실제로 데이터를 확인할 수는 없지만, 확인할 수 있다고 가정한다면 먼저 두 가지를 고민해봐야 합니다. <br>
1. 이탈한 '지점'을 무엇으로 정의할 것인가?
2. 어느 정도의 기간 내에서 이탈 여부를 판단할 것인가?

저희는 데이터리안 강의만을 대상으로 하므로 강의 결제까지의 퍼널보다는, 그 이후의 수강 현황이 더 중요합니다. 따라서 1번의 '**이탈 지점**'은 특정 '영상'을 기준으로 할 수 있을 것입니다. 완강하지 않은 고객이 `어떤 영상을 마지막으로 시청하고 이탈하였는지`를 살펴볼 수 있겠네요. <br>
그렇다면 여기서 이탈 여부를 판단하는 '**기간**'은 어느 정도가 적당할까요? <br>
<ins>수강 기간을 3개월로 제한한 강의</ins>는, 강의 결제 이후 3개월 이내에 완강하지 않은 고객을 이탈 고객으로 볼 수 있을 것이고, 해당 고객이 마지막으로 본 영상이 이탈 지점이 되겠네요. <ins>수강 기간이 무제한인 강의</ins>는 이보다 더 길게 기간을 제한할 수도 있고, 혹은 동일하게 3개월로 잡아 강의 별 이탈률을 비교해볼 수도 있겠습니다.


<br>
<br>

<h3 id = "paragraph-3">
 <b>3. 이후에도 다른 데이터리안 강의를 계속 수강할까?</b>
</h3>

<br>

> **<ins>3-A. '*[백문이 불여일타] 시리즈*' 내의 다음 강의를 이용하는 수강생 비중</ins>**

많은 분이 사랑해주시는 '[백문이 불여일타] 시리즈'는 기초 ~ 고급 SQL 부터 문제 풀이 강의까지 총 다섯 강의로 구성되어 있습니다. 기초부터 고급까지 난이도 순서대로 수강하시는 분들의 비중은 얼마나 될까요? 
<br>

<p align = center>
<img src = ./img/datarian_sql_list.PNG alt = "데이터리안 SQL 강의 목록" width = 300>
</p>

종종 '*다음 강의를 들으러 간다* '거나 '*기초부터 고급까지 완강했다* '라는 수강평을 남겨주시는 분들이 계십니다. 데이터리안 강의를 믿고 끝까지 함께 해주셨다는 점에서 항상 감사드리며, 이런 흐름대로 수강하시는 수강생분들이 얼마나 계실지도 궁금해졌습니다. <br>
만약 이 비중을 확인할 수 있다면, `시리즈가 완성되지 않았을 때와 시리즈가 완성된 이후에 다음 강의를 구매하는 비율`이 차이가 나는 지를 확인해 볼 수 있을 것입니다. 만약 시리즈 완결 이후 다음 강의로 전환되는 비중이 높다면, 앞으로 시리즈 강의를 제작할 때는 다음 강의가 최대한 빨리 나올 수 있도록 하는 것이 중요하겠네요. <br>



<br><br>

> **<ins>3-B. '*[백문이 불여일타] 시리즈*' 완강 이후 '*추천 시스템*' 강의 등록 비중 (혹은 그 반대 경우의 비중)</ins>**

현재 데이터리안 강의는 크게 두 종류로 나눠집니다. 하나는 SQL을 다루는 '*[백문이 불여일타] 시리즈* ', 다른 하나는 '*추천 시스템* ' 입니다. <br>
두 시리즈는 서로 다루는 내용이 다르다 보니 `두 가지를 모두 수강해주시는 분`들은 얼마나 되며, 어떤 분들이 `어떤 순서로 수강하는지` 궁금합니다. 앞으로 나올 다양한 주제의 강의를 많은 분이 좋아하실지, 기존의 데이터리안 강의를 수강하신 분도 데이터리안을 믿고 새로운 강의를 수강하실지 파악해볼 수 있을 것 같습니다.

<br>
<br>

---

<br>

인프런의 지식 공유자로서 데이터리안은 이런 지표가 궁금한데, 다른 지식 공유자분들은 어떤 지표에 관심이 있으실지 궁금하네요. 지식 공유자로서 일방적으로 컨텐츠를 전달하는 것이 아닌, 강의 개선을 위해 어떤 액션을 해볼 수 있을지 고민해보는 뜻깊은 시간이었습니다. 

<p>

지난 일 년 동안 데이터리안 강의를 수강해주신 모든 분께 다시 한번 감사 인사를 드리며, 앞으로 더 다양하고 발전된 강의로 오랫동안 찾아뵙겠습니다 :)   <img src="./img/datarian_p.png" alt="datarian" width="20"/> 

<p>

[<span style = "color:#537ec5"> 👉데이터리안 강의가 궁금하시다면? Click </span>](https://www.inflearn.com/users/@datarian)


<br><br>

[<span style = "color:#537ec5"> 🔼처음으로🔼 </span>](#top-section)