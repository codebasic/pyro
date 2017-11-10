# pyko

한국어 텍스트 처리를 위한 파이썬 라이브러리입니다. 자연어 처리에서 한국어가 갖는 독자적인 특징을
반영해 처리합니다.

## 설치

PyPI에 등록된 패키지를 다음과 같이 설치할 수 있습니다.

    pip install pyko

시스템에 JDK가 설치되어 있어야 합니다.

한국어 처리와 관련한 여러 라이브러리들은 C++, Java, Scala 등으로 작성되어 제공되고 있습니다.
이러한 라이브러리들을 파이썬에서 편리하게 활용할 수 있도록 합니다.

다음의 한국어 처리 기능을 지원합니다.

## 정규화

맞춤법이 틀리거나, 변형되어 작성된 텍스트를 올바른 맞춤법과 사전에 수록된 단어로 변형하는 과정입니다.

* 입니닼ㅋㅋ --> 입니다 ㅋㅋ
* 샤릉해 --> 사랑해

## 토큰화

문장을 품사에 따라 각각 분리하는 과정입니다.

한국어를 처리하는 예시입니다 -->
한국어, 를, 처리, 하는, 예시, 입니다

## 의존성 라이브러리

[open-korean-text](https://github.com/open-korean-text/open-korean-text)

프로젝트에 대한 파이썬 인터페이스를 지원합니다.
