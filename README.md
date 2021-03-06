# server-client-vending-machine
TCP/IP 소켓 프로그래밍 서버 - 클라이언트 자판기 프로그램

## 설명
  - TCP/IP 윈도우 소켓 프로그래밍을 이용한 자판기 관리 프로그램 만들기

## 개발 언어, 환경, 프레임워크
   - Java
   - JavaFX
   - Eclipse
   
## 프로그램 구현 기능
      1. 판매하는 음료의 개수는 기본적으로 5개
         (450원 물 / 500원 커피 / 550원 이온음료 / 700원고급커피 / 750원 탄산음료
      2. 각각 음료의 재고는 기본적으로 3개
      3. 3개 이상 음료가 배출되었을 때는 해당 음료(물품)에 대해 품절 표시를 하고 해당 음료를 더 이상 선택 불가능
      4. 입력 화폐 단위는 10원, 50원, 100원, 500원, 1000원으로 한정한다.
      5. 지폐로 입력 받을 수 있는 금액의 상한선은 3000원
      6. 지폐와 동전을 포함한 총 금액은 5000원까지 가능하다.
      7. 기본적으로 거스름 돈을 보유해야 하며, 기본 값을 5개씩 보유해야 한다.
      8. 거스름 돈 반환 or 음료 판매에 따른 동전 가감이 구현되어야 한다.
      9. 음료를 구매 반드시 남은 돈의 반환이 이루어져야 한다.
      10. 관리자 메뉴를 통해 비밀번호 입력 후 접속이 가능해야 한다.
          비밀번호는 반드시 특수문자 및 숫자가 하나 이상 포함된 8자리 이상으로 설정해야 한다.
      11. 각 음료의 재고 보충이 가능해야 한다.
          일, 월, 매출 산출, 각 음료의 일별/월별 산출이 가능해야 한다.
      12. 관리자 메뉴에서 현재 자판기 내의 화폐현황을 손쉽게 파악해야 하며, 수금이란 메뉴를 선택할 경우, 해당 금액을 수금해야 한다.
      13. Socket을 이용해 서버와의 실시간 통신으로 관리되어야 한다.
          기본 클라이언트는 2대, 서버는 1대로 이루어진다.
