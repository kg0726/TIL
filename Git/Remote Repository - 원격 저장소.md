# Remote Repository - 원격 저장소

### commit 만이 올라감

git remote add origin(이름) remote_repo_url(이름의 실제 주소)

git remote -v: 등록된 원격 저장소 확인

업로드 push

다운로드 pull or clone

git push origin master: commit 목록을 업로드

commit 하지 않으면 업로드 불가능

# Pull & clone

- pull: 변경사항 만큼만 다운 git pull origin master

- clone: 전체를 다운 git clone remote_repo_url (clone으로 받은 프로젝트는 이미 git init이 되어있음)

## gitignore: git과 공유하지 않음

- 이미 한번 commit이 되었다면 동작하지 않음 (git rm --cached 비상시 git 캐시에서 삭제 가능)

- gitignore.io > gitignore 파일을 자동으로 생성



## github의 활용

- 개인 포트폴리오
  
  - TIL(today i learned): 내가 배운 것을 마크다운으로 정리해서 문서화하는 것
    
    - 배운 내용에 더해서 스스로 더 나아가 어떤 학습을 했는지를 마크다운에 기록하는 것(예: 어떤 문제를 해결할 때 어떻게 해결할 것인지? 무슨 문제를 겪었고 어떻게 해결하였는지에 대한 과정을 기록해야 한다. 습관화 필수)
  
  - '문서화'의 중요성
    
    - 개발도구의 공식 레퍼런스를 보고 사용법을 스스로 익힐 수 있어야 함
    
    - 자신이 경험한 사용법을 문서화해서 팀 내에 전파할 수 있어야 함
    
    - 여러 개발자들의 TIL 작성법을 참고할 것
