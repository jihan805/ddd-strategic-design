# 키친포스

## 요구 사항
- 식당에서 사용할 수 있는 간단한 포스 시스템 구현.

- 메뉴
    - [ ] 메뉴를 등록할 수 있다.
    - [ ] 메뉴에는 가격이 있어야 한다.
    - [ ] 가격은 음수가 아니어야 한다.
    - [ ] 메뉴그룹은 등록되어 있어야 한다.
    - [ ] 여러개의 메뉴상품을 가질 수 있다.
        - [ ] 메뉴상품의 상품은 등록되어 있어야 한다.               
    - [ ] 메뉴의 가격은 메뉴상품 가격의 총합보다 클 수 없다.
    - [ ] 등록된 모든 메뉴를 조회할 수 있다.

- 메뉴그룹
    - [ ] 메뉴그룹을 등록할 수 있다.
    - [ ] 등록된 모든 메뉴그룹을 조회할 수 있다.
    
- 주문
    - [ ] 주문을 등록할 수 있다.
    - [ ] 여러개의 주문항목을 가질 수 있다.
    - [ ] 주문항목은 비어있으면 안된다.
    - [ ] 주문 테이블은 등록되어 있어야 한다.
    - [ ] 주문 테이블 그룹을 가질 수 있다.
        - [ ] 테이블 그룹은 등록되어 있어야 한다.
        - [ ] 주문 테이블은 가장 먼저 등록된 테이블을 사용한다.
    - [ ] 상태를 가지고 있다.
        - [ ] 주문 등록시 조리중으로 등록된다.
        - [ ] 조리중, 식사중, 식사완료.
    - [ ] 상태를 변경할 수 있다.
        - [ ] 상태를 변경하기 위해서는 주문이 등록되어 있어야 한다.
        - [ ] 상태가 완료인 경우 변경이 불가능하다.
    - [ ] 등록된 모든 주문을 조회할 수 있다.
   
- 상품
    - [ ] 상품을 등록할 수 있다.
    - [ ] 가격이 있어야 한다.
    - [ ] 가격은 음수가 아니어야 한다.
    - [ ] 등록된 모든 상품을 조회할 수 있다.
    
- 테이블
    - [ ] 테이블을 등록할 수 있다.
    - [ ] 테이블은 테이블그룹 아이디, 손님 수, 비어있는지의 상태를 가진다.
    - [ ] 비어있는 테이블로 변경할 수 있다.
        - [ ] 주문테이블이 등록되어 있어야 한다.
        - [ ] 주문테이블에 테이블 그룹이 있어야 한다.
        - [ ] 상태가 조리중이거나 식사중인 경우 변경할 수 없다.
    - [ ] 손님의 수를 변경할 수 있다.
        - [ ] 손님의 수는 음수가 아니어야 한다.
        - [ ] 주문테이블이 등록되어 있어야 한다.
        - [ ] 테이블이 비어있는 경우 변경할 수 없다.
    - [ ] 등록된 모든 테이블을 조회할 수 있다.

- 테이블 그룹
    - [ ] 테이블 그룹을 등록할 수 있다.
        - [ ] 주문 테이블 2개 이상 있어야 한다.
        - [ ] 주문 테이블은 비어있지 않아야 한다.
        - [ ] 주문 테이블은 다른 테이블 그룹에 포함되어 있지 않아야 한다.
        - [ ] 생성시간은 등록 요청 시점으로 한다.
    - [ ] 테이블 그룹을 삭제할 수 있다.
        - [ ] 주문 테이블이 등록되어 있어야 한다.
        - [ ] 상태가 조리중이거나 식사중인 경우 삭제할 수 없다. 

## 용어 사전

| 한글명 | 영문명 | 설명 |
| --- | --- | --- |

## 모델링

- 
