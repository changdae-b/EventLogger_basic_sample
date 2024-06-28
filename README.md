
# EventLogger basic sample
TwinCAT 4024.53 build  


# TwinCAT 3 EventLogger
[TwinCAT 3 EventLogger](https://infosys.beckhoff.com/english.php?content=../content/1033/tc3_eventlogger/index.html&id=8504177607767980219)

TwinCAT 3 EventLogger는 로깅을 남기는 기능이며 Message, Alarm 두가지 방식으로 남길 수 있다.  
TwinCAT 3 XAE 상단의 View - Other Windows - TwinCAT Logged Events에서 로그들을 확인할 수 있다.

### Messages
- 상태가 없고 단순 메시지만 보내는 기능
- [FB_TcMessage](https://infosys.beckhoff.com/english.php?content=../content/1033/tc3_eventlogger/5003041163.html&id=3352751725740089607)로 생성

### Alarm
- 메시지와 다르게 알람에는 상태가 있음
	- Not-Raised
	- Raised
- 추가로, Confirmation이 요구될 수 있음 
	- Wait for confirmation
	- Confirmed or Reset  
		-> Confirmation이 Confirm()으로 되면 상태는 Confirmed가 됨  
		-> Confirmation이 Clear(TRUE)로 되면 상태는 Reset이 됨
- [FB_TcAlarm](https://infosys.beckhoff.com/english.php?content=../content/1033/tc3_eventlogger/5001926923.html&id=)으로 생성


![image](https://github.com/changdae-b/EventLogger_basic_sample/assets/108038154/980571ba-fc0c-4e68-a3a2-f307cbc1c54d)
* EventLogger 예시


# EventLogger 튜토리얼 (Beckhoff Infosys)
[Quick Start](https://infosys.beckhoff.com/english.php?content=../content/1033/tc3_eventlogger/4279107979.html&id=8268152104426051231) 
