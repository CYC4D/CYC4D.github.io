---
title: Github에 뱃지 추가하기
date: YYYY-MM-DD HH:MM:SS +09:00
categories: [Blog, ETC]
tags:
  [github,badge]
---
# Github 뱃지 추가
가끔 Github을 구경하다보면 아래와 같은 뱃지들을 볼 수 있다.<br>

{:style="text-align:left;"}
![Static Badge](https://img.shields.io/badge/Docker-007396.svg?style=plastic&logo=docker&logoColor=white)
![Static Badge](https://img.shields.io/badge/3.10-python-green.svg?style=plastic&logo=python&logoColor=white)
![Static Badge](https://img.shields.io/badge/K8S-blue.svg?style=plastic&logo=kubernetes&logoColor=white)
![Static Badge](https://img.shields.io/badge/Twitter-Hi-white.svg?style=social&logo=x&logoColor=black)
![Static Badge](https://img.shields.io/badge/Github-black.svg?style=flat&logo=github&logoColor=white)

이런 뱃지들을 자신의 github README, Blog 또는 사이트에 추가하는 방법을 알아보자
<br><br>

## 뱃지 추가 방법
**1. 뱃지 생성 방법**<br>
기본은 shields.io에서 제공하는 링크를 사용하면 된다.<br>
https://shields.io

```
https://img.shields.io/badge/{제목}-{내용}-{색상}.svg?style={스타일}&logo={로고}&logoColor={로고색상}
```


제공하는 style은 아래와 같다.<br>
```
[flat, flat-square, plastic, for-the-badge, social]
```

<br>

**2. 로고 추가 방법**<br>
위 내용 중 logo에 들어갈 이미지는 아래 링크에서 확인할 수 있다.<br>
https://simpleicons.org/ <br>
링크 내 이미지들의 이름을 복사하여 사용하면 된다.

<br>

**3. 제작한 로고를 페이지에 추가하는 방법**<br>
- HTML에 추가하는 경우<br>
```
<img alt="Static Badge" src="https://img.shields.io/badge/:badgeContent">
```

- Markdown에 추가하는 경우<br>
```
![Static Badge](https://img.shields.io/badge/:badgeContent)
```

<br>

## 뱃지 샘플
>만드는게 귀찮은 사람들을 위해 미리 몇가지 생성하여 링크를 공유한다.


<br>

<img alt="Static Badge" src="https://img.shields.io/badge/3.7.3-python-green.svg?style=plastic&logo=python&logoColor=white"><br>
`https://img.shields.io/badge/3.7.3-python-green.svg?style=plastic&logo=python&logoColor=white`

<br>

<img alt="Static Badge" src="https://img.shields.io/badge/docker-blue.svg?style=plastic&logo=docker&logoColor=white"><br>
`https://img.shields.io/badge/docker-blue.svg?style=plastic&logo=docker&logoColor=white`

<br>

<img alt="Static Badge" src="https://img.shields.io/badge/ChatGPT-74AA9C.svg?style=plastic&logo=openai&logoColor=white"><br>
`https://img.shields.io/badge/docker-blue.svg?style=plastic&logo=docker&logoColor=white`
