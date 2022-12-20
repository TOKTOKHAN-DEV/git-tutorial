## 📄 Desc
상위(Upstream) 레포지토리에 기여하고자 복제(fork)한 레포지토리 입니다.
```
 - master에 직접 커밋한 사항 (commit #3-2)
 - develop에 직접 커밋한 사항 (commit #3-3)
 - feature/4에 직접 커밋한 사항 (commit #4)
```
상위 레포지토리로 반영하기 이전에 커밋 사항을 **로컬에서** 통합하는 과정을 수행해봅니다.
갈라진 develop, master 변경 사항을 feature 브랜치로 모두 통합 반영합니다.
통합된 브랜치에서 develop으로 PR을 생성할 준비를 하는 상황이라고 가정해봅시다!

## ☝🏻 Info
1. 본 레포지토리를 내려받습니다.(clone)
2. 로컬에서 `feature/4` 브랜치로 이동합니다. (checkout)
3. feature/4 브랜치에서 develop, master 변경 사항(#3-2, #3-3)을 모두 포함시킵니다.


**(단, 로컬에서만 해당 작업을 수행하며, origin에 반영(push)하지 않습니다.)**



## 🎯 Todo
<img width="975" alt="스크린샷 2022-12-20 오후 3 07 33" src="https://user-images.githubusercontent.com/17680551/208595797-19bf2a91-8347-4baa-bc8d-3ebd59387892.png">


## 🔍 More
- 위 Todo 이미지에서 문제로 보여지는 부분은 어떤 부분이며, 이를 어떻게 해결할 수 있을까요?
- 상위 레포지토리에는 fork 시점 이후에 #3-1 커밋이 발생한 상황입니다. 본 레포지토리에서의 수정사항과 통합하려면 어떻게 해야할까요?


## 📚 Refs
 - [[Git]오픈소스 기여 및 협업을 위한 rebase 활용 방법, git blame 명령어로 오픈 소스 분석하기](https://ihp001.tistory.com/229)
 - [An introduction to Git merge and rebase: what they are, and how to use them](https://www.freecodecamp.org/news/an-introduction-to-git-merge-and-rebase-what-they-are-and-how-to-use-them-131b863785f/)
 - ["Rebase everything so you get a clean timeline without meaningless "merge of bla" commit messages"](https://news.ycombinator.com/item?id=18227090)
