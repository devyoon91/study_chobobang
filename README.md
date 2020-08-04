**📚초보방 오프라인 스터디**
--

**⭐️주제**
- 웹 개발자 스터디(FRONT, BACK)

**🏫스터디 장소**
- 서울 ( 건대입구역 ) { 카페, 스터디룸 }

**👉진행중 스터디**
- `[2020.08] 나도 리엑트 따라해보자`
  - `0.스터디 설명 및 스터디 진행준비[2020.08.08]` 

**📢슬랙(Slack) 초대받기**
- **Slack - Chobobang**
  - **[chobobang.slack.com](https://chobobang.slack.com/)**
  - Slack 초대는 `kimbyungyoun91@gmail.com` 메일로 문의 주세요 
  - Slack 닉네임은 `실명` 또는 `한글 닉네임` 으로 변경 부탁드립니다 

**🐱Git 설치 Github 연동** 
1. GitHub 아이디 만들기, Repository 생성   
   - 블로그 참조, [깃허브(GitHub) 회원 가입하기(계정 만들기)](https://goddaehee.tistory.com/218) 
   - Repository 생성, [GitHub Repository(원격저장소) 생성](https://goddaehee.tistory.com/221)         
2. Git 설치   
   - Git 다운로드 사이트, [https://git-scm.com/download/](https://git-scm.com/download/)   
   - 기본 설치만 하도록 계속 `Next` 진행   
3. GitHub 연동 및 `README.md` 생성
   - 설치된 `Git Bash` 프로그램 실행    
      - git config 변경 ( `이름`, `이메일` 기본 설정 )   
        - ```
           $git config --global user.name "이름"   
           $git config --global user.email "이메일"   
          ```
      - git config 확인 
        - ```$git config --list``` 
   - git 초기화 `git init`
      - 로컬저장소를 생성할 디렉토리로 이동(C 드라이브에 init 할경우), `한글 디렉토리 X`
        - `$cd C:/git/repository/`
      - 초기(.git 폴더생성)
        - `$git init`
   - 로컬저장소 생성 -> 원격저장소 연결 `git remote`
      - git remote add origin https://github.com/devyoon91/study_chobobang.git
   - `README.md` 생성 및 `commit` 
      - `$echo "Hello Chobobang ~"  >> README.md`
      - ```
        $ git status
        On branch master
        Changes not staged for commit:
          (use "git add <file>..." to update what will be committed)
          (use "git restore <file>..." to discard changes in working directory)
                modified:   README.md
        ```
      - `$git add README.md` 또는 `$git add .`
      - ```
        $ git status
        On branch master
        Changes to be committed:
          (use "git restore --staged <file>..." to unstage)
                modified:   README.md
        ```
      - `$git commit -m "Commit README.md ~!!"`
      - `$git status` 로 변경파일이 없는지 마지막으로 확인
   - 로컬저장소 -> 원격저장소 업데이트 
      - `$git push -u origin master`
      - 처음 `push` 할 경우 GitHub 로그인 창 팝업이 나옵니다, 로그인 해줍시다 ~
4. `Git` 배우기
    - [누구나 쉽게 이해할 수 있는 Git 입문](https://backlog.com/git-tutorial/kr/) 
***

**🐱Visual Studio Code 설치/기본설정**
--

**✔️설치파일 다운로드**
  - [Visual Studio Code 다운로드](https://code.visualstudio.com/)

**✔️다음 눌러 설치진행**
  - 기타 3개만 추가 체크   
   
    ![](https://i.ibb.co/r70vNLm/2020-08-02-163401.png)
  
  - 설치 완료    
    
    ![](https://i.ibb.co/zszcZhm/image.png)
  
**한글 설정**
  - 익스텐션 아이콘 클릭 -> `korean` 검색   
  
    ![](https://i.ibb.co/2S9wK70/image.png)
  
  - `Korean language pack for visual studio code` install 클릭! -> 오른쪽 하단 `Restart Now` 클릭   
  
    ![](https://i.ibb.co/DpJFgS6/image.png)
    
  - 한글어팩 설치 완료

    ![](https://i.ibb.co/SNC9vKM/image.png)
 
**⚠️참고 사이트**
  - [개발도구-VSCode-설치와-한글-설정-방법](https://yjshin.tistory.com/entry/%EA%B0%9C%EB%B0%9C%EB%8F%84%EA%B5%AC-VSCode-%EC%84%A4%EC%B9%98%EC%99%80-%ED%95%9C%EA%B8%80-%EC%84%A4%EC%A0%95-%EB%B0%A9%EB%B2%95)

**🍯추천 플러그인 세팅**
  - Visual Studio Code 는 다른 에디터와 마찬가지로 플러그인을 제공합니다 설치는 아래 관련 블로그를 참조합니다
    - [vscode 추천 익스텐션(Extensions)과 세팅](https://caesiumy.github.io/2019/04/02/vscode-recommended-extensions/) 
***

**Nodejs 설치/기본설정**
--

**✔️설치파일 다운로드**
  - 최신버전보다 구버전으로 다운로드(LTS)
    - [https://nodejs.org/ko](https://nodejs.org/ko/) 
    - ✔️기본적인 경로 설정 후 Next 눌러 설치진행

**✔️CMD 를 열어 nodejs 버전 확인**
  - 윈도우키 + r -> cmd 입력 후 엔터
  
    ![](https://i.ibb.co/DCKNPJF/image.png)
  
  - `node -v` 명령어 입력
  
    ![](https://i.ibb.co/82WHXDm/image.png)

**🐤Nodejs로 간단하게 html 띄우기**
  - [node js 설치 (on Windows)](https://dejavuqa.tistory.com/378)

***
