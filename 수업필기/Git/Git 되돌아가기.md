# Git 되돌아가기

- git revert: 특정 commit을 없었던 일로 만드는 작업
  
  - ``git revert commit id``

- git revert 작동 원리
  
  - 재설정
  
  - 단일 commit을 실행 취소 하는 것
  
  - 재설정 할 커밋을 없었던 일로 처리 후 그 결과를 새로운  commit으로 추가함(과거에 재설정 할 commit이 없었다면 일어날 일)
  
  - git에서 기록이 손실되는 것을 방지하며 기록의 무결성과 협업의 신뢰성을 높임



- git reset: 특정  commit으로 되돌아가는 작업(타임머신)
  
  - ``git reset  옵션 commit id``

- git reset 작동원리
  
  - 특정 commit으로 되돌아 갔을 때, 되돌아간 commit 이후의 commit은 모두 삭제됨

- reset의 3가지 옵션
  
  - ``--soft`` > 삭제된 commit의 기록을 staging area에 남김
  
  - ``--mixed`` > working directory에 남김 (기본 옵션 값)
  
  - ``--hard`` > 기록을 남기지 않음





나머지 읽어만 보기






























