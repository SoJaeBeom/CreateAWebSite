## 프로젝트 실행 방법

- npm start

## 사용한 기술과 선택한 이유

1. 영역별 등장 애니메이션

- @keyframes
  - 애니메이션 중간중간의 특정 지점들을 거칠 수 있는 키프레임들을 설정하여 CSS 애니메이션 과정의 중간 절차를 제어할 수 있습니다.
  - 브라우저가 자동으로 애니메이션을 처리하는 것 보다 더 세밀하게 중간 동작들을 제어할 수 있습니다.

2. 숫자 증가 애니메이션

- react의 useState hook을 사용하여 데이터 변경시 리렌더링이 될 수 있도록 하였습니다.
- react의 useEffect hook을 사용하여 컴포넌트가 렌더링되거나 []안의 특정 값이 업데이트 될 때마다 코드를 실행시켜 숫자가 증가하도록 하였습니다.
- setInterval()을 사용하여 일정한 시간 간격으로 코드를 실행하고 clearInterval()을 사용하여 setInterval() 메소드를 취소하도록 하였습니다.
