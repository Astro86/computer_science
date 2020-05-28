# 메모리 관리
1. 기본적인 메모리 관리
2. swapping
3. 가상 메모리
4. Page replacement 알고리즘
5. 세그멘테이션


프로그래머들이 가장 바라는 메모리는 바로

1. 크고
2. 빠르고
3. 비 휘발성인것을 원한다.


## Memory Manager(메모리 관리자)
- 메모리 계층을 관리하는 운영체제의 일부분
- 사용하고 있는 메모리와 사용하고있지 않는 메모리를 계속해서 추적한다.
- 메모리를 프로세스에 할당하고 해제한다.
- 프로세스의 용량이 커서 메모리에 용량이 작을 경우 메모리와 디스크를  swapping한다.

## 기본적인 메모리 관리 기법

### paging이나 swapping이 없는 단일 프로그램


## 메모리보다 더 큰 Program의 등장

프로그램이 점점 커지다 보니 우리가 사용하는 메인 메모리보다 큰 프로그램이 생겨나게 됐다. 이를 해결하기 위한 방법으로 `1. overlay`와 `2. virtual memory` 방법이 나왔다.

overlay와 virtual memory의 기본 아이디어는 하나의 프로그램을 여러가지 조각으로 나누어 실행한다는 공통점이 있다. 하지만, overlay의 경우에는 프로그래머가 직접 프로그램들을 나누어야 하고 virtual memory의 경우에는 컴퓨터가 대신해준다는 차이점이 있다.

## Virtual Memory

Virtual Memory는 `paging`기법과 `segmentation` 기법을 이용한다.

- paging : 고정분할
- segmentation : 가변분할## 메모리보다 더 큰 Program의 등장

프로그램이 점점 커지다 보니 우리가 사용하는 메인 메모리보다 큰 프로그램이 생겨나게 됐다. 이를 해결하기 위한 방법으로 `1. overlay`와 `2. virtual memory` 방법이 나왔다.

overlay와 virtual memory의 기본 아이디어는 하나의 프로그램을 여러가지 조각으로 나누어 실행한다는 공통점이 있다. 하지만, overlay의 경우에는 프로그래머가 직접 프로그램들을 나누어야 하고 virtual memory의 경우에는 컴퓨터가 대신해준다는 차이점이 있다.
