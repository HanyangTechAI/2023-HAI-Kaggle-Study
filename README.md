# 2023-HAI-Kaggle-Study
2023년 1학기 HAI 캐글스터디 활동 사항을 기록하기 위한 repo입니다.
주별로 자신이 작성한 스터디 내용을 본 레포에 등록합니다.

## 과제 등록 방법

이 레포지토리를 자신의 계정에 Fork한 후, Pull Request를 날려주시면 됩니다.

#### 1. 아래 이미지와 같이 자신의 계정으로 이 레포지토리를 Fork합니다.

![image](https://user-images.githubusercontent.com/44901828/229419810-c85cb7d7-f081-4c72-ba72-b3a985ec89fa.png)

#### 2. 이후, github에서 Code 부분을 눌러 나오는 git 링크를 복사합니다.
 
![image](https://user-images.githubusercontent.com/44901828/229420011-a26b7509-7f03-498a-bebc-b971f3dc6d64.png)

#### 3. 자신의 컴퓨터에서 원하는 위치에서 git clone을 합니다.

```shell
$ git clone https://github.com/<YOUR_USERNAME>/2023-HAI-Kaggle-Study.git
$ cd 2023-HAI-Kaggle-Study
```

#### 4. Clone된 Repo를 연 다음, 각 주차별 폴더에 자신의 한글 이름으로 된 폴더를 생성하고, 해당 폴더에 .py, .ipynb 또는 설명을 위한 .md 파일 등을 저장합니다.

```
$ mkdir week1/이성진
$ vi week1/이성진/README.md // 또는 원하는 코드편집기를 사용해주세요.
```

#### 5. 과제를 작성 후에는 아래와 같이 Commit을 진행해주세요. 커밋 메세지는 `이름 n주차`로 작성해주세요. 

```
$ git add week1/이성진/*
$ git commit -m "이성진 1주차"
```

#### 6. 과제를 레포로 push해주세요.

```
// 처음 repo로 push할 시
$ git push --set-upstream origin week1/seongjin

// 이전에 push한 적이 있을 때
$ git push
```

#### 7. Pull Request로 이동하여 자신의 Pull Request를 만듭니다.

![image](https://user-images.githubusercontent.com/44901828/229422285-9b49efb8-1839-4cf2-9c0b-4bead18264f5.png)

#### 8. base repository는 HAI Repo의 master branch를 선택해주시고, head repository는 여러분 계정에 Fork한 레포의 master branch를 선택해서 fork된 repo의 변경사항이 반영될 수 있도록 해주세요.

![image](https://user-images.githubusercontent.com/44901828/229422893-d8794c4c-5723-4baa-8439-ddfc8533a0e3.png)

#### 9. 제목은 [n주차 과제 제출] 0조 000(이름), 본문에는 과제에 대한 간단한 설명을 작성해주세요. 이후 Create Pull Request를 누릅니다.

![image](https://user-images.githubusercontent.com/44901828/229423543-0ce4087b-b6e2-441f-9fa7-753217512e57.png)

이후, 임원진이 과제를 검토 후 과제 체크를 해드릴 예정입니다!
