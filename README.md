## 홈페이지

### 배포 방법

1. [Gitlab Website](http://lab.t3q.co.kr:9999/fe/website) 레포지토리에서 `yarn export` 명령어를 사용하여 정적 빌드
2. 빌드 후 생성된 `/out` 폴더의 파일들을 Github `main` 브랜치에 복사 및 붙여넣기
   - <span style="color:blue;">`main` 브랜치의 `README.md` 파일이 삭제되지 않도록 주의해주세요</span>
3. [Netlify](https://app.netlify.com/teams/t3qfeteam/builds)에서 빌드 상태 확인 후 [new-t3q](https://new-t3q.netlify.app/ko) 확인
