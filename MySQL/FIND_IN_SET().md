## FIND_IN_SET

<br/>

### FIND_IN_SET(str, strlist)

콤마(,)로 구분된 문자열(strlist)에서 매칭되는 문자열(str) 있는지 검사.

있다면 포지션값을, 없다면 0을 반환

    ex: SELECT FIND_IN_SET('b', 'a,b,c,d') --> 2

<br/>

### FIND_IN_SET(int, column)

비트 연산 가능

<br/>

### FIND_IN_SET(str, column)

<br/>

### FIND_IN_SET(column, strlist)


---

| 함수의 매개변수로 column을 전달하면 INDEX 활용할 수 없다.
