## GIT CONVENTION 가이드

1. 커밋 메시지 구조
커밋 메시지는 다음과 같은 구조를 가진다.

```shell
<타입>: <제목> [Jira 이슈 키]

<본문>

<푸터>
```

2. 타입(Type)
타입은 커밋의 목적을 나타낸다. 사용되는 타입은 아래와 같다. <br/>
feat: 새로운 기능 추가 <br/>
fix: 버그 수정 <br/>
docs: 문서 수정 <br/>
style: 코드 스타일 변경 (formatting, missing semi colons 등) <br/>
refactor: 코드 리팩토링 <br/>
perf: 성능 개선 <br/>
test: 테스트 코드 추가 및 수정 <br/>
build: 빌드 시스템 및 외부 종속성에 대한 수정 <br/>
ci: CI 파이프라인에 대한 수정 <br/>
chore: 빌드나 도구, 라이브러리 관련 변경사항 (개발자의 책임 범위를 벗어나는 작업) <br/>
revert: 이전 커밋을 되돌릴 때 사용 <br/>

3. 제목(Subject)
커밋의 간결한 설명으로, 50자를 넘지 않도록 한다. 첫 글자는 대문자로 작성하고 마침표를 찍지 않는다. 과거 시제가 아닌 현재 시제로 작성한다.


4. 본문(Body)
커밋의 상세한 설명으로, 변경 사항의 이유와 추가적인 정보를 기재한다. 72자를 넘지 않는 라인 길이로 작성하며, 선택 사항으로 둔다.

5. 푸터(Footer)
이슈와 관련된 정보를 기재하며, 선택 사항으로 둔다. 예를 들어, 관련된 이슈 번호를 작성할 수 있다.

<br/>

##### 커밋 메시지 예시
```shell
feat(user): Add user authentication [PROJ-123]

- Implement JWT token for user authentication
- Add login and register endpoints
- Update user model

Resolves: #32
```

<br/>
<br/>
<br/>


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





