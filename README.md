# vaccine_portfolio

![image](https://user-images.githubusercontent.com/102296551/201816587-c1eacfdf-cc51-4079-a282-1a5902b84a64.png)

백신예약 페이지에 <br>
백신을 예약하기 위한 예약번호와 주민번호, 백신코드, 병원코드, 예약날짜, 예약시간 등을 <br>
테이블로 생성하고, 각 정보에 알맞는 input을 작성한다. <br>

# 자동생성

![image](https://user-images.githubusercontent.com/102296551/201816831-1896103e-da53-4cb5-9875-2859d70a829a.png)
자동생성된 예약번호는 SQL에 저장되어있는 예약번호에 +1을 한 값을 출력하여 바로 다음사람이 예약할 수 있도록 생성한다.


# DBConnect

백신예약 프로그램 역시 백그라운드에서 정보를 주고 받아야 하기 때문에 DB를 연동할 JAVA 페이지를 만들어준다. <br>

![image](https://user-images.githubusercontent.com/102296551/201579059-b97efda2-f870-4e63-87c1-5e9055e4c29d.png)

# layout

페이지에 알맞는 layout을 생성하고, 각각 header, nav, footer 등으로 나누어 만들어준다.

# index.jsp

모든 정보를 보여줄 페이지인 index.jsp를 만들고 header, nav, section, footer 를 모두 include 시켜준다. <br>

![image](https://user-images.githubusercontent.com/102296551/201579437-ca972114-7d63-456b-a296-ecd386c2858d.png)

# insert_reservation.jsp

![image](https://user-images.githubusercontent.com/102296551/201810286-43d005f5-3aa3-41dd-b018-1251a026ddcd.png)

DB에 연결하기 위한 쿼리문 작성 <BR>
백신을 예약하기 위한 백신예약 페이지의 백그라운드 페이지를 만든다. <BR>
  DB 테이블에있는 정보를 토대로 파라미터값의 이름을 만든다 예) RNUM, JNUM
