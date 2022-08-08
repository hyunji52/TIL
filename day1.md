## **기본 명령어**

1. mkdir 폴더명
=> make directory
=> 폴더를 만들어

2. cd 폴더명
=> change directotry
=> 폴더를 이동해

3. touch 파일명
=> 파일을 만들어

4. ls
=> list segments
=> 해당 디렉토리 안의 파일들의 리스트를 보여줘
ls -a : 숨김파일까지 전부 보여줘
ls -l : 확장자 등 모든 정보 표시해서 보여줘

5. rm 대상
=> remove
=> 대상을 삭제해줘
주의!! 되도록 GUI 환경에서 삭제 부탁
-r : 재귀적으로 폴더 하단 내역도 삭제
-rf : 강제로 삭제

6. mv
=> move
=> 6-1. 이름을 변경하라
=> mv 대상파일 변경이름
=> 6-2. 파일을 이동하라
=> mv 대상파일 이동위치
* 전체 지칭 (asterisk)

(추가) 알아두면 좋은 명령어/단축키
1. pwd
=> present working directory
=> 절대경로 시 좋음

2. ctrl + l
=>스크롤 내리기

3. clear
=> ctrl + l과 동일,
=> 위로 올라가서 이전 코드 확인하긴 어려움

4. 화살표 위,아래
=> 이전 라인 가져오기

5. 경로
상대경로 : . (현재), .. (상위)
절대경로 : /c/Users/chelsea/test

---

## **git 명령어**

1. git init
git 으로 관리 시작
-> 디렉토리당 한번만
주의! 홈폴더나 바탕화면 x

2. git status (중요)
파일 상태 확인

3. git add 파일명
무대위로 올리기

4. git commit -m "커밋 사유"
변경사항을 기록
즉, 사진 찍기
(vim 빠져 나오는 것 esc + :q )

5. config 설정 
-> 한번만
->git에게 내가 누군지 알려주기 
git config --global user.email "you@example.com"
git config --global user.name "Your Name"
git config --global --list

6. git log
커밋의 내역 확인
--oneline

7. 커밋들을 비교하기
git diff 해쉬값 해쉬값

8. github와 연결
git remote add origin URL
git remote -v
# remote 삭제
git remote rm origin

9. github에 local commits 올리기
git push origin master