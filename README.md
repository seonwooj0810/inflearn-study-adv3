# inflearn-study-adv3

인프런 **김영한의 실전 자바 - 고급 3편 (람다, 스트림, 함수형 프로그래밍)** 학습 저장소입니다.

## 강의 / 학습 정보

- 강의: 김영한의 실전 자바 - 고급 3편
- 플랫폼: 인프런

## 사용 기술

- Java 17+ (단일 모듈, `src` 디렉터리 + IntelliJ 모듈 구성)
- 자바 표준 라이브러리: 함수형 인터페이스, Stream API, Optional, Fork/Join

## 학습한 내용 (코드 근거)

- 람다와 함수형 인터페이스: SAM 인터페이스, 람다 전달/캡처, 타깃 타입, 제네릭 활용 (`lambda/lambda1`~`lambda6`)
- 표준 함수형 인터페이스: `Function`, `BiFunction`, `Supplier`, `Predicate`, `Operator`, 기본형 특화 함수 (`lambda/lambda4`)
- 스트림 직접 구현으로 원리 학습: `MyStreamV1`~`V3`, filter/map 제네릭 구현 (`lambda/lambda5`)
- 메서드 참조: 정적/인스턴스/생성자 참조 (`methodref`)
- 디폴트 메서드: 인터페이스 기본 구현 활용 (`defaultmethod`)
- Stream API: 생성, 중간/최종 연산, 지연 평가, `flatMap`, 기본형 스트림, Collectors(grouping/partitioning/reducing 등) (`stream`)
- Optional: 생성, `orElse`/`orElseGet`, 체이닝 활용 (`optional`)
- 병렬 처리: 병렬 스트림, Fork/Join 프레임워크 (`parallel`)

## 프로젝트 구조

```
inflearn-study-adv3/
└── src/
    ├── lambda/        # 람다, 함수형 인터페이스, 직접 구현 스트림
    ├── methodref/     # 메서드 참조
    ├── defaultmethod/ # 디폴트 메서드
    ├── stream/        # Stream API (연산, Collectors)
    ├── optional/      # Optional
    └── parallel/      # 병렬 스트림, Fork/Join
```
