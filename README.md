# 메모장 프로젝트

기본적인 메모장 기능을 구현한 프로젝트입니다. 메모를 생성, 조회, 수정, 삭제할 수 있습니다.

![image](https://github.com/user-attachments/assets/b46bd5ab-43f9-4669-bf14-eb7283f87825)


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
