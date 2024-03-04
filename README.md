# 🤾🏻‍♂️ Sandbox with Tech Contents

> 테크 컨텐츠 내용을 적용하고 탐구해보는 나만의 샌드박스

<br/>

## 🧼 Clean Code

### [[토스] SLASH 21 - 실무에서 바로 쓰는 Frontend Clean Code](https://www.youtube.com/watch?v=edWbHp_k_9Y&list=PL1DJtS1Hv1PiGXmgruP1_gM2TSvQiOsFL&index=55&t=690s)

- 실무에서 클린 코드의 의의는 **유지보수 시간의 단축**이다.
- 동료 혹은 과거의 스스로 짠 코드를 빠르게 이해할 수 있다면 유지보수할 때 드는 개발 시간이 짧아진다.
- 이 영상은 실제 예시와 함께 (1) 응집도, (2) 단일 책임, (3) 추상화 총 세 가지 관점으로 클린코드 방법론을 공유한다.
- 구체적인 액션 플랜은 따로 [이 문서](/doc/clean_code.md)에 정리해 두었다.

<br/>

## 🔏 Logging

### [[토스] 프론트엔드 로깅 신경 안 쓰기](https://toss.tech/article/engineering-note-5)

- 로깅 작업을 하기 위해 개발자가 알아야 하는 지식이 하나 없어져 기존의 불편함이 사라졌다.
- 개발자는 오직 로깅하고 싶은 화면이나 버튼에 컴포넌트들을 사용하도록 변경하고, 로깅을 좀 더 선언적으로 처리 가능하다.
- 쏟아지는 요구사항과 로깅으로부터 코드를 보호할 수 있다.
- 비슷한 패턴이 많다면 로깅을 숨긴다. (버튼과 토스트와 같은 공통으로 나타나는 패턴)

<br/>

## 🎋 Git

### [[당근] 매일 배포하는 팀이 되는 여정(1) — 브랜치 전략 개선하기](https://medium.com/daangn/%EB%A7%A4%EC%9D%BC-%EB%B0%B0%ED%8F%AC%ED%95%98%EB%8A%94-%ED%8C%80%EC%9D%B4-%EB%90%98%EB%8A%94-%EC%97%AC%EC%A0%95-1-%EB%B8%8C%EB%9E%9C%EC%B9%98-%EC%A0%84%EB%9E%B5-%EA%B0%9C%EC%84%A0%ED%95%98%EA%B8%B0-1a1df85b2cff)

- 당근페이 머니서비스팀의 더 적합한 브랜치 전략을 찾아 나갔던 이야기 (Git Flow → Github Flow로 변경)
- Github Flow 전략에서 main 브랜치는 mainline의 역할과 동시에 Stable함을 의미한다.
- Git Flow는 develop 브랜치가 Mainline이고, Github Flow는 main 브랜치가 Mainline이다.
- 언제 배포해도 상관없는 Stable 브랜치가 release 형태로 분리되어 있는 Git Flow와 다르게, Github Flow는 배포 브랜치와 작업을 시작하는 Mainline이 동일한 main 브랜치를 사용하고 있다.
- Github Flow는 Git flow에 비해서 Release를 위한 절차가 굉장히 줄어들기 때문에 잦은 기능 수정과 배포가 있는 애자일 조직에 적합한 전략이라고 볼 수 있다. 또한 여러 버전을 동시에 관리할 필요가 없는 Middle급 조직에 어울리는 전략이기도 하다.
