# EventLogger basic sample

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


# EventLogger 사용 설정 방법
[Quick Start](https://infosys.beckhoff.com/english.php?content=../content/1033/tc3_eventlogger/4279107979.html&id=8268152104426051231) 
