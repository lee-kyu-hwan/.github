# .github

lee-kyu-hwan 계정의 기본 community health 파일 저장소다. 계정이 소유한 모든 저장소(private 포함)에 아래 템플릿이 기본으로 적용된다.

| 파일 | 용도 |
| --- | --- |
| `.github/pull_request_template.md` | PR 본문 템플릿 |
| `.github/ISSUE_TEMPLATE/feat.yml` | 기능 요청 (`enhancement`) |
| `.github/ISSUE_TEMPLATE/bug.yml` | 버그 리포트 (`bug`) |
| `.github/ISSUE_TEMPLATE/docs.yml` | 문서 (`documentation`) |
| `.github/ISSUE_TEMPLATE/chore.yml` | 작업·정리 (라벨 없음) |
| `.github/ISSUE_TEMPLATE/config.yml` | 빈 이슈 허용 |

## 적용 규칙

- 저장소에 자체 `.github/ISSUE_TEMPLATE/`가 있으면 이 저장소의 이슈 템플릿은 **전부** 쓰이지 않는다.
- 저장소에 자체 PR 템플릿이 있으면 그 파일이 우선한다.
- 템플릿이 지정한 라벨은 사용할 저장소에도 있어야 붙는다. 여기서는 GitHub 기본 라벨(`enhancement`, `bug`, `documentation`)만 쓴다.
- 이 저장소는 public이어야 동작한다. 템플릿에 내부 정보를 넣지 않는다.

참고: [Creating a default community health file](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file)
