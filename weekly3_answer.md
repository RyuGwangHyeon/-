### Git에서 branch merge 방법들과 각 방법의 특징을 설명하세요

1. Merge Commit을 생성하여 branch를 병합하기
    기본적으로 병합된 커밋들의 기록이 남아있다는 특징이 있습니다.

2. Fast-forward로 branch 병합하기
    branch가 순차적으로 변경되었을 때만 사용이 가능합니다.
    새로운 commit이 생성되지 않고, 현재 branch가 빠르게 앞으로(Fast-forward) 이동합니다.
    히스토리가 단순하지만 branch간의 작업이 겹치지 않는 경우에만 사용이 가능합니다.

3. Rebase를 이용한 branch 재배치
    기본 branch의 commit들을 새로운 branch위에 재배치합니다.
    히스토리가 한줄로 깔끔하게 정리가 되지만 병합된 branch의 기록들이 없어지기 때문에 신중하게 사용해야 합니다.

### Git Flow branch 전략에 대해서 설명하세요

Git Flow는 효과적인 소프트웨어 개발을 위한 branch전략입니다.

1. 기능 개발
2. 기능 완료
3. 릴리즈 주비
4. 테스트 및 수정
5. 출시
6. 수정

앞의 순서로 진행을 하게 되며, 체계적으로 관리를 할 수 있어서 효과적입니다.