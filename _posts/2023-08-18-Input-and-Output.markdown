---
title: Input and Output
author: "Woojin JEON"
categories: Algorithm
tags: [Algorithm]
---

### 01. 문제

[문제 확인하기](https://www.hackerrank.com/challenges/cpp-input-and-output/problem?isFullScreen=true&h_r=next-challenge&h_v=zen){:target="_blank" rel="noopener noreferrer"}

### 02. 정답 코드 (C++11)

```Python
#include <cmath>
#include <cstdio>
#include <vector>
#include <iostream>
#include <algorithm>
using namespace std;


int main() {
    vector<int> numbers;
    int num;
    
    while (cin >> num) {
        numbers.push_back(num);
    }
    
    int sum;
    for (int i = 0; i < numbers.size(); i++) {
        sum += numbers[i];
    }
    
    cout << sum;
    
    return 0;
}
```
