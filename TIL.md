# Tody I Learned

## 깃허브 첫 날 (210125)



- ## Git

  - ## Home 폴더에서 시작

    

  - ## 터미널 명령어

    start . / open .

    1. date = 시간 알려준다
    2. ~ : 루트, 홈 디렉토리
    3. ls (list segments) : 현재 디렉토리 내의
       폴더 & 파일을 보여줌
       -> ls -a : all 숨김 폴더 & 파일까지
    4. ctrl + l => 스크롤 내리기
    5. clear
    6. 배쉬창 화살표 키 => 최근 기입확인
    7. ctrl a, e => 앞뒤 이동

    ------------------------------------

    경로 -> 
    상대경로 = 내 위치 기준
    절대경로 = 어디든 상관없는 위치

    8. touch a.txt => '파일' 을 만드는 경우
    9. mkdir (make directory) => '폴더' 만들기
    10. cd (change directory) =>

    . vs ..  ->  
    . => 현재 위치!
    .. => 현재 위치에서 상대 경로로 상위

    11. mv => 이동 + 이름바꾸기
    12. rm => remove
        파일삭제 : rm a.txt
        폴더삭제 : rm -r test

    * => asterisk , wildcard 
      => all
      rm *.txt

    rm -r , rm -rf
    rm -rf

    

    ---

    

    touch

    파일을 생성하는 명령어

    ```bash
    $ touch text.txt
    ```

    1. mkdir

       make directory

       새 폴더를 생성하는 명령어

       폴더 이름에 띄어쓰기가 있다면 따옴표 사용

       ```bash
       $ mkdir folder
       $ mkdir 'happy hacking'
       ```

- ## Typora

  1. -> 문서의 논리적 흐름
     대제목, 소제목
     주의: 글씨 크기를 키우기 
     위해 사용 x

  2. 인용문 : > 꺽쇠
  3. 리스트 : * or -
     tab 으로 안으로 간다
     shift tab 으로 밖으로 나온다

  4. 이미지 : ![]()
  5. 링크 : []()
     [보여질 제목](실제링크)

  6. 수평선 : ---
  7. 표 만들기
     파이프 스페이스 파이프
     스페이스 파이프 엔터

  

  

  ### vscode 깃 명령어

  깃 명령어 정리

1. git init
   => 현재 폴더를 깃이 
   관리하는 폴더로 만들어줘!
   홈폴더에서 기입하지 X
   딱 최초 1번만 기입!

2. git status
   => 현 상황을 보고싶어!

3. git add a.txt
   git add . (전부다 올리기)

4. git commit -m "메시지"
   => 찰칵! 후 저장소

5. git log 
   => 버전들 확인할래!
   git log --oneline
   을 기입하면 해쉬값을
   알려준다! 그걸 
   체크아웃에 쓰기로 하자!

6. 돌아가보기 :
   git checkout 해쉬값
   git checkout head~3
   다시 나오기 :
   git checkout master


7. 브릿지 잇기 !
   git remote add origin 주소

이어진거 확인
git remote -v

8. 올리기!
   git push origin master

