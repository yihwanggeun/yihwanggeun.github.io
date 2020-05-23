---
layout: post
title:  "Telegram Bot"
date:   2020-05-17
현재 진행사항: 40%
내가 맡은 부분: "github관리, 코드 추가"
---
<!--
<title> Telegram Bot </title>
-->

<h1> Python-Telegram-Bot 라이센스</h1>
<p>
&nbsp;You may copy, distribute and modify the software provided that modifications are described and licensed for free under LGPL-3. Derivatives works (including modifications or anything statically linked to the library) can only be redistributed under LGPL-3, but applications that use the library don't have to be.<div></div>
Link: <a href="https://github.com/python-telegram-bot/python-telegram-bot#license">https://github.com/python-telegram-bot/python-telegram-bot#license</a> 
</p>


<h1>소개</h1>
<p> 
&nbsp;&nbsp;&nbsp;&nbsp;메신저 봇이란, 좁은 의미에서는 단순히 인간 사용자의 메시지에 대한 자동 응답기능을 가진 프로그램을 의미한다.
그러나 넓은 의미에서는, 해당 메신저의 기능을 기반으로 수많은 문제를 해결하고 사용자의 요청에 응답할 수 있는 프로그램을 의미한다.
본 과제에서 선정한 오픈소스 프로젝트는 텔레그램에서 파이썬을 이용하여 구현한 텔레그램 봇이다. 아래는 원본 사이트에 소개되어 있는 소개글이다.
</p>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;This library provides a pure Python interface for the Telegram Bot API. It's compatible with Python versions 3.5+ and PyPy.
In addition to the pure API implementation, this library features a number of high-level classes to make the development of bots easy and straightforward. These classes are contained in the telegram.ext submodule.
</p>

<h1>선정이유</h1>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;메신저 봇의 경우 이미 만들어진 프로그램을 적극 활용하여 다양한 작업을 간편하게 수행할 수 있다는 점이 매력적이라 느껴 선정하게 되었다.
또한, 비공식적인 봇들을 단속하는 경향이 있는 타 메신저 서비스들과는 다르게 텔레그램의 경우 2015년에 공식적으로 봇API를 발표했다. 따라서, 텔레그램을 이용한 봇 구현 및 오픈소스 프로젝트 참여에 있어 해당 기업의 지침사항 위배와 오픈소스 라이선스 위배와 관련된 문제가 따르지 않는것도 프로젝트 선정에 있어 큰 이유중 하나가 되었다.<div></div>
&nbsp;&nbsp;&nbsp;&nbsp;이와 함께, 언어를 배우는것에 시간을 투자하기 보다 실제 OSS프로젝트에 참여하고 기여하는 것이 본 수업의 취지와 적합하다고 판단하여 조원 모두가 익숙한 언어은 파이썬을 사용하는 프로젝트를 선정하게 되었다.
</p>

<h1>최근 이슈</h1>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;커스텀 필터의 접근권한에 관한 이슈, 일부 특수문자 및 기호가 표기되지 않는 버그에 관한 이슈, 지역에 따른 시간정보 충돌에 관한 이슈, 그리고 동영상 출력 문제에 관한 이슈 등이 있다.
</p>
