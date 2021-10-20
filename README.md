## 210914
### Findings
- JSX는 DOM을 다루기 때문에 정확한 오류를 잡아내기 어렵다.
- @testing-library는 이런 문제를 해결하기 위한 DOM 테스팅 라이브러리 이다.
- 리액트를 지원하는 @testing-library는 react-testing-library 이다.
- 공식문서의 첫줄에 다음과 같이 적혀있다.
- The @testing-library family of packages helps you test UI components in a user-centric way.
- @testing-library 패키지는 UI 컴포넌트를 사용자 중심에서 테스트하는데에 도움을 준다. 
- [testing blibrary docs](https://testing-library.com/docs/)
- [react-testing-library github](https://github.com/testing-library/react-testing-library)

---

## 210910
### Facts
- JEST 맛보기
- 코드 직접 작성
### Findings
- null은 undefined가 아니다.
### Feelgins
- jest를 처음 사용해봐서 재밌었다.
- code coverage를 확인할 때 java의 jacoco도 해보고 싶다는 생각을 했다.

## 211004
### Finding
- react-testing-libraray의 render 함수가 반환하는 값 중 container는 화면에 표시되는 부분을 담고 있는 오브젝트이다.

## 211015
### Finding
- 자바스크립트는 동적 프로그래밍 언어이기 때문에 런타임중 발생하는 오류를 확인하기 어렵다.
- 리액트에서는 Flow 라는 정적 타입 분석기를 사용할 수 있다.
- 타입스크립트는 Flow 보다 범용적으로 사용할 수 있다.


## 211020
### Finding
```
npm intstall --save-dev typescript @types/node @types/react @types/react-dom @types/jest
```
- typescript : 타입스크립트 라이브러리
- @types/node : 노드의 타입이 정의된 타입 정의 파일
- @types/react : 리액트의 타입이 정의된 타입 정의 파일
- @types/react-dom : react-dom의 타입이 정의된 타입 정의 파일
- @types/jest : Jest의 타입이 정의된 타입 정의 파일

