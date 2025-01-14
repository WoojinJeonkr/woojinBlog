---
layout: post
title: Prettier and ESLint
subtitle: Pritter와 ESLint 사용하기
categories: React
tags: [React, Pritter, ESLint]
---

## 01. Prettier

- 파일을 저장할때마다, 코드를 사용자가 원하는 형식으로 만들어주는 Node.js 패키지
- VSCode Extension을 통하거나 npm을 통해 설치 가능

```console
npm i -D prettier
```

## 02. ESLint

- 자바스크립트 문법에서 에러를 표시해주는 도구
- VSCode Extension을 통하거나 npm을 통해 설치 가능

```console
npm install -D eslint
```

## 03. Prettier와 ESLint 함께 사용하기

### 03-1.  터미널에 커맨드로 입력하는 방법

1. 자바스크립트 프로젝트에 prettier npm 패키지를 개발 의존성으로 설치

```console
npm i -D prettier
```

2. ESLint와 통합을 위해 2개의 npm 패키지 추가 설치

```console
npm i -D eslint-config-prettier eslint-plugin-prettier
```

3. ESLint 설정 파일(.eslintrc.js, .eslintrc.json)에 설정 추가하기

```js
{
    "extends": ["plugin:prettier/recommended"]
}
```

- 참고로 eslint에서는 우선 설정하고자 하는 설정을 배열 내 맨 뒤에 작성해야 한다.

### 03-2. 확장 프로그램 이용하기

[VSCode Prettier 플러그인](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

## 04. Reference

- [prettier](https://prettier.io/)
- [eslint](https://eslint.org/)