\# Markdown 실습

인공지능학부 241818 신유민



\### Week1-1 강의 개요 (강의계획서)  

\* 교과목명: \*\*오픈소스소프트웨어\*\*`(SAI0003-2)`

\* 담당교수: 최광훈

\* 강의실: \_AI융합대학-301\_

\* 강의시간: 화1목1

---

\### Week1-2 오픈소스소프트웨어 개요

\* Octoverse: 오픈소스소프트스웨어의 현황을 잘 볼 수 있는 통계 자료

&nbsp; \* \[2024 Octoverse](https://github.blog/news-insights/octoverse/octoverse-2024/)

> 오픈소스소프트웨어(OSS):  

> 소프트웨어 저작권 소유자가 모든 사람에게 소스 코드를 게시, 사용, 복사, 수정 및 배포할 권리를 부여한 소프트웨어

> 

> OSS라이선스:  

> 오픈소스 소프트웨어의 사용, 복제, 수정, 배포 권한의 범위를 지정

> \* Linking with Proprietary SW (상용 소프트웨어와의 연동)

> \* Must Publish Modification(수정 시 공개 의무)

> \* Patent Protection (특허 보호 조항)

\* 상용화 관점 OSS 특징

&nbsp; \* 일괄 사전 이용 허락

&nbsp; \* 로열티 없음

&nbsp; \* 소스 코드 제공

&nbsp; \* 복제, 배포, 수정 허용

&nbsp; \* 기간/목적 제한 없음

&nbsp; \* 지적재산권(상용화된 SW와 공통된 특징)

\* 철학적 관점

\* \_free SW\_ vs. \_open source SW\_

---

\### Week2-1 버전 관리 개요

> Version Control System (VCS):  

> Track your files over time so that you can easily get back to a previous working version

\* VCS software

&nbsp; \* CVS (Concurrent Version System)

&nbsp; \* SVN (Subversion)

&nbsp; \* Mercurial

&nbsp; \* Darcs

&nbsp; \* Git

\* Repository or Repo (저장소)

\* Actions

&nbsp; \* Checkin << commit(git)

&nbsp; \* Checkout, editing

&nbsp; \* Diffs

&nbsp; \* Branching

&nbsp; \* Merging

&nbsp; \* Conflicts

&nbsp; \* Tagging

\* Two Main Types

&nbsp; \* Centralized VCS ( \_E.g. CVS, SVN\_ )

&nbsp; \* Decentralized (Distributed) VCS ( \_E.g. GIT, Mercurial, Darcs\_ )

---

\### Week2-2 \*\*Git\*\*

\* Control system  

<img width="1242" height="322" alt="image" src="https://github.com/user-attachments/assets/0dfdcd09-6ae4-46ae-b23e-55abaa362284" />



\* Workflow  

&nbsp; \* `git clone` << \*\*처음으로 내려 받을 때만\*\*  

&nbsp; \* `git add`  

&nbsp; \* `git commit`  

&nbsp; \* `git push`  

&nbsp; \* `git fetch`  

&nbsp; \* `git merge` << conflict  

&nbsp; \* `git pull` << 되도록 `git fetch`, `git merge`하기  

&nbsp; \* `git diff HEAD`, `git diff`  

&nbsp; \*  fork, pull request  

---

\### Week2-3 Github, fork, pull request

> GitHub:  

> 전 세계 개발자들이 코드를 올리고 협업하는 원격 저장소 플랫폼.  

> (Git = 버전 관리 도구 / GitHub = 그걸 공유·협업할 수 있는 웹 서비스)



주요 기능:

\* 저장소(repository) 관리

\* 버전 추적 (commit, branch, merge)

\* 협업 기능 (issue, pull request, review)



> Fork:  

> 다른 사람의 GitHub 저장소를 내 계정으로 복사하는 것.  

> 원본에는 영향을 주지 않고, 독립적인 사본을 만들어 내 마음대로 수정 가능함.

>

> Pull Request:  

> Fork(복사)한 저장소에서 수정한 내용을 원래 저장소에 반영해 달라고 요청하는 것.



흐름:



&nbsp; 1. 원본 저장소 Fork  

&nbsp; 2. 내 Fork에서 수정 및 Commit  

&nbsp; 3. GitHub에서 Pull Request 생성  

&nbsp; 4. 원본 소유자가 코드 리뷰 후 Merge

---

\### Week2-4 Git: Advanced topics

\* Git training  

\[Pdf\_Training](https://github.com/uminshin/git\_training/blob/master/Git\_training.pdf)

\* 나의 실습 결과  

\[Pdf\_uminshin](https://github.com/uminshin/git\_training/blob/master/hw\_git\_%EC%8B%A4%EC%8A%B5\_241818\_%EC%8B%A0%EC%9C%A0%EB%AF%BC.pdf)

---

\### Week3  Markdown

> Markdown: A lightweight markup language for creating formatted text using a plain-text editor

\* Examples

&nbsp; \* Headings

&nbsp;   # Heading one

&nbsp; \* Italic, bold, etc.

&nbsp;   \_italic\_

&nbsp;   \*\*bold\*\*

&nbsp;   `monoplace`

&nbsp; \* Lists

&nbsp;   1. mission

&nbsp;      \* markdown

&nbsp;   2. period

&nbsp;      - 10.14

&nbsp; \* Links and images  

&nbsp;   \[github](www.github.com)  

&nbsp;   github logo image    

&nbsp;   !\[github logo](https://github.githubassets.com/images/modules/logos\_page/GitHub-Mark.png)

&nbsp; \* Blockquotes

&nbsp;   > block quotes

&nbsp; \* Paragraphs  

&nbsp;   paragraphs

