---
layout: post
title:  "Github pages 오픈"
date:   2019-11-12 23:31:00 +9
categories: post
---
많은 분들이 Github pages를 사용하고 계시길래, 만들어 보았습니다.<br><br>
[slate](https://github.com/slatedocs/slate){:target="_blank"}와 비슷하긴 한데, 좀더 복잡하고 애매한 문제들이 있는 것 같습니다.  
lanyon 테마를 사용하시면 함정 같은 것들이 있는데, 이게 실시간으로 오류를 보여주지 않아서 더 아리송 합니다.    
  
1. date의 문제 : date 표기에서 날짜와 시간을 넣고 그 뒤 숫자까지 넣어줘야 정상동작합니다. date_to_string에서 형식이 맞아야 하는 것 같네요.
2. categories의 문제 : categories에 넣은 글자가 순서대로 _site의 디렉토리로 생성이 됩니다.
3. index.html의 문제 : site.baseurl 뒤에 / 가 하나 더 붙어있어서 오동작합니다.
4. 그외 자잘한 버전의 문제 : 구글링하시면 찾으실 수 있을 겁니다.
  
제가 생각할 때는 프로그래머가 아닌 이상에야 굳이 이걸 사용할 필요가 있을까 합니다. 
그냥 마크 다운 공부한다는 정도의 의미를 가지고 개선하면서 사용해 보겠습니다.