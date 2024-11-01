# GIT 과 GITHUB
# GIT

- GIT : **분산** 버전 관리 시스템
- GITHUB : **원격 GIT 저장소**

## Local Git

- 저장소 생성
```bash
git init
```

- git 설정
```bash
git config user.name "HoJeong Moon"
git config user.email firstmoon5@naver.com
#공용 git 설정을 하려면 -g
#예) git config -g user.name 이름
```

- git 상태 확인
```bash
git status
```

-staging
```bash
git add .
```

- 저장소에 반영 (commit)
```bash
git commit -m "First Commit"
```

- 상태 확인과 로그 확인
```bash
git status  #상태확인
git log #로그확인
```