---
title: African Cities
author: "Woojin JEON"
categories: SQL
tags: [SQL]
---

### 01. 문제

[문제 확인하기](https://www.hackerrank.com/challenges/african-cities/problem?isFullScreen=true){:target="_blank" rel="noopener noreferrer"}

### 02. 정답 코드

```sql
SELECT CITY.NAME FROM CITY, COUNTRY
WHERE CITY.COUNTRYCODE = COUNTRY.CODE AND COUNTRY.CONTINENT = "Africa";
```
