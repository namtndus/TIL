# Primitive Type vs Reference Type
- Primitive Type(원시 타입) : 하나의 데이터만 갖고 있는 타입
  - Primitive Type Date의 종류
    - Number
    - String
    - boolean
    - Null
    - undefined    
    
- Recerence Type : 주소를 데이터로 갖는 타입    
  - Recerence Type Data의 종류
    - Object
    - Array
    - Function 
# Scope
 - 의미: 변수 접근에 따른 유효 번위
 - 특징: 
  - 안쪽 스코프에서 바깥쪽 스코프로는 접근이 가능하지만, 반대는 불가능함
    - 스코프는 중첩이 가능함
    - 가장 바깥 스코프는 특별히 전역 스코프(Global Scope) 라고 하고, 안쪽 스코프는 지역 스코프(Local Scope)
    - 지역 변수는 전역 변수보다 더 높은 우선 순위를 가짐  
 - shodow(쉐도우)
  - 바깥 변수가 지역 변수에 의해 가려져서 출력이 안 되는 경우  

# Closer
 - 의미: 외부 함수의 변수에 졉근할 수 있는 내부함수
