# graphql-movie

## GrahpQL을 사용하는 이유

- 데이터 베이스에 내가 사용하지 않을 영역의 데이터를요청하는 것은 좋지 않다.
  - (over-fetching)
- 하나의 페이지를 구성하기 위해서 여러번의 REST를 호출해서 데이터를 만들 필요가 없다.
  - (under-fetching)
- 오직 하나의 end-poing를 가지고 query를 작성하여 데이터를 요청하고 받을 수 있다.
