# 도서 관리 API 제작

**[기능 구현 및 역할]**

- **Stacks: JAVA, JPA, Spring Framework, MySQL  등**

**[기능 구현한 부분]**

- 사용자 등록 및 삭제
    1. 하나의 도서관에서 사용자명 + 휴대전화번호는 유일해야 하지만 같은 사용자가 다른 도서관에 등록할 수도 있습니다.
    - 예시)
        - A 도서관: 사용자명: 홍길동, 휴대전화: 01012341234
        - B 도서관: 사용자명: 홍길동, 휴대전화: 01012341234
    
     2.  사용자가 대출중인 책이 있을 경우 삭제 할 수 없습니다.
    
- 도서 대출
    - 사용자의 대출 히스토리가 있고 대출 기한이 있습니다.
    - 대출 중인 책이 5권 이상 이거나 연체중인 책이 있는 경우 대출이 불가능합니다.
    - 해당 책이 대출중인 경우 대출이 불가능 합니다.
- 도서 검색
    - 책 제목, 저자, 출판사로 검색이 가능 합니다.
