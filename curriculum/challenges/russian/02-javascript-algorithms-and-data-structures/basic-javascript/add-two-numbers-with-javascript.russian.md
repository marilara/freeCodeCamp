---
id: cf1111c1c11feddfaeb3bdef
title: Add Two Numbers with JavaScript
challengeType: 1
videoUrl: https://scrimba.com/c/cM2KBAG
forumTopicId: 16650
localeTitle: Сложить два числа с JavaScript
---

## Description
<section id='description'>
<code>Number</code> - это тип данных в JavaScript, который представляет числовые данные. Теперь попробуем добавить два числа, используя JavaScript. JavaScript использует символ <code>+</code> в качестве операции сложения при размещении между двумя числами. <strong>пример</strong> <blockquote> myVar = 5 + 10; // присвоено 15 </blockquote>
</section>

## Instructions
<section id='instructions'>
Измените <code>0</code> так, чтобы сумма равнялась <code>20</code> .
</section>

## Tests
<section id='tests'>

```yml
tests:
  - text: <code>sum</code> should equal <code>20</code>
    testString: assert(sum === 20);
  - text: Use the <code>+</code> operator
    testString: assert(/\+/.test(code));

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='js-seed'>

```js
var sum = 10 + 0;

```

</div>

### After Tests
<div id='js-teardown'>

```js
(function(z){return 'sum = '+z;})(sum);

```

</div>

</section>

## Solution
<section id='solution'>

```js
var sum = 10 + 10;
```

</section>
