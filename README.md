# 2023/08/31
## Next.js 알아보기
### next.js는 리액트를 위해 만든 오픈소스 자바스크립트 웹 프레임워크
리액트에는 없는 다양한 기능 제공
- 서버사이드 렌더링 (SSR)
- 정적 사이트 생성 (SSG)
- 증분 정적 재생성 (ISR)

## Next.js가 제공하는 새로운 기능들
- 코드분할
- 정적 사이트 생성만 지원
- 클라이언트 사이드 렌더링만 지원
- 동적으로 변하는 복잡한 웹 사이트는 x

#### 코드 분할 
##### 페이지를 로딩 할 때 번들을 여러 조각으로 나누어 필요한 부분만 전송하는 방식
- 서버 사이트 렌더링
- 파일 기반 라우팅
- 경로 기반 프리페칭
- 정적 사이트 생성
- 증분 정적 콘텐츠 생성
- 타임스크립트에 대한 기본 지원
- 자동 플리필 적용
- 이미지 최적화
- 웹 애플리케이션의 국제화 지원
- 성능 분석
## Next.js와 비슷한 프레임워크
[Gatsby]
- 정적 웹 사이트를 만들 수 있는 프레임워크
- 정적 사이트 생성만 지원
- 클라이언트 사이드 렌더링만 지원
- 동적으로 변하는 복잡한 웹 사이트 x

[Razzle]
- 서버 사이드 렌더링이 가능한 자바스크립트 애플리케이션 개발 가능
- CRA와 유사하게 프로젝트를 구성할 수 있다는 장점이 있습니다
- React , Preact , Reason-React , Angular 및 Vue와 함께 사용 가능

[Nuxt.js]
- Vue를 사용한 웹 애플리케이션 개발에서 리엑트의 Next.js에 해당하는 프레임워크

[Angluar Universal]
- 정적 사이트 생성과 서버 사이드 렌더링 지원
- 구굴에서 만듬

  ## 왜 Next.js 일까 ?
  - React 에서 제공하지 않는 여러 기능 지원
  - 설정이나 개발 옵션 등 다양한 부분에서도 유용한 기능들을 지원
  - 활동적인 커뮤니티 있어 개발 단계별로 많은 지원 받을 수 있음
