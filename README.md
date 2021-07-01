# 42

> The Answer to the Ultimate Question of Life, the Universe, and Everything is 42.

2020년 2월 24일부터 현재까지, 42서울의 카뎃(Cadet)으로서 진행해온 프로젝트를 정리하기 위한 문서입니다. 42서울의 본과정(42 Cursus)은 각 단계를 서클(Circle)로 구분하여, 0번 서클부터 6번까지 총 일곱 단계로 나뉘어 있습니다. 3번 서클까지는 특정 프로그램(Wordpress, MySQL 등)이나 어셈블리어, 쉘스크립트를 사용하는 경우 외에는 C 언어로 과제를 수행하며, 4번 써클의 "CPP Modules(총 9개의 모듈로 구성)"을 시작으로 C++ 언어로 프로그램을 작성합니다. 단, 마지막 과제인 "ft_transcendence"는 이너서클(inner circle)에서 한 번도 사용하지 않았던 언어인 타입스크립트로 프로그램을 작성합니다.

과제 중 "Minishell", "Webserv", "ft_transcendence"는 동료들과 협업하는 팀프로젝트입니다.

## Piscine

1기 1차 피신(Piscine): 2020.1.20 ~ 2.15.

4주간 진행하는 사전 과정, "피신(Piscine)"을 통해 본과정에 합류할 인원을 선발합니다. 피신은 진행기간 동안 24시간 클러스터(교육장)를 개방해, 각자의 실력에 맞춰 과제를 수행하며 학습하는 프로그램입니다. 매주 금요일에 시험을 진행하고, 주말에는 팀프로젝트를 수행합니다. 이 과정에서 합격하면 2년간 본과정을 진행할 자격을 얻습니다.

## 42 Cursus

아래 표는 본과정에서 진행한 프로젝트의 목록입니다.

|    Circle   | 프로젝트 | 개요 | 종료일자 |
|:-----------:|:-------|:----|:-------|
| 0 | [Libft](https://github.com/paikwiki/libft) | 앞으로 진행할 프로젝트를 위해, 일반적인 함수를 모은 C 라이브러리를 만든다. | 2020.4.17. |
| 1 | [Get_next_line](https://github.com/paikwiki/get-next-line) | 파일 디스크립터로부터 개행을 기준으로 한 줄씩 읽어오는 함수를 만든다. | 2020.7.31. |
| 1 | [Ft_printf](https://github.com/paikwiki/ft-printf) | `printf` 함수를 직접 만들어 보며 가변인자 사용법을 익힌다. | 2020.9.2. |
| 2 | [Ft_server](https://github.com/paikwiki/ft-server) | 도커(Docker)를 이용해 첫 웹 서버(Nginx + Wordpress + MySQL)를 실행한다. | 2020.9.9. |
| 2 | [Cub3D](https://github.com/paikwiki/cub3d) | 최초의 FPS 게임인 울펜슈타인(Wolfenstein)을 만들어보는 프로젝트. 레이 캐스팅(ray-casting)을 이용해 미로 속 동적 뷰를 구현한다. | 2020.10.4. |
| 2 | [Exam Rank 02:lock:](https://github.com/paikwiki/42cursus-exam02) | 파일 디스크립터 `0`(stdin)로부터 읽어온 행을 저장하는 함수를 만든다. | 2020.10.6. |
| 3 | [Libasm](https://github.com/paikwiki/libasm) | 어셈블리어와 친숙해지기 위한 프로젝트. | 2020.12.20. |
| 3 | [Minishell](https://github.com/paikwiki/minishell-new) | 간단한 쉘을 구현해보는 프로젝트. 프로세스와 파일 디스크립터에 대해 익힌다. | 2021.2.3. |
| 3 | [Ft_services](https://github.com/paikwiki/ft-services) | 시스템 관리와 네트워킹에 대한 프로젝트. 쿠버네티스(Kubernetes)를 이용해 웹어플리케이션을 운영한다. | 2021.2.25. |
| 3 | [Exam Rank 03:lock:](https://github.com/paikwiki/42cursus-exam03) | "operation file"을 받아 지시대로 터미널 화면에 도형을 출력한다. | 2021.3.5. |
| 4 | [Push_swap](https://github.com/paikwiki/push-swap) | 최적화된 데이터 정렬법을 찾아내는 프로젝트. 최대한 적은 수의 동작으로, 제한적인 동작들을 이용해 변형 스택에 데이터를 정렬한다. | 2021.3.17. |
| 4 | [Philosophers](https://github.com/paikwiki/philosophers) | 프로세스 스레딩에 대한 기초를 배우는 프로젝트. 스레드(thread)와 뮤텍스(mutex), 세마포어(semaphore)에 대해 익힌다. | 2021.3.25. |
| 4 | [CPP Module 00](https://github.com/paikwiki/cpp-module-00) | 토픽: `namespace`, `class`, 멤버 함수, 입출력 스트림, 초기화 리스트, `static`, `const` 등, 기본 지식 | 2021.3.28. |
| 4 | [CPP Module 01](https://github.com/paikwiki/cpp-module-01) | 토픽: 메모리 할당, 참조, 포인터, 파일 스트림 | 2021.4.3. |
| 4 | [CPP Module 02](https://github.com/paikwiki/cpp-module-02) | 토픽: 임시 다형성(Ad-hoc polymorphism), 연산자 오버로드와 캐노니컬 클래스(canonical classes) | 2021.4.4. |
| 4 | [CPP Module 03](https://github.com/paikwiki/cpp-module-03) | 토픽: 상속 | 2021.4.9. |
| 4 | [CPP Module 04](https://github.com/paikwiki/cpp-module-04) | 토픽: 서브타입 다형성(Subtype polymorphism), 추상 클래스, 인터페이스 | 2021.4.15. |
| 4 | [CPP Module 05](https://github.com/paikwiki/cpp-module-05) | 토픽: 예외처리 | 2021.4.17. |
| 4 | [CPP Module 06](https://github.com/paikwiki/cpp-module-06) | 토픽: C++ 캐스팅 | 2021.4.20. |
| 4 | [CPP Module 07](https://github.com/paikwiki/cpp-module-07) | 토픽: C++ 템플릿 | 2021.4.26. |
| 4 | [CPP Module 08](https://github.com/paikwiki/cpp-module-08) | 토픽: 템플릿 컨테이너, 이터레이터, 알고리즘 | 2021.5.3. |
| 4 | [Exam Rank 04:lock:](https://github.com/paikwiki/42cursus-exam04) | 쉘 커맨드를 실행하듯이 동작하는 프로그램을 만든다. | 2021.4.20. |
| 5 | [Ft_containers](https://github.com/paikwiki/ft-containers) | C++ 컨테이너를 재구현하면서 컨테이너에 대해 익힌다. | 2021.6.7. |
| 5 | [Webserv:lock:](https://github.com/innercircle-byebye/sucbaek) | HTTP RFC를 준수하여 실제 브라우저에서 테스트 가능한 HTTP 서버를 만든다. | On progress |
| 5 | Exam Rank 05 | 시험에서 요구하는 C++ 프로그램을 작성한다. | - |
| 6 | ft_transcendence | 아직 한번도 사용해보지 않은 언어와 프레임워크로 진행하는 프로젝트. | - |
| 6 | Exam Rank 06 | - | - |
