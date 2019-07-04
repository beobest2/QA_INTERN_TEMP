# 02. 테스트 기본

## 단위테스트 만들어보기

### 실습내용

첫 번째 실습에서 만들었던 문자열 뒤집기 프로그램의 단위테스트 코드를 만들어주세요.

완성된 테스트 프로그램은 `https://github.com/leehaejoon/QA_INTERN_TEMP/tree/master/src/02.test_basic` 하위에 각자의 이름이 적힌 폴더에 올려주세요.

파일명은 본인이 작성한 문자열 뒤집기 프로그램 이름 앞에 `test_` 라는 접두어를 붙인 형태로 만들어주세요. 

단위테스트라는 용어에 생소할수 있으니, 아래 간략하게 부가설명을 드리겠습니다.

### 단위테스트

하나의 프로그램은 한 개 이상의 '단위' 기능으로 구성되어있습니다.

첫번째 실습으로 진행했던 문자열 뒤집기 프로그램을 생각해보면,

1. 파일에 적힌 문자열을 읽어들이는 기능

2. 읽어들인 문자열을 원하는 형태로 변형하는 기능

3. 완성된 문자열을 다시 파일에 쓰는 기능

처럼 세 개의 단위 기능으로 이루어진 프로그램으로 볼 수도 있고,

그냥 단순히

1. 파일의 문자열을 뒤집어서 다시 파일로 쓰는 기능

처럼 한 개의 단위기능으로 이루어진 프로그램으로 볼 수도 있습니다.

이 단위를 나누는 기준을 세우는 것은 개발자 자신의 몫이 될 수도 있고,

고객의 요구사항에 따라 결정될수도 있습니다.

<br/>

어쨌든, 모든 단위 프로그램이 제대로 동작해야 하나의 소프트웨어가 완성되는 것입니다.

이를 바꿔말하면, 한 개의 기능이라도 오동작하게되면 소프트웨어는 완성되지 않습니다.

따라서 모든 단위 기능이 제대로 동작하는지 테스트 하는 것은 매우 중요합니다.

<br/>

이처럼 각 단위 기능이 요구사항에 맞게 정확히 동작하는지 검증하는 것을 단위테스트라고 합니다.

파이썬에서 어떤 방식으로 단위테스트를 하고있는지에 관해서는 인터넷에서 수많은 레퍼런스를 찾을 수 있을 것입니다.

만들어주세요!