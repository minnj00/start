# git 명령어

## 파일 관리

- `git init`
    - 현재 폴더에  `.git` 폴더를 생성

- `git add <file., folder name>`
    - `working directory` 에서 `staging area` 로 추가
    - 일반적으로 모든 파일, 폴더를 추가하기 위해 아래의 코드를 사용
    - `git add .`

- `git commit -m 'message'` (변경점을 message 안에 넣음)
    - staging area 에 올라간 파일들의 스냅샷을 찍어 `.git directory` 에 저장

## 설정

- `git status`
    - 현재 상태를 체크하는 명령어
- `git config`
    - `git config --global user.email 'your@email.com'`
    - `git config --global user.email` 통해 값 확인
    - `git config --global user.name 'yourname'`
    - `git config --global user.name` 통해 값 확인