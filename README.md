# 2023-HAI-Kaggle-Study
2023년 1학기 HAI 캐글스터디 활동 사항을 기록하기 위한 repo입니다.
주별로 자신이 작성한 스터디 내용을 본 레포에 등록합니다.

## 과제 등록 방법

이 레포지토리를 자신의 계정에 Fork한 후, Pull Request를 날려주시면 됩니다.

1. 아래 이미지와 같이 자신의 계정으로 이 레포지토리를 Fork합니다.

<img width="1018" alt="Fork 방법" src="https://user-images.githubusercontent.com/5627185/158590352-6e892863-3182-4e2c-865b-3e482923806b.png">

2. 이후, github에서 Code 부분을 눌러 나오는 git 링크를 복사합니다.
 
<img width="958" alt="git clone" src="https://user-images.githubusercontent.com/5627185/158590642-063a7c64-05e7-4d4d-b9c1-e924e41dda5b.png">

3. 자신의 컴퓨터에서 원하는 위치에서 git clone을 합니다.

```shell
$ git clone https://github.com/<YOUR_USERNAME>/2023-HAI-Paper-Study.git
```

4. clone 후 해당 폴더에 들어가고, 자신만의 branch를 만듭니다. branch name은 `week<주차>/영어이름`로 해주세요.

```shell
$ cd 2023-HAI-Paper-Study.git
$ git checkout -b week1/hyunwoo
```

5. 해당 Repo를 VSCode와 같은 코드편집기로 연 후, 각 주차별 폴더에 자신의 과제파일을 만듭니다. 과제명은 `한글이름.md`로 해주세요.

```
$ vi week1/1주차_이현우.md //또는 원하는 코드편집기를 사용해주세요.
```

6. 과제를 작성 후에는 아래와 같이 Commit을 진행해주세요. 커미 메세지는 `docs: 이름 n주차`로 작성해주세요. 

```
$ git add week1/1주차_이현우.md
$ git commit -m "docs: 이현우 1주차"
```

7. 과제를 레포로 push해주세요.

```
// 처음 repo로 push할 시
$ git push --set-upstream origin week1/hyunwoo

// 이전에 push한 적이 있을 때
$ git push
```

8. Pull Request로 이동하여 자신의 Pull Request를 만듭니다.

<img width="1128" alt="make pr" src="https://user-images.githubusercontent.com/5627185/158592434-7acab4e4-21cd-4499-be17-40ee90e7fcde.png">

9. base repository는 HAI Repo의 master branch를 선택해주시고, head repository는 여러분 계정에 Fork한 레포의 여러분이 새로 만든 branch를 선택해주세요.

<img width="1135" alt="check branch" src="https://user-images.githubusercontent.com/5627185/158592636-6c7d7978-8552-48b2-ad9b-fdd725cbbe4c.png">

10. 제목은 [n주차 과제 제출] 이름, 내용을 작성하고 Assignees를 자신으로 설정해주세요. 이후 Create Pull Request를 누릅니다.

<img width="1145" alt="submit" src="https://user-images.githubusercontent.com/5627185/158592788-45d734f3-bdc9-469e-8eee-8c23d91c3a16.png">

이후, 임원진이 과제를 검토 후 과제 체크를 해드릴 예정입니다!
