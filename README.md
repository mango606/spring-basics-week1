# 메모장 프로젝트

기본적인 메모장 기능을 구현한 프로젝트입니다. 메모를 생성, 조회, 수정, 삭제할 수 있습니다.

![image](https://github.com/user-attachments/assets/3e7d274e-77da-47ea-b77b-19e46e9930e4)

## 프로젝트 구조

- **메모장 프로젝트 생성**
    - 프로젝트의 기본 환경을 설정합니다.
    - Spring Boot와 필요한 의존성을 포함합니다.

- **Create, Read 구현하기**
    - **Create**: 사용자가 새로운 메모를 추가할 수 있습니다.
    - **Read**: 사용자가 저장된 모든 메모를 조회할 수 있습니다.
    - 구현 방법:
        - `MemoController`를 생성하고 `@PostMapping`과 `@GetMapping`을 사용하여 메모 생성과 조회 기능을 구현합니다.

- **Update, Delete 구현하기**
    - **Update**: 사용자가 기존의 메모를 수정할 수 있습니다.
    - **Delete**: 사용자가 메모를 삭제할 수 있습니다.
    - 구현 방법:
        - `MemoController`에 `@PutMapping`과 `@DeleteMapping`을 추가하여 수정과 삭제 기능을 구현합니다.

- **JDBC 연결하기**
- **역할 분리하기**
  - Controller는 API 요청을 받고 Service에 받아온 데이터와 함께 요청을 보냅니다.
  - Service는 해당 요청을 수행하고, DB 작업을 Repository에 요청합니다.
  - Repository는 DB와 연결 및 CRUD 작업을 담당합니다.

## 강의 목록

- [x] Spring 입문주차 1주차
- [x] Spring 입문주차 2주차

## 참고 자료

- [Spring 공식 문서](https://spring.io/docs)
- [Spring 프로젝트 예제](https://github.com/spring-projects/spring-petclinic)
