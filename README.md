# 파이썬 프로젝스 환경설정 예제

## pyenv 활용

### pyenv 버전 확인

```sh
$ pyenv --version
$ pyenv 2.3.36
```

### pyenv virtualenv 생성

```sh
$ pyenv virtualenv 3.12.2 python-project-env
```

### pyenv virtualenv 목록 확인

```sh
$ pyenv virtualenvs
```

### pyenv virtualenv local 설정

```sh
$ pyenv local python-project-env
```

- `.python-version` 파일 생성됨

### pyenv virtualenv local 확인

```sh
$ pyenv local
```
