# OSS Git Example

## Week1-1: **강의 개요 (강의계획서)**
*이 강의는 오픈소스 소프트웨어와 Git, GitHub를 사용한 버전 관리에 대해 다룹니다.*

## Week1-2: **오픈소스소프트웨어 개요**
- **오픈소스 소프트웨어**란 소스 코드를 공개하여 누구나 사용, 수정, 배포할 수 있는 소프트웨어를 의미합니다.
- [오픈소스 소프트웨어에 대해 더 알아보기](https://en.wikipedia.org/wiki/Open-source_software)

## Week2-1: **버전 관리 개요**
- 버전 관리 시스템을 사용하여 프로젝트의 이력과 변경 사항을 추적할 수 있습니다.
- **Git**은 대표적인 분산 버전 관리 시스템입니다.

## Week2-2: **Git**
> "Git은 로컬과 원격 저장소에서 코드의 변경 내역을 추적하고 협업을 가능하게 합니다."

### 주요 Git 명령어:
1. `git init` : 새로운 Git 저장소 생성
2. `git add` : 변경된 파일을 스테이징
3. `git commit` : 스테이징된 변경 사항을 기록

## Week2-3: **GitHub, Fork, Pull Request**
- GitHub는 Git 저장소를 호스팅하는 **플랫폼**으로, 협업을 위한 다양한 도구를 제공합니다.
- **Fork**: 다른 사람의 저장소를 복사하여 자신의 계정에서 변경 작업을 할 수 있습니다.
- **Pull Request**: 변경 사항을 원래 저장소에 반영하도록 요청하는 작업입니다.
- ![GitHub Logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

## Week2-4: **Git: Advanced topics**
- **브랜치**를 사용하여 독립적인 개발 환경을 만들 수 있습니다.
  - 예: `git branch feature-branch`
- **Merge**를 사용하여 변경 사항을 메인 브랜치에 통합합니다.
  - 예: `git merge feature-branch`

## Week3: **Markdown**
Markdown은 다양한 텍스트 요소를 쉽게 표현할 수 있는 마크업 언어입니다.

- **Headers**: 제목을 표시하는 데 사용합니다 (`#`).
- **Italic and Bold Faces**: 강조 표시를 위해 사용합니다.
  - *Italic* : `*italic*`
  - **Bold** : `**bold**`
- **Lists**: 순서가 있는 목록과 순서가 없는 목록을 작성합니다.
  - 순서 없는 목록: `- item 1`
  - 순서 있는 목록: `1. item 1`
- **Links and Images**:
  - 링크 예시: [Google](https://www.google.com)
  - 이미지 예시: 
    ![Markdown Logo](https://markdown-here.com/img/icon256.png)

> "Markdown은 문서 작성의 단순성과 효율성을 극대화시킵니다."

---

### Step 2: 수정된 파일 저장
- 메모장이나 텍스트 편집기에서 수정한 내용을 **저장**합니다.

### Step 3: Git을 사용하여 변경 사항 커밋 및 푸시
1. **Git 명령어로 변경 사항 추가 및 커밋**:
   ```shell
   git add README.md
   git commit -m "Update README.md with course overview and details using Markdown elements"