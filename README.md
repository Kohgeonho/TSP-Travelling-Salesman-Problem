# TSP-Travelling-Salesman-Problem

## Introduction

TSP(Traveling Salesman Problem, 외판원 순회) 문제는 전산학의 아주 고전적이고 유명한 문제 중 하나이다. 이 문제는 NP-Hard로, 다항 이하의 시간복잡도 및 공간복잡도를 갖는 풀이는 현재까지는 존재하지 않는다. 이 때문에 최적의 해가 아닌 적당히 괜찮은 해를 구하는 heuristic 알고리즘이 많이 연구되기도 하였다. 여기서는 최적의 해를 보장하는 완전 탐색과 Dynamic Programming 알고리즘, 그리고 대표적인 heuristic 알고리즘 중 하나인 Genetic Algorithm을 이용하여 문제를 풀고, 문제의 크기에 따른 알고리즘들의 시간과 정확도를 비교할 것이다.

TSP(Traveling Salesman Problem) is one of the most popular and traditional problem in Computer Science. TSP is known as NP-Hard, which means that solution with time-complexity and spacial-complexity below polynomial does not exist so far. As a result, various kinds of heuristic algorithm was suggested to obtain "good enough" solution for TSP. Complete Search Algorithm and Dynamic Programming, which guarantee the optimal solution, and Genetic Algorithm, one of the most well-known heuristic algorithm will be suggested to solve the problem, and their estimated time and accuracy will be evaluated as following.

## Problems

<img src="https://d2gd6pc034wcta.cloudfront.net/tier/15.svg" width="13pt"> [BaekJoon 2098 Traveling Salesman Problem](https://www.acmicpc.net/problem/2098)

이 문제는 2차원 격자위의 점들을 순회하는 일반적인 TSP와는 다르게 다음과 같은 특징을 가진다. 

- asymmetric
- non-euclidean

이에 따라 많은 heuristic algorithm(KNN, Genetic Algorithm) 등을 적용할 수 없다.

## Algorithms

### [Complete Search Algorithm](https://en.wikipedia.org/wiki/Travelling_salesman_problem#:~:text=Exact%20algorithms%5Bedit%5D)

### [Dynamic Programming](https://shoark7.github.io/programming/algorithm/solve-tsp-with-dynamic-programming)

### 
