## Today I Learned..

### 셸(Shell)이란?
- 운영체제의 커널과 사용자 사이를 연결해주는 프로그램
- 주요 셸: sh, csh, bash, zsh
- 학습한 명령어: cd, mkdir, touch, rm, cat 등

### Vim이란?
- CLI 기반의 텍스트 에디터
- 모드: 일반(normal), 입력(insert), 선택(visual), 명령(command-line)
- 주요 단축키: i, v, ESC, dd, yy, p, :wq 등

### 마크다운 기초
- 텍스트 포맷을 위한 가벼운 마크업 언어
- 문법: 제목(#), 리스트(-, 1.), 링크, 이미지, 강조(_, **), 코드블럭 등

### Git이란?
- 분산형 버전관리 시스템(DVCS)
- 오프라인에서도 작업 가능, 브랜치를 통한 비선형 개발 지원
- 리누스 토르발스가 개발

### 저장소 구성 필수 항목
- 문서화를 위한 README.md 작성
- 불필요한 파일은 `.gitignore`로 추적 제외
- 새로운 컴퓨터에서 첫 push 시 비밀번호 대신 *Personal Access Token* 사용
  → 보안을 위해 만료일 설정 권장
  → 토큰 발급 링크: https://github.com/settings/tokens

### Git 기본 작업 흐름
- git clone: 작업 위치가 dev 등 적절한 디렉토리인지 확인
- git status: 현재 상태 확인 필수
- git add: 꼭 필요한 파일만 스테이징
- git commit: *Conventional Commit* 양식 준수
  - Prefix: feat, fix, docs 등
  - 제목: 간결하고 명령형으로 작성 (문장형 금지)
  - 본문: 제목으로 충분하면 생략 가능
- git push: 커밋 후 원격 저장소로 푸시

### Git 브랜치 개념
- 브랜치는 특정 시점으로부터 독립적인 코드 흐름을 만드는 모델
- 브랜치 생성/전환/병합/삭제: git branch, git switch, git merge, git branch -D
- 충돌 발생 시 수동 해결 필요

## Tomorrow I'll Learn..
- Git 브랜칭 전략
- Git/GitHub/GitLab Flow
- 이슈 및 프로젝트 관리
- Pull Request
- Git 문제 해결 방법 (stash, restore, reset, revert 등)
- GitHub 협업
- 파이널 프로젝트 개요

## What's interesting..
- 단순한 CLI 명령어만으로도 강력한 협업과 버전 관리를 할 수 있다는 점이 매우 인상 깊었다.
