---
title: Amicable pairs
id: 5949b579404977fbaefcd737
challengeType: 5
videoUrl: ''
localeTitle: Parejas amistosas
---

## Description
<section id="description"> Se dice que dos enteros $ N $ y $ M $ son <a href="https://en.wikipedia.org/wiki/Amicable numbers" title="wp: números amistosos">pares amigables</a> si $ N \ neq M $ y la suma de los <a href="http://rosettacode.org/wiki/Proper divisors" title="Divisores adecuados">divisores apropiados</a> de $ N $ ($ \ mathrm {suma} (\ mathrm {propDivs} (N)) $) $ = M $, así como $ \ mathrm {suma} (\ mathrm {propDivs} (M)) = N $. Ejemplo: 1184 y 1210 son una pareja amigable, con divisores apropiados: 1, 2, 4, 8, 16, 32, 37, 74, 148, 296, 592 y 1, 2, 5, 10, 11, 22, 55, 110, 121, 242, 605 respectivamente. Tarea: Calcula y muestra aquí los pares de amigos por debajo de 20,000 (hay ocho). Tareas relacionadas Divisores <a href="http://rosettacode.org/wiki/Proper divisors" title="Divisores adecuados">apropiados</a> <a href="http://rosettacode.org/wiki/Abundant, deficient and perfect number classifications" title="Numerosas, deficientes y perfectas clasificaciones numéricas.">Clasificaciones numéricas abundantes, deficientes y perfectas Clasificaciones de</a> <a href="http://rosettacode.org/wiki/Aliquot sequence classifications" title="Clasificaciones de secuencias alícuotas">secuencias alícuotas</a> y su clasificación amistosa. </section>

## Instructions
<section id="instructions">
</section>

## Tests
<section id='tests'>

```yml
tests:
  - text: <code>amicablePairsUpTo</code> es una función.
    testString: 'assert(typeof amicablePairsUpTo === "function", "<code>amicablePairsUpTo</code> is a function.");'
  - text: '<code>amicablePairsUpTo(300)</code> debe devolver <code>[[220,284]]</code> .'
    testString: 'assert.deepEqual(amicablePairsUpTo(300), answer300, "<code>amicablePairsUpTo(300)</code> should return <code>[[220,284]]</code>.");'
  - text: '<code>amicablePairsUpTo(3000)</code> debe devolver <code>[[220,284],[1184,1210],[2620,2924]]</code> .'
    testString: 'assert.deepEqual(amicablePairsUpTo(3000), answer3000, "<code>amicablePairsUpTo(3000)</code> should return <code>[[220,284],[1184,1210],[2620,2924]]</code>.");'
  - text: '<code>amicablePairsUpTo(20000)</code> debe devolver <code>[[220,284],[1184,1210],[2620,2924],[5020,5564],[6232,6368],[10744,10856],[12285,14595],[17296,18416]]</code> .'
    testString: 'assert.deepEqual(amicablePairsUpTo(20000), answer20000, "<code>amicablePairsUpTo(20000)</code> should return <code>[[220,284],[1184,1210],[2620,2924],[5020,5564],[6232,6368],[10744,10856],[12285,14595],[17296,18416]]</code>.");'

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='js-seed'>

```js
function amicablePairsUpTo (maxNum) {
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
