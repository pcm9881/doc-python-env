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

## uv 활용

### uv 버전 확인

```sh
$ uv --version
uv 0.9.14 (Homebrew 2025-12-01)
```

### uv init
```sh
$ uv init
Initialized project `프로젝트 경로`
```

### uv virtualenv 생성

```sh
$ uv venv --python 3.13.0
Using CPython 3.13.0
Creating virtual environment at: .venv
Activate with: source .venv/bin/activate
```

### virtualenv 실행

```sh
$ source .venv/bin/activate
```

### uv 파이썬 버전 설정

```sh
$  uv python pin 3.13
Pinned `.python-version` to `3.13`
```

### uv main.py 실행

```sh
$  uv run python main.py
```

