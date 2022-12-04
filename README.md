# Private gitignore

## 1. Private gitignore 설정
Github에 커밋을 진행할 때 무시할 파일 및 디렉토리에 대해서 .gitignore 파일을 통해서 무시 할 수 있다.<br>
이것에 대해서 매번 프로젝트별 생성하는것이 불편함이 있어 Git에서 Global 하게 사용을 하고자 한다.<br>
해당 방법은 아래 사이트를 통해서 자세히 작성 해놓았다.
- https://happylie.tistory.com

## 2. 사용 방법
### 2.1 Git Clone
```bash
$ git clone https://github.com/happylie/gitignore.git
```

### 2.2 Git Global Config 설정
```bash
$ git config --global core.excludesfile {git clone path}/gitignore_global
```

### 2.3 Git Global Config 확인
```bash
$ git config --list

... 이하 생략 ...
core.excludesfile={설정한 파일 위치}
... 이하 생략 ...
```

## 3. 참고 문서
- https://github.com/github/gitignore
- https://www.toptal.com/developers/gitignore
- https://docs.github.com/ko/get-started/getting-started-with-git/ignoring-files?platform=mac