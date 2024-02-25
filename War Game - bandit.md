# War Game - bandit

1. 복붙은 ctrl C 하고 화면을 우클릭하자
2. 띄어쓰기는 ‘’로 묶거나 \하고 띄어쓰는것도 가능
    
    Ex) spaces\ in\ this\ filename
    
3. file ./* → 해당 경로의 모든 파일의 정보를 나타낸다.
4. file이름 앞에 -이 붙는 다면 ./를 입력해줘야함
5. File Descriptor : 프로세스에서 특정 파일에 접근할때 사용하는 추상값
    1. 일반적으로 0,1,2를 사용한다.
        - 0 : `Standard input`, 표준 입력
        - 1 : `Standard output`, 표준 출력
        - 2 : `Standard error`, 표준 에러
    2. /dev/null : 쓰레기통이다. → 출력 안되는 영역
6. `Redirection`은 입, 출력의 방향을 지정할 때 사용한다.
    - `A > B` : A의 결과를 B로 보냅니다(저장).
    - `A >> B` : A의 결과를 기존 B의 데이터에 추가합니다.
    - `A < B` : B의 데이터를 A(명령)에 입력합니다.

---

du - 파일 공간 사용량 추정

find - 특정조건을 찾아준다.

-size : 파일의 크기에 따라서 달라짐

→ c = byte

→ b = block

→ w : 2byte word

5,6 번을 사용해서 2 >/dev/null : 에러인 친구들 출력하지 말아라~~

grep : 문서안에 찾는 단어가 있을때 사용

> grep -r 'millionth' ./data.txt
> 

> sort data.txt | uniq -u
> 

→ data.txt 에서 유일한 라인만 표시해라

> strings : 파일에 포함된 문자열을 출력합니다
> 

> 
> 

- 비밀번호
    
    > 2lv : rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi
    > 
    
    > 3lv:  aBZ0W5EmUfAf7kHTQeOwd8bauFJ2lAiG
    > 
    
    > 4lv:  2EW7BBsr6aMMoJ2HjW067dm8EgX26xNe
    > 
    
    > 5lv:  lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR
    > 
    
    > 6lv : P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU
    > 
    
    > 7lv :  z7WtoNQU2XfjmMtWA8u5rN4vzqu4v99S
    > 
    
    > 8lv :  TESKZC0XvTetK0S9xNwm25STk5iWrBvP
    > 
    
    > 9lv :  EN632PlfYiZbn3PhVK3XOGSlNInNE00t
    > 
    
    → grep ⇒ binary file 이라 안먹음
    
    → 
    
    > 10lv :  G7w8LIi6J3kTb8A7j9LgrywtEUlyyp6s
    > 
    
    > 11lv :
    >