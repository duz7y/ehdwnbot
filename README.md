# 동주봇
[엔트리이야기](<https://playentry.org/community/entrystory/>)에서 봇을 호출할수 있게 해주는 툴입니다.<br>
Streamlit을 사용했으며 실행할땐 터미널에서 streamlit run app.py로 실행할수 있습니다.

심심할때마다 업데이트합니다.
<br>
<br>
# 주의사항
~초마다 서버에 요청을 날리기때문에 엔트리 서버에 무리가 갈수있습니다.<br>
(이 부분은 app.py에서 ctrl+f누르고 time.sleep을 검색해줍니다.<br>
그리고 () 부분에 서버에 요청을 날릴 지연시간을 정해줍니다.<br>

과도하게 사용할 경우 글정을 당할 수 있습니다.<br>
개발하고 실행한 본인은 엔트리 IP밴을 당했으니 조심하세요.<br>

keyerror하고 message이런식으로 뜬 경우<br>
1. 아이디또는 비밀번호를 잘못 입력했거나,
2. 계정이 잠겼거나<br>

둘중 하나입니다.<br>

또한 글이 안써질땐 이메일인증이나 캡차를 해야하는 경우가 있습니다.<br>
가장 좋은 방법은 봇을 실행할 계정에서 한번 글을 써보세요.<br>

24시간 봇서버를 돌리는건 추천하지않습니다.<br>
정말로요!
<br>
<br>
# 제미나이 (ai)
```py
genai.configure(api_key="APIKEY")
```
부분에 발급받은 apikey를 넣으시면 제미나이의 api로 생성형 답변을 내놓을수 있는 기능을 추가했습니다. (2024-9-29)
<br>
<br>
# 스크린샷
실제 유저가 실행하는 장면<br>
<img src="https://github.com/user-attachments/assets/cdd3e6bb-fe91-4d38-bb7f-5bdaac98150d"  width="350px" height="auto"/>
<br><br>
파이어베이스를 이용한 사용자정의 명령어 (본 툴에선 제거함)<br>
<img src="https://github.com/user-attachments/assets/b7930491-e25a-465c-906f-23e6f3056335"  width="350px" height="auto"/>
<br>
<br>
쓸때 최소한의 출처는 남기세요.<br>
EX. 봇 계정에 https://naver.me/FFGwfSNY 의 소스코드를 사용했다고 남기기
