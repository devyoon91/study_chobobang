**📚초보방 오프라인 스터디**
--

**⭐️주제**
- 웹 개발자 스터디(FRONT, BACK)

**🏫스터디 장소**
- 서울 ( - ) { 카페, 스터디룸 }

**👉진행중 스터디**
- `[2020.08] 나도 리엑트 따라해보자`

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
4. `Git` 배우기
    - [누구나 쉽게 이해할 수 있는 Git 입문](https://backlog.com/git-tutorial/kr/) 
