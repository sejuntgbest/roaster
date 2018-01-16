github 사용법
============


## github clone #
깃헙에 있는 소스를 복사한다.

* 복사할 경로

    <code>
    gimhaegyeong-ui-MacBook-Pro:~ schema9$ pwd
    /Users/schema9
    </code>

* git의 경로

  <code>
  gimhaegyeong-ui-MacBook-Pro:~ schema9$ which git
    /usr/bin/git
  </code>

* 복사할 github의 경로를 입력하고 명령어를 실행하면 소스를 복사해온다.

  <code>
  gimhaegyeong-ui-MacBook-Pro:~ schema9$ git clone https://github.com/kimhaegyeong/roaster-1
  </code>





## atom 에서 github 연동하기 #
* clone한 프로젝트를 atom 에서 열기

  ![Alt text](./img/01.atom_add_project.png)



* git panel 을 이용한 커밋 방법
  * 패널 열기
    - atom 하단 [file]을 클릭한다.

  * Staging 상태로 변경하기
    - [Stage All]버튼을 클릭 : 모든 파일을 Staging 상태로 이동
    - 파일 더블클릭 : 해당 파일만 Staging 상태로 변경

      ![Alt text](./img/03.git_panel_01.png)

    - 커밋 메세지를 작성하고 [Commit] 버튼을 클릭한다.

      ![Alt text](./img/02.use_git_panel.png)

  * github로 push 하기
    - 깃헙 파일서버에 올린다.

    ![Alt text](./img/04.push_to_git.png)
