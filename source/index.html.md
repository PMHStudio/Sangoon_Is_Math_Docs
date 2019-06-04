---
title: Sangoon Is Math Docs

language_tabs: # must be one of https://git.io/vQNgJ
  - javascript

toc_footers:
  - <a href='https://www.npmjs.com/package/sangoon_is_math'>npm 모듈 페이지</a>
  - <a href='https://github.com/ttakkku/Sangoon_Is_Math'>GitHub 저장소</a>
  - <a href='https://github.com/lord/slate'>Documentation Powered by Slate</a>

search: true
---

# Introduction

sangoon_is_math 모듈은 여러분들의 수학적 귀차니즘을 해결해 주는 모듈입니다!

더하기, 빼기 등을 포함한 기본 연산부터 원주계산, 거듭제곱, 루트까지 간단한 문법으로 가능합니다!

# Installation

> 터미널에서

```
npm i sangoon_is_math
```

> 혹은

```
yarn add sangoon_is_math
```

> 를 입력해 설치합니다


이 모듈을 사용하기 전에 설치 과정을 거처야 합니다

모듈의 설치 방법은 주로 **[npm](https://www.npmjs.com/package/sangoon_is_math)**를 사용하거나 **[yarn](https://yarnpkg.com/lang/en/docs/install/#debian-stable)**을 사용하면 됩니다


<aside class="notice">
개인적으로 yarn을 추천합니다, 왜냐구요? 빠르거든요!
</aside>

# Demo

```javascript
const sangoonIsMath = require('sangoon_is_math')
```
> 를 사용하여 모듈을 불러올 수 있습니다

이 모듈의 모든 함수들을 모아 놓았습니다

이 문서에 의문점이나, 틀린점, 오타 등이 있다면 이 문서의 [이슈](https://github.com/PMHStudio/Sangoon_Is_Math_Docs/issues/new) 에 올려주시기 바랍니다

## .plus(a, b)

> plus(더하기) 함수는 다음과 같이 사용합니다

```javascript
const sangoonIsMath = require('sangoon_is_math')

console.log(sangoonIsMath.plus(10, 30)) // 출력: 40
```

> 혹은 문자열도 a, b에 사용 가능합니다

```javascript
const sangoonIsMath = require('sangoon_is_math')

console.log(sangoonIsMath.plus('This is ', 'plus function')) // 출력: This is plus function
```
`.plus(a, b)` 함수는 인자값 a와 b를 합한 값을 반환합니다


인자 이름 | 자료형             | 설명
----------|--------------------|-------------
a         | Number 혹은 String | 더해질 값
b         | Number 혹은 String | 더하는 값

반환: Number 혹은 String

## .Minus(a, b)

> Minus(빼기) 함수는 다음과 같이 사용합니다

```javascript
const sangoonIsMath = require('sangoon_is_math')

console.log(sangoonIsMath.minus(50, 10)) // 출력: 40
```


> 혹은 문자열도 a, b에 사용 가능합니다

```javascript
const sangoonIsMath = require('sangoon_is_math')

console.log(sangoonIsMath.Minus('This is minus function, bro', ', bro')) // 출력: This is minus function
```

`.minus(a, b)` 함수는 인자값 a와 b를 뺀 값을 반환합니다


인자 이름 | 자료형 | 설명
----------|--------|--------
a         | Number | 빼질 값
b         | Number | 빼는 값

반환: Number 혹은 String

## .multiply(a, b)

> multiply(곱셈) 함수는 다음과 같이 사용합니다

```javascript
const sangoonIsMath = require('sangoon_is_math')

console.log(sangoonIsMath.multiply(10, 10)) // 출력: 100
```

`.multiply(a, b)` 함수는 인자값 a의 b배 한 값을 반환합니다


인자 이름 | 자료형 | 설명
----------|--------|-------------
a         | Number | 곱해질 값
b         | Number | 곱하는 값

반환: Number

## .division(a, b)

> division(나눗셈) 함수는 다음과 같이 사용합니다

```javascript
const sangoonIsMath = require('sangoon_is_math')

console.log(sangoonIsMath.division(10, 5)) // 출력: 2
```


`.division(a, b)` 함수는 인자값 a에 b를 나눈 값을 반환합니다


인자 이름 | 자료형 | 설명
----------|--------|-------------
a         | Number | 나눠질 값
b         | Number | 나누는 값

반환: Number

## .caret(a, b)

> caret(제곱) 함수는 다음과 같이 사용합니다

```javascript
const sangoonIsMath = require('sangoon_is_math')

console.log(sangoonIsMath.caret(2, 5)) // 출력: 7
```

<aside class="warning">.pow()와 같은 기능을 함으로서 곧 없어질 예정입니다</aside>

`.multiply(a, b)` 함수는 인자값 a의 b 제곱 한 값을 반환합니다


인자 이름 | 자료형 | 설명
----------|--------|----------
a         | Number | 밑
b         | Number | 지수

반환: Number

## .plueandminus(a, b)

> plueandminus (더한후 빼기) 함수는 다음과 같이 사용합니다

```javascript
const sangoonIsMath = require('sangoon_is_math')

console.log(sangoonIsMath.plueandminus(10, 5)) // 출력: 10
```

<aside class="warning">결과는 무조건 a으로서 곧 없어질 예정입니다</aside>

## .minusandplue(a, b)

> minusandplue(뺀후 더하기) 함수는 다음과 같이 사용합니다

```javascript
const sangoonIsMath = require('sangoon_is_math')

console.log(sangoonIsMath.minusandplue(10, 5)) // 출력: 10
```

<aside class="warning">결과는 무조건 a으로서 곧 없어질 예정입니다</aside>

## .pow(a, b)

> pow(거듭제곱) 함수는 다음과 같이 사용합니다

```javascript
const sangoonIsMath = require('sangoon_is_math')

console.log(sangoonIsMath.pow(2, 5)) // 출력: 32
```

`.pow(a, b)` 함수는 인자값 a의 b 제곱 한 값을 반환합니다


인자 이름 | 자료형 | 설명
----------|--------|----------
a         | Number | 밑
b         | Number | 지수

반환: Number

## .sqrt(a, b)

> sqrt(루트) 함수는 다음과 같이 사용합니다

```javascript
const sangoonIsMath = require('sangoon_is_math')

console.log(sangoonIsMath.sqrt(2, 5)) // 출력: 1.4142135623730951
```

`.sqrt(a)` 함수는 인자값 a에 (√)를 씌운 값, 제곱근을 반환합니다


인자 이름 | 자료형 | 설명
----------|--------|----------
a         | Number | 루트(√)를 씌울 값

반환: Number

## .random(a, b)

> ramdom(랜덤) 함수는 다음과 같이 사용합니다

```javascript
const sangoonIsMath = require('sangoon_is_math')

console.log(sangoonIsMath.random(1, 5)) // 출력: 1~5
```

`.random(a, b)` 함수는 인자값 a와 b의 사이(a, b를 포함)의 난수 값을 반환합니다


인자 이름 | 자료형 | 설명
----------|--------|----------
a         | Number | 난수의 최소값
b         | Number | 난수의 최대값

반환: Number

## .primenumbers(a, b)

> primenumbers(소수(素數)) 함수는 다음과 같이 사용합니다

```javascript
const sangoonIsMath = require('sangoon_is_math')

console.log(sangoonIsMath.primenumbers(1, 5)) // 출력: 1, 2, 3, 5
```

`.primenumbers(a, b)` 함수는 인자값 a부터 b까지의 소수들의 배열을 반환합니다


인자 이름 | 자료형 | 설명
----------|--------|----------
a         | Number | 소수 검색의 최소값
b         | Number | 소수 검색의 최대값

반환: Number로 이루워진 배열

## .pi2(a)

> pi2(반지름) 함수는 다음과 같이 사용합니다

```javascript
const sangoonIsMath = require('sangoon_is_math')

console.log(sangoonIsMath.pi2(5)) // 출력: 31.41592653589793
```

`.pi2(a)` 함수는 인자값 a의 반지름을 가진 원의 원주를 반환합니다


인자 이름 | 자료형 | 설명
----------|--------|----------
a         | Number | 원의 반지름

반환: Number

## .round(a)

> round(소수(小數)) 함수는 다음과 같이 사용합니다

```javascript
const sangoonIsMath = require('sangoon_is_math')

console.log(sangoonIsMath.round(2.9)) // 출력: 3
```

`.round(a)` 함수는 인자값 a를 반올림하여 정수로 변환한 값을 반환합니다


인자 이름 | 자료형 | 설명
----------|--------|----------
a         | Number | 반올림할 소수

반환: Number

## .official

> official(공식) 상수는 다음과 같습니다

```javascript
const sangoonIsMath = require('sangoon_is_math')

console.log(sangoonIsMath.official) // 출력: { discord: 'https://discord.gg/KNBGZU2', github: 'https://github.com/ttakkku/Sangoon_Is_Math' }
```

이 모듈과 관련된 공식 사이트들입니다

* official
  * discord: '[https://discord.gg/KNBGZU2](https://discord.gg/KNBGZU2)'
  * github: '[https://github.com/ttakkku/Sangoon_Is_Math](https://github.com/ttakkku/Sangoon_Is_Math)'

## .discord

> discord(디스코드) 상수는 다음과 같습니다

```javascript
const sangoonIsMath = require('sangoon_is_math')

console.log(sangoonIsMath.discord) // 출력: { tag: 'CY8ER#5278', love: 'Discord Love~' }
```

이 모듈과 관련된 디스코드 정보입니다

* discord
  * tag: 'CY8ER#5278'
  * love: 'Discord Love~'
