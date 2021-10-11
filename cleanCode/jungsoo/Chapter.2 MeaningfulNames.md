# Chapter.2 MeaningfulNames

## 의도를 분명히 밝혀라

- 존재 이유는? 수행 기능은? 사용 방법은? 질문에 답할 수 있어야 한다.

## 그릇된 정보를 피하라

- 여러 계정을 그룹으로 묶을 때, 실제 List가 아니라면, List가 포함된 단어로 명명하지 마라.
계정을 담는 컨테이너가 실제 List가 아니라면 프로그래머에게 그릇된 정보를 제공하는 셈이다.
Group이나 Bunch라는 언어로 명명하라.
- 흡사한 이름을 사용하지 마라.
- 유사한 개념은 유사한 표기법을 사용하라.
일관성이 떨어지는 표기법은 그릇된 정보다.

## 의미 있게 구분하라

- 연속된 숫자를 덧붙이거나 불용어를 추가하는 방식도 적절하지 못하다.
Info나 Data는 의미가 불분명한 불용어다.
- 이름에 차이를 둔다면 읽는 사림이 차이를 알도록 이름을 지어라.

- 발음하기 쉬운 이름을 사용하라
- 검색하기 쉬운 이름을 사용하라
⇒ 긴 이름이 짧은 이름보다 좋다.
⇒ 이름 길이는 범위 크기에 비례해야 한다.
- 인코딩을 피하라.
⇒ 요즘에는 컴파일러가 타입을 기억하고 강제한다.
⇒ 자바 ㅡㅍ로그래머는 벼수 이름에 타입을 인코딩할 필요가 없다.
⇒ 객체는 Strongly-typed이며, IDE는 코드를 컴파일하지 않고 타입 오류를 감지할 정도로 발전했다.
⇒ 접두어는 옛날에 작성항 구닥다리 코드의 징표가 되버린다.
⇒ 인터페이스 이름은 접두어를 붙이지 않는 편이 좋다고 생각한다.

## 자신의 기억력을 자랑하지 마라

- 자신만 기억하는 변수로 명명하지 마라.
- 전문가 프로그래머는 자신의 능력을 좋은 방향으로 사용해 남들이 이해하는 코드를 내놓는다.

## 클래스 이름

- 명사 or 명사구 (추상적인 단어, Manager, Processor, Data, Info등과 같은 단어는 피하자)

## 메서드 이름

- 동사 or 동사구
- 접근자, 변경자, 조건자는 값 앞에 get, set, is를 붙인다.
- 생성자를 중복정의할 때는 정적 팩토리 메서드를 사용한다.
    
    ```java
    Complex fulcrumPoint = Complex.FromRealNumber(23.0); // 보다
    Complex fulcrumPoint = new Complex(23.0); // 이 더 좋다
    ```
    

## 기발한 이름은 피하라

- 재미난 이름보다 명료한 이름을 선택하라
- 의도를 분명하고 솔직하게 표현하라.

## 한 개념에 한 단어를 사용하라

- 메서드 이름은 독자적이고 일관적이어야 한다.
- 일관성 있는 어휘는 프로그래멈가 반갑게 여길 "선물"이다.

## 말장난을 하지 마라

- 한 단어를 두 가지 목적으로 사용하지 마라.
다른 개념에 같은 단어를 사용한다면 그것은 말장난에 불과하다.
- add라는 단어를 썼기에 일관성을 지킨다는 명목으로 개념이 다른 곳에 같은 이름을 사용하지 말자.

- 집중적인 탐구가 필요한 코드가 아니라 대충 훑어봐도 이해할 코드 작성이 목표다.

## 해법 영역에서 가져온 이름을 사용하라

- 기술 개념 (VISITOR 패턴 등)에는 기술 이름이 가장 적합한 선택이다.

## 문제 영역에서 가져온 이름을 사용하라

- 우수한 프로그래머와 설계자라면 해법 영역과 문제 영역을 구분할 줄 알아야 한다.
- 문제 영역 개념과 관련이 깊은 코드라면 문제 영역에서 이름을 가져와야 한다.

## 의미 있는 맥락을 추가하라

## 불필요한 맥락을 없애라

- 일반적으로는 짧은 이름이 긴 이름보다 좋다. 단, 의미가 분명한 경웨 한해서다.
이름에 불필요한 맥락을 추가하지 않도록 주의한다.

- 암기는 요즘 나오는 도구에게 맡기고, 우리는 문장이나 문단처럼 읽히는 코드 아니면 적어도 표나 자료 구조처럼 읽히는 코드를 짜는 데만 집중해야 마땅하다.