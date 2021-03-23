# 연습해 볼 기능들

git commit -m "메세지"

    스테이지에 있는 파일 git에 저장

git push origin 브랜치명

    로컬 저장소에서 commit한 것들 원격 저장소로 전달

git pull

    원격 저장소에서 내 로컬 저장소와 다른 것들 다운

git branch 브랜치명

    현재 branch에 있는 사항들 복제하여 새로운 branch 생성

git merge 브랜치명

    현재 branch에 명령어에 쓴 branch에서 바뀐거 가져오기




# 추가 

git clone github주소

    로컬 저장소에 원격 저장소에 있는 파일들을 폴더를 생성해서 복제
    
git add 파일명

    로컬 저장소에서 편집한 파일 스테이지에 올림

git checkout 브랜치명

    입력한 branch로 이동

git checkout -b 브랜치명
    
    git branch 와 git checkout 동시실행

git status
    
    현제 스테이지 상태점검

git rm --cached 파일명
    
    스테이지에서 파일 내리기

git log
    
    git의 변동사항 히스토리 보기

git revert 로그번호(앞6자리)
    
    log에서 확인하고 그때 상태로 되돌리기 현재꺼 저장 (reset도 있는데 별로같음)
    
git fetch
    
    원격저장소 변동사항 다운. 이거하고 git status로 확인해야함



# Sourcetree 
유투브에서 봤는데 터미널 쓰기로함



# default branch
Master가 20년 10월 부터 main으로 바뀜
