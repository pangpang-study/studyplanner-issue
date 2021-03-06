# studyplanner-Issue
>  설계, 방향 설정, 기능 논의 등 여러 이슈 관리를 위한 공동 레포지토리

## !! 프로젝트 정책 !!
> 모든 레포지토리 공통
0. **무조건 서로 코드 리뷰 하기** 잘했으면 잘한 부분 칭찬하기(보고 배운점이라던가)
1. 새로운 기능을 제안하고 싶다면 issue 레포지에서 제안
    1. 이슈 템플릿을 적극 활용 
    - ex): 새로운 기능 제안에 대해서는 Issue 레포지토리에 Feature template을 사용하면 편함
    2. 누가, 어떻게 구현할 지 세부사항 정해지면 close
2. issue 레포지토리에서 협의된 기능을 토대로 각 파트의 레포지토리에서 다시 이슈를 열어서 기능 구현
3. 이슈 기반으로 브랜치를 관리. **(main에 바로 커밋하는 것 조심)**
    1. 이슈가 발행되면, 브랜치를 생성한다.
    2. 코드를 구현하고 PR을 올린다. 이 때 resolve #issue번호 를 적어서 이슈와 PR을 연동한다.
    3. 코드리뷰를 받는다. PR을 올릴 때 자기 파트 같이 하는 사람을 Reviewer로 꼭 걸기. **Review 승인을 받아야 Merge가 가능하도록 설정했음.**
    4. 리뷰가 종료되면 Merge. 이 때 commit이 2개 이상이라면 Squash and Merge로 머지하여 commit을 한 개로 압축한다.(안 그러면 커밋이 지저분해짐)

## !! 같이 공부하면 좋을 내용이 생긴다면? !!
- studyplanner-issue 레포지에 이슈를 올린다.
- study 템플릿을 참고하여 올리고 댓글로 활발한 소통을 했으면 좋겠음.
