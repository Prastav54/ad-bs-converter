# ad-bs-date-converter

## - Overview

The aim of this package is to convert AD date to BS date and vice versa . Since there is no standard logic for nepali calendar, we have to store nepali calender for this operation. So,This package can convert date from 1970-01-01 BS to 2099-12-30 BS for BSToAD and its equivalent AD date for ADToBS conversion .

## - Getting Started

### 1) Install

```bash
$ npm install --save ad-bs-date-converter
```

### 2) Usage

```js
import { ADToBS, BSToAD } from "ad-bs-date-converter";

console.log(ADToBS("2021-04-13")); // Prints 2077-12-31
console.log(BSToAD("2077-12-31")); // Prints 2021-04-13
console.log(ADToBS("2021/04/13")); // Prints 2077-12-31
console.log(BSToAD("2077/12/31")); // Prints 2021-04-13
```
