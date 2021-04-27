- Area

  - Area 에는 3가지가 있다.
    1. local Area : 실제 파일을 작업하는 공간
    2. stage Area : commit을 하기위해 파일을 선택하는 공간
    3. repository Area : commit이 되어 있는 공간

- Branch

  - 가지치기
  - 선택한 시점에서 시작하는 다른 타임라인을 가지는것.
  - 평행세계

    1. master 에서 새로운 branch 생성
    2. master 의 변경사항을 branch 에 가져올때 Branch - Update from default branch
    3. branch 의 변경사항을 branch 로 가져올때 Branch - Merge into current branch

  - conflict : 충돌
    - branch merge 시 충돌이 일어나면 vscode 에서는 4가지 옵션을 제공한다. ( 타 IDE 에서는 확인 하지 않음.)
      1. Accept Current Change : 현재 상태로 변환
      2. Accept Incoming Change : merge 대상의 상태로 변환
      3. Accept Both Changes : 현재 상태와 merge 대상의 상태를 모두 변환
      4. Compare Changes : 충돌되는 부분을 보여줌.
