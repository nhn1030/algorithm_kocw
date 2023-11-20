[강의출처 : 건국대학교 KOCW 알고리즘 강의 (김강일 교수님)](http://www.kocw.net/home/enrolment/enrolmentView.do?cid=240178eac2f2278d&lid=bec6b498b09bd1ad)


알고리즘은 오랜 역사를 기반으로 하며, 우리가 문제를 어떻게 해결해야 하는가에 대한 고민에서 시작되었다.

## 1. Find a Maximum Number

![](https://velog.velcdn.com/images/rowehnn/post/b2bff0f4-86d0-46e1-9efd-7bf88ee98a7d/image.png)

### Brute-force approach (Sequential Search):
- 순차적으로 각 숫자를 확인하여 최댓값을 찾는 방법.
- 간단하지만 큰 데이터셋에서는 효율적이지 않음.

### Divide and Conquer approach:
- 데이터를 여러 그룹으로 나누어 비교하며 최댓값을 찾음.
- 문제를 더 작은 단위로 나누어 해결하므로 효율적.

## 2. Find a Specific Number

![](https://velog.velcdn.com/images/rowehnn/post/0d014440-7cc3-444d-8be6-73c92aa857f0/image.png)


### Sequential Search:
- 모든 경우를 다 확인하여 원하는 숫자를 찾는 방법.
- 데이터가 많아지면 효율이 떨어짐.

### Binary Search:
- 데이터가 정렬되어 있다는 가정하에 중간값과 비교하여 범위를 좁혀가며 탐색.
- 효율적이지만 정렬된 데이터에만 적용 가능.

### Greedy Algorithm:
- 동전 거스름돈 문제에서 큰 단위의 동전을 우선적으로 거슬러 주는 알고리즘.
- 하지만 모든 경우에 최적해를 보장하지는 않음.

## 3. Euler Trail
![](https://velog.velcdn.com/images/rowehnn/post/32d83c9d-f134-41ce-beb5-4aae5701f382/image.png)

- 그래프에서 모든 간선을 한 번씩 지나는 경로를 찾는 문제.
- 시작과 끝점을 찾아내고, 간선을 지나면서 오일러 패스를 찾는 알고리즘.

## 4. Escape a Maze
![](https://velog.velcdn.com/images/rowehnn/post/2faa1cda-b223-4304-a0b1-535319df98d1/image.png)

- 미로에서 출구까지 탈출하는 문제.
- 백트래킹을 활용하여 갔던 경로를 기억하고, 탈출구를 찾을 때까지 경로를 탐색.

## 5. Find a Fake Coin

![](https://velog.velcdn.com/images/rowehnn/post/13602411-4fe3-44b7-a7b1-874e8d382d51/image.png)


- 여러 개의 동전 중에서 하나의 가짜 동전을 찾는 문제.
- 이분 탐색을 활용하여 무게가 적은 그룹을 찾아내는 방법.

## 6. Find a Poisoned Drink!

![](https://velog.velcdn.com/images/rowehnn/post/411bb8ad-cda7-4e39-b7de-152fcad86d15/image.png)

- 여러 병 중에서 독이 든 음료를 찾는 문제.
- 이분 탐색을 활용하여 미리 정한 양의 음료를 마셔보는 방법.

## recap

이번 시간에는 다양한 알고리즘과 그에 따른 문제 해결 전략들을 살펴봤다.
내용을 간단히 요약하자면

1. 알고리즘은 문제 해결의 과정을 체계적으로 접근하고 해결하기 위한 도구로 활용되며, 다양한 상황에 따라 적절한 알고리즘을 선택하는 능력이 필요하다.


2. 이러한 알고리즘들은 특정 유형의 문제를 해결하기 위한 템플릿으로 볼 수 있다. 그러나 어떤 문제에 어떤 알고리즘을 적용해야 하는지를 판단하는 것이 핵심이다.

3. 알고리즘을 공부하는 것은 누군가가 미리 정의한 템플릿을 사용하여 문제를 해결하는 것뿐만 아니라, 주어진 특정 문제에 어떤 템플릿을 적용해야 하는지를 잘 이해하는 것이 중요하다.


4. 앞으로의 강의에서는 아무것도 모르는 상태에서 문제를 해결하는 기법들을 배울거다.

5. 알고리즘에서 우리가 해결하려는 건 문제의 제약조건을 X라는 Input이 들어온 상태에서 Output Y 를 골라주는 프로그램 F를 만드는 것이다.

6. 결과적으로, 정확한 F를 찾는 것과 효율적인 F를 찾는 것이 중요하다.



## tl dr

>- 알고리즘 문제 해결에 있어서 핵심은 문제를 정확하게 이해하고, 목표한 대상을 찾는 것.
- 시간 복잡도와 공간 복잡도를 고려하여 효율적인 알고리즘을 선택해야 함.
- 문제를 해결할 때 sequential search를 시작으로 케이스 스터디를 통해 일반화할 수 있는 알고리즘을 개발하는 것이 중요.








