---
title: Day of the week
id: 5966f99c45e8976909a85575
challengeType: 5
videoUrl: ''
localeTitle: День недели
---

## Description
<section id="description"><p> Компания решает, что всякий раз, когда Xmas падает на воскресенье, они отдают своим работникам все дополнительные оплачиваемые отпуска, так что вместе с любыми праздничными днями работникам не придется работать на следующей неделе (с 25 декабря по 1 января). </p><p> Задача: </p><p> Напишите функцию, которая запускает год начала и конец года и возвращает массив всех лет, в которые 25 декабря будет воскресенье. </p></section>

## Instructions
<section id="instructions">
</section>

## Tests
<section id='tests'>

```yml
tests:
  - text: <code>findXmasSunday</code> - это функция.
    testString: 'assert(typeof findXmasSunday === "function", "<code>findXmasSunday</code> is a function.");'
  - text: '<code>findChristmasSunday(2000, 2100)</code> должен возвращать массив.'
    testString: 'assert(typeof findXmasSunday(2000, 2100) === "object", "<code>findChristmasSunday(2000, 2100)</code> should return an array.");'
  - text: '<code>findChristmasSunday(2008, 2121</code> должен вернуться [1977, 1983, 1988, 1994, 2005, 2011, 2016]'
    testString: 'assert.deepEqual(findXmasSunday(1970, 2017), firstSolution, "<code>findChristmasSunday(2008, 2121</code> should return [1977, 1983, 1988, 1994, 2005, 2011, 2016]");'
  - text: '<code>findChristmasSunday(2008, 2121</code> должны вернуться [2011, 2016, 2022, 2033, 2039, 2044, 2050, 2061, 2067, 2072, 2078, 2089, 2095, 2101, 2107, 2112, 2118]'
    testString: 'assert.deepEqual(findXmasSunday(2008, 2121), secondSolution, "<code>findChristmasSunday(2008, 2121</code> should return [2011, 2016, 2022, 2033, 2039, 2044, 2050, 2061, 2067, 2072, 2078, 2089, 2095, 2101, 2107, 2112, 2118]");'

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='js-seed'>

```js
function findXmasSunday (start, end) {
  // Good luck!
  return true;
}

```

</div>


### After Test
<div id='js-teardown'>

```js
console.info('after the test');
```

</div>

</section>

## Solution
<section id='solution'>

```js
// solution required
```
</section>
