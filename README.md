# ad-bs-date-conversion

## - Overview

The aim of this package is to convert AD date to BS date and vice versa . Since there is no standard logic for nepali calendar, we have to store nepali calender for this operation. So,This package can convert date from 1970-01-01 BS to 2099-12-30 BS for BSToAD and its equivalent AD date for ADToBS conversion .

## - Getting Started

### 1) Install

```bash
npm install --save ad-bs-date-conversion
```

### 2) Usage

```js
import { ADToBS, BSToAD, findLastDayOfMonthOfAdDate, findLastDayOfMonthOfBsDate } from "ad-bs-date-conversion";

console.log(ADToBS("2021-04-13")); // Prints 2077-12-31
console.log(BSToAD("2077-12-31")); // Prints 2021-04-13
console.log(ADToBS("2021/04/13")); // Prints 2077-12-31
console.log(BSToAD("2077/12/31")); // Prints 2021-04-13
console.log(findLastDayOfMonthOfAdDate(2021, 7)); //Prints 31
console.log(findLastDayOfMonthOfBsDate(2078, 4)); //Prints 32
```
