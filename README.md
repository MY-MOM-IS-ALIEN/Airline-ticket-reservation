# Airline-ticket-reservation
작성자 안민우

프로젝트 명 : Airline ticket reservation

기획의도 :
1. 항공권예매
2. 예매정보 조회
3. 체크인

벤치마킹 : 스카이스캐너 , 대한항공 예매

주요기능 : 
1. 최저가 비교
2. 마일리지 충전하여 바로 결제
3. 항공권정보 스크랩(항공권 장바구니)

MemberDTO
id,memberEmail,memberPassword,memberName(이름),memberMobile(전화번호),Account(잔고)

AirlineDTO 
id,airlineSchedule(비행일정),airlineToAirfort(도착지),airlineFromAirfort(출발지)

MileageDTO
id,mileageAmount(입금),mileageWithdraw(출금)
