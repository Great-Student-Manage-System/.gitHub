# Great : 그레잇, 학생 성적 관리 시스템

프로젝트 그레잇은 소규모 학원, 혹은 과외 선생님들이 열정을 부어 지도하는 학생들의 성적관리를 한층 더 편하게 만들어주기 위해 시작되었습니다. 

학생의 성적 변화추이, 자신이 지도하는 학생들의 평균치 등의 통계기능을 제공합니다. 나아가 선생님들간의 커뮤니티로의 확장도 준비하고 있습니다.

# 프로젝트 배포 링크


# 회고록
작성자 | 링크
----- | ----
[robinjoon 임수빈](https://github.com/robinjoon) | [팀 프로젝트, Great 1차 배포 회고](https://url.kr/n35z9j)

# 백엔드

## 기술스택

`Spring Boot 2.7.3`

## 사용한 프레임워크 및 라이브러리

```css
dependencies {
	implementation 'org.springframework.boot:spring-boot-starter-hateoas'
	implementation 'org.springframework.boot:spring-boot-starter-jdbc'
	implementation 'org.springframework.boot:spring-boot-starter-web'
	implementation 'org.springframework.boot:spring-boot-starter-mail'
	implementation 'io.jsonwebtoken:jjwt:0.9.1'
	implementation group: 'javax.xml.bind', name: 'jaxb-api', version: '2.3.1'
	compileOnly 'org.projectlombok:lombok'
	runtimeOnly 'org.mariadb.jdbc:mariadb-java-client'
	annotationProcessor 'org.projectlombok:lombok'
	testImplementation 'org.springframework.boot:spring-boot-starter-test'
}
```

# 프론트엔드

## 기술 스택

`React.js`

## 사용한 프레임워크 및 라이브러리

```json
"dependencies": {
    "@craco/craco": "^6.4.5", // 절대경로 설정을 위한 라이브러리
    "@testing-library/jest-dom": "^5.16.5",
    "@testing-library/react": "^13.4.0",
    "@testing-library/user-event": "^13.5.0",
    "@types/react-router-dom": "^5.3.3", // SPA 구현을 위한 라이브러리
    "@vscode/codicons": "^0.0.32",
    "axios": "^1.0.0", 
    "dayjs": "^1.11.5", // 날짜 설정을 위한 라이브러리
    "react": "^18.2.0",
    "react-dom": "^18.2.0",
    "react-google-login": "^5.2.2", // 소셜 로그인을 위한 라이브러리
    "react-hook-form": "^7.36.0",
    "react-icons": "^4.4.0",
    "react-router-dom": "^6.4.0", // SPA 구현을 위한 라이브러리
    "react-scripts": "5.0.1",
    "recharts": "^2.1.15", // 차트 구현을 위한 라이브러리
    "web-vitals": "^2.1.4"
  },
"devDependencies": {
    "@svgr/webpack": "^6.4.0", // svg 설정을 위한 라이브러리
    "@types/jest": "^29.0.2",
    "@types/node": "^18.8.5",
    "@types/react": "^18.0.20",
    "@types/react-dom": "^18.0.6",
    "@types/styled-components": "^5.1.26",
    "craco-alias": "^3.0.1",
    "eslint": "^8.23.1", // 코드 컨벤션
    "eslint-config-prettier": "^8.5.0", // 코드 컨벤션
    "eslint-plugin-prettier": "^4.2.1", // 코드 컨벤션
    "msw": "^0.47.4",
    "recoil": "^0.7.5", // 전역 상태관리
    "styled-components": "^5.3.5", // 디자인
    "swr": "^1.3.0", // 서버 상태 관리
    "ts-node": "^10.9.1",
    "tsconfig-paths": "^4.1.0",
    "typescript": "^4.8.3",
    "webpack": "^5.74.0",
    "webpack-cli": "^4.10.0"
  }
```
