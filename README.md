# onboarding
## 이벤트 시작전 관리자 준비사항
Organization Setting > Member privileges > Base permissions 를 Write를 설정해야 멤버들이 레포지토리에 초대받지 않아도 push, merge를 진행할 수 있음

## 진행순서
아래 단계를 순차적으로 진행하시면 됩니다.
### Issues 등록시 규칙
1. Assignees에 본인 Github ID 걸기
2. Label에 Introduce 사용하기
3. Issue number 기억해두기

### Markdown 생성시 규칙
1. Hello/이름 형태로 브랜치 생성 (예시: Hello/IMKUNYOUNG)
2. Root 경로에 있는 NAME.md 파일의 내용을 복사하여 3 rules와 wish 항목을 수정하여 따로 복사해놓기
2. Add file로 Root에 Markdown 파일을 생성. 파일명은 이름.md (예시: IMKUNYOUNG.md)
3. 커밋 몇은 Init: wish and 3 rules #1 ( #1은 본인의 Issue number )

### Pull Requets 진행시 규칙
1. 본인의 주변 3인에게 Github ID를 물어보고 추가하여 Reviewers로 등록하기 ( 3인 미추가시 Merge불가 )
2. Assignees에 본인 ID 추가
3. Label에 Introduce 사용하기
4. Reviewers로 등록된 PR에 접속해서 칭찬 or 궁금증 or 응원 글을 남기고 approve하기

## 이벤트 효과
reviewer를 찾고 approve 방법을 찾아가며 Github 사용법을 자연스럽게 익히고, 문제 해결 과정을 통해 서로가 알아가며 친해질 수 있는 시간을 갖음


## GIT CONVENTION
feat: 새로운 기능 추가
fix: 버그 수정
docs: 문서 수정
style: 코드 스타일 변경 (formatting, missing semi colons 등)
refactor: 코드 리팩토링
perf: 성능 개선
test: 테스트 코드 추가 및 수정
build: 빌드 시스템 및 외부 종속성에 대한 수정
ci: CI 파이프라인에 대한 수정
chore: 빌드나 도구, 라이브러리 관련 변경사항 (개발자의 책임 범위를 벗어나는 작업)
revert: 이전 커밋을 되돌릴 때 사용
