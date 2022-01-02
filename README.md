# VanillaJS로 Todo-list 만들기

## 1. main block
|||
|:--:|:--:|
|<img width="266" alt="image" src="https://user-images.githubusercontent.com/67853616/147870693-7a9b6917-7036-4f4d-ad38-b5f47cf977eb.png">|<img width="254" alt="image" src="https://user-images.githubusercontent.com/67853616/147870654-adae62f4-97e5-4180-b308-e98d0701f879.png">|
* 랜덤 배경 img 
* 실시간 현재 시각
* API 활용한 위치/날씨/공기 오염도

## 2. daily block
|||
|:--:|:--:|
|<img width="230" alt="image" src="https://user-images.githubusercontent.com/67853616/147870717-5805a21d-a9c9-4c91-bd5d-4dc2326f3bc1.png">|<img width="230" alt="image" src="https://user-images.githubusercontent.com/67853616/147870745-0f9fb4e9-e9e8-49db-9c2e-4cea4b575f85.png">|

* 본인 입력시 local storage에 담겨 새로고침 이후에도 계속 유지 가능

## 3. daily quotes
|PC|Mobile|
|:--:|:--:|
|<img width="215" alt="image" src="https://user-images.githubusercontent.com/67853616/147870788-d1ef65d4-f2b4-4184-896d-5a85cc991728.png">|<img width="88" alt="image" src="https://user-images.githubusercontent.com/67853616/147870809-a1407155-8201-4766-ab10-d64f1b40a8dc.png">|
* 랜덤 격언
* 화면 크기에 따라 넘치지 않도록 (명언+사람) / (명언)으로 구성

## 4. daily water
|Default|Click|
|:--:|:--:|
|<img width="193" alt="image" src="https://user-images.githubusercontent.com/67853616/147870853-393ea65f-584e-46d0-a570-39d95d40b283.png">|<img width="185" alt="image" src="https://user-images.githubusercontent.com/67853616/147870874-6935ec0f-fdd5-4c2c-a5db-060ef7c55bd2.png">|
* 하루 목표 물 5잔 마시기 기록
* click 이벤트 발생시 일정 percent만큼 progress bar가 채워 지도록!!

## 5. daily calender
<img width="253" alt="image" src="https://user-images.githubusercontent.com/67853616/147870940-072fbd47-3017-4d6c-bc0f-bb2878f76d75.png">

[바닐라 JS로 달력 만들기 기록](https://velog.io/@hixkix59/JS-%EB%8B%AC%EB%A0%A5-%EB%A7%8C%EB%93%A4%EA%B8%B0)

* css를 이용한 월/일/요일 칸 구획 <br>
* 현재 달에 맞는 이전 달 날짜/이번 달 날짜/다음 달 날짜 불러온 후 색상 구분

## 6. daily to-do-list
|default|check|add|
|:--:|:--:|:--:|
|<img width="251" alt="image" src="https://user-images.githubusercontent.com/67853616/147871081-f868d757-3737-4371-bc6b-a1df8191e03a.png">|<img width="235" alt="image" src="https://user-images.githubusercontent.com/67853616/147871094-d8664c41-34a5-48f7-891a-552cef3bcd76.png">|<img width="254" alt="image" src="https://user-images.githubusercontent.com/67853616/147871088-2b0ed542-a687-4050-8c06-1b0155c26d2d.png">|
* 새로 고침 후에도 사라지지 않도록 생성된 local storage에 todo 담기
* check된 todo에 밑줄 긋고 새로고침 후에도 밑줄 유지되도록!!
* delete (-) 클릭 시 목록에서 사라지고 local storage에서도 사라지도록 구현
