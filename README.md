## 개발환경 (1주6일차)
> 1. 환경 설정 + 프로젝트 시작 하는 법 한번에 끝내기 
> 2. 깃허브로 포트폴리오 올리기 
> 3. 내 프로젝트에 도메인 얻는 법


URL 만들기
---
> url : [https://noona-fj.netlify.app/](https://noona-fj.netlify.app/)



맥에서 git 올리는 방법
---

```
git init
.git/ 안의 빈 깃 저장소를 다시 초기화했습니다

git add . // 작업파일 git에 올릴 파일 준비시키기

git commit -m "first commit"
[dev (최상위-커밋) c104462] first commit
 2 files changed, 10 insertions(+)
 create mode 100644 index.html
 create mode 100644 style.css

git branch -M main 

git remote add origin https://github.com/cse96hk/first-noona-project.git

git remote -v 
origin  https://github.com/cse96hk/first-noona-project.git (fetch)
origin  https://github.com/cse96hk/first-noona-project.git (push)

git push -u origin main
오브젝트 나열하는 중: 4, 완료.
오브젝트 개수 세는 중: 100% (4/4), 완료.
Delta compression using up to 10 threads
오브젝트 압축하는 중: 100% (3/3), 완료.
오브젝트 쓰는 중: 100% (4/4), 441 bytes | 441.00 KiB/s, 완료.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/cse96hk/first-noona-project.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.


```
저장소에 내려 받기
---
```
git remote update
remote: Enumerating objects: 7, done.
remote: Counting objects: 100% (7/7), done.
remote: Compressing objects: 100% (5/5), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
오브젝트 묶음 푸는 중: 100% (6/6), 2.64 KiB | 450.00 KiB/s, 완료.
https://github.com/cse96hk/first-noona-project URL에서
   e93f38e..46b802d  main       -> origin/main

git pull
업데이트 중 e93f38e..46b802d
Fast-forward
 README.md | 51 +++++++++++++++++++++++++++++++++++++++++++++++++++
 1 file changed, 51 insertions(+)
 create mode 100644 README.md

git status
현재 브랜치 main
브랜치가 'origin/main'에 맞게 업데이트된 상태입니다.

커밋할 사항 없음, 작업 폴더 깨끗함
```

