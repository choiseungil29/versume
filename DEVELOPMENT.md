# self convention

- Page와 Component를 구분한다
  > Page는 actions와 components의 조합을 갖고있는 Controller로써 기능하고, component는 React App에서 가장 작은 독립적인 단위로 구분함으로써 재사용성을 이룩한다.
- Component는 React renderer 외의 의존성을 갖지 않도록 한다.
  > 다른 component를 사용해야 하는(의존할 수 있는) 경우가 생길 수 있는데, 이는 Redner props를 사용함으로써 서로가 서로를 모를 수 있도록 할 수 있다.
- WIP
