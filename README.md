# github_connect

## 🐶 깃 설치 (https://git-scm.com/download/win)
      git을 통해서 github과 연결할 수 있다.
      깃에 올려야할 폴더에 shift + 우클릭하여 Powershell 창열기
      git init
      .git 폴더가 생성됨
      
-------------------------------------

## 2. 깃 설치 후 git bash 열기
![image](https://user-images.githubusercontent.com/105650300/235417919-be03e509-e51f-4ae5-b783-2b0d1e247b1d.png)



* 유저이름설정

      user@DESKTOP-KS31RFK MINGW64 /d/이정민/htmlCss/flex (master)
      $ git config --global user.name "leejm"

* 유저 이메일 설정하기(반드시 github에 가입했던 이메일 주소와 동일해야한다.
      git config --global user .email "slzlxn@naver.com"
      
* 내 정보 확인하기
      git config --list
      
## ⬆️ 위의 연결은 해당 컴퓨터에서 한번만 실행하면 됨
------------------------------------------

# github에 코드 업로드하기
      * 초기화
            git init
      * 추가 할 파일 (폴더 안에 내용을 모두 올림) (.은 모든 파일을 의미)
            git add .
      * 히스토리 만들기 (-m은 메세지를 의미함 ""안에는 히스토리 이름을 적음)
            git commit -m "first commit"
      * github의 repository를 만들고 그 주소와 연결하기
            git remote add origin https://github.com/slzlxn/css_flex.git
            
      * 연결이 잘 되었는지 확인하기(사용안해도 됨)
            git remote -v
      * github에 올리기
            git push origin master
     \
-----------------------------------------------

## 수정하여 다시 업로드할때 
      * 초기화
            git init
      * 추가 할 파일 (폴더 안에 내용을 모두 올림) (.은 모든 파일을 의미)
            git add .
      * 히스토리 만들기 (-m은 메세지를 의미함 ""안에는 히스토리 이름을 적음)
            git commit -m "first commit"

      1. 기존의 코드를 다운받는 행위를 해야한다.
            git pull origin master
      
      2. 다시 push 해야한다
            git push origin master
      
자식 파일 찾을때 dir 뒤로갈때 cd . 




----------------------------------------------------------------------

# github 협업하는 방법 (사원입장)

1. 소스코드 다운로드

   git clone 주소 
   ![image](https://github.com/slzlxn/github_connect/assets/105650300/4c35302b-598f-4176-a4d3-f5aff4a00bb3)

   비주얼스튜디오에서 폴더 만들고 새 터미널에서 
   git clone https://github.com/slzlxn/hanacard.git

2. 수정후 올리기
      브랜치(branch) 만들기
      git checkout -b 브랜치이름
      git checkout -b lee
      
      git add .
      git commit -m "하나카드"
      
      git push origin lee 브랜치이름
      git push origin lee
      
      
      ![image](https://github.com/slzlxn/github_connect/assets/105650300/ac1a10b2-6118-488f-b3e7-cbf9a9496dab)
 
 나혼자 하면 브랜치 말고 마
 
 ![image](https://github.com/slzlxn/github_connect/assets/105650300/f14a7dd6-f370-4da5-a78b-1a51822b9f53)

