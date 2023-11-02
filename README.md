# 201930302 김솔빈
# 2023/11/02
```js
    const {data} = await axios.get('${process.env.API.ENDPOINT}/api/04/user`);

    return(
        props:{
            user:data, 
        },
    );

```

# 2023/10/26
## 메타데이터
- 눈에는 보이지 않지만 사진이 가지고 있는 기타의 유용한 정보들

## _app.js 
- pages내의 모든 페이지에 적용
# 2023/10/12
## 라우팅 시스템
- 클라이언트 라우팅만 구현 가능
- 페이지 라우팅

# 2023/10/05

## 서버사이드렌더링s
- 웹페이지를 제공하는 가장 흔한 방법
- ARM을 이용하는 일반적인 웹 페이지 생성
- 자바스크립트 코드가 적재되면 동적으로 렌더링
# 2023/09/21
# 2023/10/05
## 동적 컴포넌트 로딩 - dynamic
## SSG  = 높은 확장성 , 뛰어난 성능을 보이는 프론트엔드 애플리케이션
- 문제점 : 다음 배포 전까지 내용이 변하지 않음

# 2023/09/21

- porcess.browser 변수

* 서버에서 렌더링할 떄 브라우저 전용 api로 인한 문제를 다른 방법으로 해결할 수도 있씁니다
* process browser 값에 따라서 스크립트와 컴포넌트를 조건별로 실해앟는 것.
* 이 변수는 boolean 값

- 페이지에 대한 요청이 들어오면 서버가 REST API를 호출해서 필요한 사용자 정보를 가져옴

1. getServerSideProps라는 비동기 함수 export

- CSR 사용시 주요 이점
1. 네이티브 앱처럼 느껴지는 웹앱
2. 쉬운 페이지 전환
3. 지연된 로딩과 서능
# 2023/09/14

## 서버사이드렌더링s
- 웹페이지를 제공하는 가장 흔한 방법
- ARM을 이용하는 일반적인 웹 페이지 생성
- 자바스크립트 코드가 적재되면 동적으로 렌더링
## 일어날 수 있는 오류 
- CRA 미설치 
- Next.js 12 이후 babel 지원 X
## Transpile 동작법
- 개발자가 작성한 코드 -> Parse -> Transform -> Generate -> 이전 버전의 코드

# 2023/09/07
## ECMAScript 파이프라인 연산자
- 파이프라인  / 공식적으로 채택되지 않은 연산자 
- 사용하기 위해선 바벨 플러그인 설치
- .babelrc 파일 수정
```
    {
        "presets":["next/babel],
        "plugins": [
            
        ]
    }
```
## CSS용 프리프로세스
- Sass (부트스트랩) 추천
- Less (부트스트랩 초기버전)

## Next.js 프로젝트 생성
```
- npx create-react-app test1 
```
## Next.js의 페이지 라우트 방식
- 주소창에 /about ~ 이런식으로 페이지 라우팅 

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
-  ### 서버사이드 렌더링 !

## 리엑트에서 Next.js로 (Node.js -> Next.js)
- Next.js의 기본 철학은 React와 거의 같음
- "설정보다 관습" 이라는 리엑트의 철학을 계승
  
