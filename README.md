# taddy-rag-notes

## 환경설정

### Use virtual env

- Install pyenv

```bash
brew update
brew install pyenv
```

- set venv

```bash
python3.11 -m venv myenv
```

- virtual env コマンド

```bash
# activate env
source myenv/bin/activate

# deactivate
deactivate
```

- Install poetry (virtual env 가 activated 된 상태에서 진행하기)

```bash
pip3 install poetry

# 파이썬 가상환경 설정
poetry shell

# 파이썬 패키지 일괄 업데이트
poetry update
```

### Use Local python

- Install pyenv

```bash
brew update
brew install pyenv
```

- Install python

```bash
pyenv install 3.11
pyenv global 3.11

# 현재 실행 중인 셸(shell)을 새로운 zsh 프로세스로 완전히 교체하는 명령어입니다.
exec zsh
```

- Install poetry

```bash
pip3 install poetry

# 파이썬 가상환경 설정
poetry shell

# 파이썬 패키지 일괄 업데이트
poetry update
```

- [mac](https://teddynote.com/10-RAG%EB%B9%84%EB%B2%95%EB%85%B8%ED%8A%B8/%ED%99%98%EA%B2%BD%20%EC%84%A4%EC%A0%95%20(Mac)/)
- [windows](https://teddynote.com/10-RAG%EB%B9%84%EB%B2%95%EB%85%B8%ED%8A%B8/%ED%99%98%EA%B2%BD%20%EC%84%A4%EC%A0%95%20(Windows)/)

## 강의에서 사용되는 External Services

### LLM services

- [OpenAI API](https://platform.openai.com/docs/overview)
- [LangSmith API](https://smith.langchain.com/)
  - code 를 실행할 때, 코드의 추척을 위해서 한다.(ex. langchain 의 pipeline 을 추적)

### Langchain Services


## Wiki docs 의 활용법

[langchain note](https://wikidocs.net/book/14314)

## Links

- [langchain note](https://wikidocs.net/book/14314)
- [Lecture Codes](https://github.com/teddylee777/langchain-kr)
- [데이터 분석 블로그](https://teddylee777.github.io/)
- [저자 youtube](https://www.youtube.com/c/@teddynote)
