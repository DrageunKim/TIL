# TIL
> 야곰 아카데미 진행 중에는 적고 싶어도 힘들어서 적지 못했던 TIL... 이제부터라도...🔥

### [23년]

<details> 
<summary> 2월 </summary>

- 23일
  - SOLID 
  - Frame vs Bound - Frame:SuperView 기준, Bound:View기준
  - 실제 디바이스가 없을 경우 개발 환경에서 할 수 있는 것과 없는 것을 설명 - 센서, 통신 불가
  - TabBarController에서 NavigationItem 사용방법

- 24일
  - Stack 활용 : LIFO 구조
  - Queue 활용 : FIFO 구조
  - Deck : 앞뒤로 데이터 추가 가능
- 25일
  - OAuth 기본개념 : SNS 로그인
  - 모바일앱이 모바일웹에 비해 좋은 점 : 빠른 속도와 안정적인 동작
- 26일
  - API
  - REST - HTTP를 잘 활용하기 위한 아키텍쳐
  - RESTful API - HTTP를 잘 활용할 수 있도록 짜여진 구조
- 27일
  - 운영체제 & 인터럽트
  - 최대공약수와 최소공배수 - 최대공약수 x 최소공배수 = 두 값의 곱
  - 소수 찾기 - 에라토스테네스의 체 (빈 배열을 만들어 소수가 아닌 것은 삭제)
  - 팩토리얼의 0의 개수 - 2와 5의 갯수
  - URL Request

</details>

<details> 
<summary> 3월 </summary>

- 1일
  - 앱의 콘텐츠나 데이터 자체를 저장/보관하는 특별한 객체를 무엇이라고 하는가?
  - App thinning에 대해서 설명하시오.
  - 앱이 시작할 때 main.c 에 있는 UIApplicationMain 함수에 의해서 생성되는 객체는 무엇인가?
  - @Main에 대해서 설명하시오.
  - 앱이 foreground에 있을 때와 background에 있을 때 어떤 제약사항이 있나요?
  - 상태 변화에 따라 다른 동작을 처리하기 위한 앱델리게이트 메서드들을 설명하시오.
  - 앱이 In-Active 상태가 되는 시나리오를 설명하시오.
  - scene delegate에 대해 설명하시오.
  - UIApplication 객체의 컨트롤러 역할은 어디에 구현해야 하는가?
  - App의 Not running, Inactive, Active, Background, Suspended에 대해 설명하시오.
  - GCD API 동작 방식과 필요성에 대해 설명하시오.
  - Global DispatchQueue 의 Qos 에는 어떤 종류가 있는지, 각각 어떤 의미인지 설명하시오. 

  <br/>

  - 알고리즘 - 다이나믹 프로그래밍
  - 서울 공공데이터 API 사용을 위한 사전 준비
    - addingPercentEncoding
    - ATS Policy

- 2일

  - RxSwift 기초
    - DispatchQueue & RxSwift 차이점
    - Observable 생성 & Operation 사용
    - Subscribe 사용
    - Scheduler
    - 코드 간소화 (RxCocoa도 함께 사용)
    - RxSwift 응용
      - ID & PW 형식에 맞는지 확인 후 로그인 해보는 실습
    - Subject

- 4일

  - iOS 앱을 만들고, User Interface를 구성하는 데 필수적인 프레임워크 이름은 무엇인가?
  - Foundation Kit은 무엇이고 포함되어 있는 클래스들은 어떤 것이 있는지 설명하시오.
  - Delegate란 무엇인지 설명하고, retain 되는지 안되는지 그 이유를 함께 설명하시오.
  - NotificationCenter 동작 방식과 활용 방안에 대해 설명하시오.
  - UIKit 클래스들을 다룰 때 꼭 처리해야하는 애플리케이션 쓰레드 이름은 무엇인가?
  - App Bundle의 구조와 역할에 대해 설명하시오.
  - 모든 View Controller 객체의 상위 클래스는 무엇이고 그 역할은 무엇인가?
  - 자신만의 Custom View를 만들려면 어떻게 해야하는지 설명하시오.
  - View 객체에 대해 설명하시오.
  - UIView 에서 Layer 객체는 무엇이고 어떤 역할을 담당하는지 설명하시오.
  - UIWindow 객체의 역할은 무엇인가?
  - UINavigationController 의 역할이 무엇인지 설명하시오.
  - TableView를 동작 방식과 화면에 Cell을 출력하기 위해 최소한 구현해야 하는 DataSource 메서드를 설명하시오.
  - 하나의 View Controller 코드에서 여러 TableView Controller 역할을 해야 할 경우 어떻게 구분해서 구현해야 하는지 설명하시오.
  - setNeedsLayout와 setNeedsDisplay의 차이에 대해 설명하시오.
  - stackView의 장점과 단점에 대해서 설명하시오.

- 5일

  - NSCache와 딕셔너리로 캐시를 구성했을때의 차이를 설명하시오.
  - URLSession에 대해서 설명하시오.
  - prepareForReuse에 대해서 설명하시오.
  - 다크모드를 지원하는 방법에 대해 설명하시오.
  - ViewController의 생명주기를 설명하시오.
  - TableView와 CollectionView의 차이점을 설명하시오.

  <br/>

  - 오토레이아웃을 코드로 작성하는 방법은 무엇인가? (3가지)
  - hugging, resistance에 대해서 설명하시오.
  - Intrinsic Size에 대해서 설명하시오.
  - 스토리보드를 이용했을때의 장단점을 설명하시오.
  - Safearea에 대해서 설명하시오.
  - Left Constraint 와 Leading Constraint 의 차이점을 설명하시오.

  <br/>

  - MVVM + RxSwift 기초
    - 이전에 다뤘던 ID & PW를 입력하여 로그인하는 예제를 활용하여 코드 작성

- 6일

  - 운영체제

    - 프로세스 vs 쓰레드
    - 프로세스 주소 공간
    - 시스템 콜 (System Call)
    - IPC (Inter Process Communication)
  - 알고리즘
    - 다이나믹 프로그래밍1 - 2차원 배열 활용
  - 동시성 프로그래밍 (원티드프리온보딩 1)
    - 용어 정리
    - 사전과제 코드 리뷰

- 7일

  - 알고리즘
    - 다이나믹 프로그래밍1 - 기본예제 끗
  - 동시성 프로그래밍 (원티드프리온보딩 2)
    - DispatchQueue 부가기능
    - OperationQueue vs Dispatch Queue

- 8일

  - 코드 팩토링
    - 네트워크 설계
    - 네트워크 삽질의 흔적

- 9일

  - RxSwift 개념 다듬기
  - 알고리즘
    - 그리디 개념 세우기



- 12일

   - struct와 class와 enum의 차이
   - class의 성능을 향상 시킬수 있는 방법
   - Copy On Write는 어떤 방식으로 동작
   - Convenience init
   - Any & AnyObject
   - Optional
   - Struct
   - Subscripts
   - String은 왜 subscript로 접근이 안되는지

   <br/>

   - 다이나믹 프로그래밍
     - 개념
     - 사용하는 조건
     - 구현 방법
     - 다이나믹 프로그래밍과 분할 정복의 차이점

- 13일
  - 알고리즘
    - 브루트 포스 (완전 탐색)
    - DFS & BFS

- 15일

   - 알고리즘
      - 브루트 포스
         - 자리수 구하는 방법 - **%10** 사용
         - 절대값 구하는 방법 - **abs** 사용
         - 최대공약수 구하는 방법 (유클리드 호제법)
      
   - 코드 팩토링
      - RxSwift
         - Bind vs Subscribe

- 16일
  - 알고리즘
    - 브루트 포스 (N과 M)
  - 코드 팩토링
    - 진동 동작시키는 3가지 방법
    - Xcode - Refactor 안될 때 해결법

- 23일
  - 개념정리
    - MVC VS MVVM
  - 알고리즘
    - 브루트 포스 - 순열

- 24일

   - 개념정리
      - instance 메서드와 class 메서드의 차이점을 설명하시오.
      - class 메서드와 static 메서드의 차이점을 설명하시오.
      - Delegate 패턴을 활용하는 경우를 예를 들어 설명하시오.
      - Singleton 패턴을 활용하는 경우를 예를 들어 설명하시오.
      - KVO 동작 방식에 대해 설명하시오.
      - Delegates와 Notification 방식의 차이점에 대해 설명하시오.
      - 멀티 쓰레드로 동작하는 앱을 작성하고 싶을 때 고려할 수 있는 방식들을 설명하시오.
      - MVC 구조에 대해 블록 그림을 그리고, 각 역할과 흐름을 설명하시오.
      - 접근 제어자의 종류엔 어떤게 있는지 설명하시오.
   - 알고리즘
      - 브루트 포스 - 순열
      - DFS


</details>
