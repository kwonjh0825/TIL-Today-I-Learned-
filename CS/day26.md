## 절차지향 프로그래밍

- Procedural Programming
- 프로시저(메서드, 함수, 하위 프로그램 등)을 이용하여 작성하는 프로그래밍 방식
- 프로시저 콜(함수 호출) 개념을 바탕으로 하는 프로그래밍 패러다임
- 기능 중심
- 어떤 기능을 어떤 순서로 처리할 것인지
- 특징
    - 하나의 큰 기능을 처리하기 위해 작은 단위의 기능들로 나누어 처리하는 Top-down 접근 방식
    - 데이터와 함수를 별개 취급
    - 모든 함수는 데이터 공유 가능
    - 정해진 순서대로 입력해야 하므로 순서가 바뀌면 결과를 도출하기 어려움
    - 프로그램이 커지면 구조가 복잡해져 유지보수가 어려움

## 객체지향 프로그래밍

- Object-Oriented Programming
- 프로그램 구현에 필요한 객체를 파악하고 각각의 객체들의 역할이 무엇인지를 정의하여 객체 간 상호작용을 통해 프로그램을 만드는 것
- 객체란 우리가 실생활에서 쓰는 모든 것. 클래스라는 틀에서 생겨난 실체
- 객체 중심
- 누가 어떤 일을 할 것인지
- 특징
    - 추상화(Abstraction)
        - 구체적으로 정의하는 것이 아니라 필요한 정보만을 중심으로 간소화하는 것
    - 캡슐화(Encapsulation)
        - 객체가 독립적인 역할을 할 수 있도록 데이터와 기능을 하나로 묶어 관리
        - 실제 구현되는 부분을 외부에 드러나지 않도록 하여 정보 은닉 가능
    - 상속성(Inheritance)
        - 하나의 클래스가 가진 데이터나 기능을 다른 클래스가 그대로 물려받는 것
        - 기존 코드를 재사용하여 확장시킬 수 있음
    - 다형성(Polymorphism)
        - 하나의 클래스나 메서드가 다양한 방식으로 동작이 가능한 것
        - 오버라이딩(overriding): 상속받은 자식 클래스에서 부모 클래스의 메서드와 같은 이름을 사용하고 매개 변수와 리턴 타입도 같은 상태에서 기능을 재정의하는 것
        - 오버로딩(overloading): 같은 이름의 함수를 매개변수를 다르게 하여 기능을 재정의하는 것
- 객체지향 설계 5가지 원칙(SOLID)
    - 단일 책임 원칙(Single responsibility principle)
        - 한 클래스는 하나의 책임만 가지고, 클래스는 그 책임을 완전히 캡슐화해야 함
    - 개방-폐쇄 원칙(Open-closed principle)
        - 소프트웨어 개체(클래스, 모듈, 함수 등)은 확정에 대해 열려 있어야 하고, 변경에 대해서는 닫혀 있어야 함
    - 리스코프 치환 원칙(Liskov substitution principle)
        - 프로그램의 객체는 프로그램의 정확성을 깨뜨리지 않으면서 하위 타입의 인스턴스로 바꿀 수 있어야 함
    - 인터페이스 분리 원칙(Interface segregation principle)
        - 클라이언트가 자신이 이용하지 않는 메서드에 의존하지 않아야 함
        - 큰 덩어리의 인터페이스를 구체적이고 작은 단위로 분리함으로써 클라이언트들이 꼭 필요한 메서드만 이용할 수 있도록 해야 함
    - 의존관계 역전 원칙(Dependency inversion principle)
        - 상위 모듈은 하위 모듈에 의존해서는 안됨. 상위 모듈과 하위 모듈 모두 추상화에 의존
        - 추상화는 세부 사항에 의존해서는 안됨. 세부 사항이 추상화에 의존해야 함