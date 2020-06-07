---
layout: post
title:  "블로그 글 작성 가이드"
subtitle: "데이터리안 멤버들을 위한 포스팅 요령"
type: "How to write a post"
blog: true
text: true
author: Hanseul Wang
post-header: true
header-img: img/header.jpg
order: 2
---

## 📚 how to write a post

1. blog에 글을 작성하고 싶을 때, 원하는 폴더에 새로운 폴더를 생성합니다.

2. 폴더를 생성할 때는 `"text-style-guide"`처럼 폴더명을 소문자 영어로 작성합니다. (띄어쓰기는 - 으로 대신해 주세요.)

3. `index.md` 파일을 만들고 예시 스타일을 복붙해서 [front matter](https://jekyllrb.com/docs/front-matter/) 부분을 변경해 주세요.

4. 포스트를 작성할 때에는 마크다운 형식을 사용합니다. 이미지 첨부, 줄바꿈 등 모든 형식은 마크다운을 따라주시면 됩니다.

5. 이미지를 넣을 때는 `내가 만든 폴더명`/img/ 를 만든 후 이미지를 넣습니다. (png로 넣어주세요)

6. 위 배너에 멋진 이미지를 넣고 싶다 하면, post-header: true / header-img: "\[이미지 링크]" 를 해주시면 됩니다.(괜찮은 무료 이미지 사이트 : https://pixabay.com/ko/)

7. 로컬에서 먼저 build 하여 확인해본 후, PR을 보냅니다.

![예시이미지](img/datarian-logo.png){: width="100%"}
