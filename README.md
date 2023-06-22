# `티셔츠디자인누가함?` - `HTA`

해커그라운드 해커톤에 참여하는 `티셔츠디자인누가함?` 팀의 `HTA`입니다.

## 참고 문서

> 아래 두 링크는 해커톤에서 앱을 개발하면서 참고할 만한 문서들입니다. 이 문서들에서 언급한 서비스 이외에도 더 많은 서비스들이 PaaS, SaaS, 서버리스 형태로 제공되니 참고하세요.

- [순한맛](./REFERENCES_BASIC.md)
- [매운맛](./REFERENCES_ADVANCED.md)

## 제품/서비스 소개

<!-- 아래 링크는 지우지 마세요 -->
[제품/서비스 소개 보기](TOPIC.md)
<!-- 위 링크는 지우지 마세요 -->

## 오픈 소스 라이센스

<!-- 아래 링크는 지우지 마세요 -->
[오픈소스 라이센스 보기](./LICENSE)
<!-- 위 링크는 지우지 마세요 -->

## 설치 방법

> **아래 제공하는 설치 방법을 통해 심사위원단이 여러분의 제품/서비스를 실제 Microsoft 애저 클라우드에 배포하고 설치할 수 있어야 합니다. 만약 아래 설치 방법대로 따라해서 배포 및 설치가 되지 않을 경우 본선에 진출할 수 없습니다.**

> *배포 및 접속방법

> 1. `hackers-ground`의 레포지토리를 나의 레포지토리로 `fork`한다.
> 2. microsoft azure의 `정적 웹/앱`의 `만들기`를 누른다.
> 3. `리소스 그룹`은 `본인의 리소스 그룹`을 선택한다.
> 4. 웹앱 이름은 아무거나 원하는 것으로 정해준다.
> 5. `계획 유형`은 `표준`으로 설정한다.
> 6. `Azure Functions 및 준비 세부 정보`는 `East Asia`로 선택해준다.
> 7. `배포 세부 정보`는 `GitHub`로 설정하고, 본인 계정을 등록해준다.
> 8. `조직`은 `본인의 계정`로 선택해준다.
> 9. `리포지토리`는 `Whodesignedthisfxckingt-shirts-`로 정해준다.
> 10. `분기`는 `main`으로 설정해준다.
> 11. `빌드 세부 정보` 중 `빌드 사전 설정`은 `React`로 설정해준다.
> 12. `앱위치`는 `/hackers_frontend`라고 적어준다.
> 13. `출력위치`는 `build`로 하라고 한다.
> 14. `검토+만들기`를 통해 웹 앱을 생성한다.
> 15. `GitHub Action`을 통해 앱 빌드를 한 후 배포를 시작한다.
> 16. `정적 웹앱` (위의 기술한 사항대로 만든 정적 웹앱)의 기본정보에 있는 URL을 웹 브라우저에 입력한다.


> *사용방법

> `구급차`
>  1. HTA 웹에 접속한다.
>  2. `엠뷸런스`를 누른다.
>  3. 최적(근처)의 병원을 찾기위해 `요청`버튼을 누른다.
>  4. 환자의 증상을 입력한다.
>  5. 오른쪽에 병원리스트를 보고 최적의 병원을 선택한다.(선택하면 병원측에 환자 증상과 요청이 전달된다.)


> `병원` 
>  1. HTA 웹에 접속한다.
>  2. `병원`을 누른다.
>  3. `로그인`을 한다.
>  4-1. 구급차의 요청이 들어올 시 알림이 뜨고 '수락'또는 '거절'버튼을 누른다.
>  4-2. 병상 개수에 변동이 생길경우 각각 버튼을 위 아래로 눌러 `전체병상의 수`와 `남은 병상 수`를 조절할 수 있다. (위로 누르면 +1, 아래로 누르면 -1)


### 사전 준비 사항

> 없음.

## 시작하기

> 위 `배포 및 접속 방법`의 `16.` 참고.(동일)
