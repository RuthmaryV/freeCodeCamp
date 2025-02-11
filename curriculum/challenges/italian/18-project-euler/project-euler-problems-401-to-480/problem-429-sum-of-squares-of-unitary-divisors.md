---
id: 5900f5191000cf542c51002c
title: 'Problema 429: somma dei quadrati di divisori unitari'
challengeType: 1
forumTopicId: 302099
dashedName: problem-429-sum-of-squares-of-unitary-divisors
---

# --description--

Un divisore unitario $d$ di un numero $n$ è un divisore di $n$ che ha la proprietà $MCD(d, \frac{n}{d}) = 1$.

The unitary divisors of $4! = 24$ are 1, 3, 8 and 24.

La somma dei loro quadrati è $12 + 32 + 82 + 242 = 650$.

Sia $S(n)$ la rappresentazione della somma dei quadrati dei divisori unitari di $n$. Thus $S(4!) = 650$.

Trova $S(100\\,000\\,000!)$ modulo $1\\,000\\,000\\,009$.

# --hints--

`sumSquaresOfUnitaryDivisors()` dovrebbe restituire `98792821`.

```js
assert.strictEqual(sumSquaresOfUnitaryDivisors(), 98792821);
```

# --seed--

## --seed-contents--

```js
function sumSquaresOfUnitaryDivisors() {

  return true;
}

sumSquaresOfUnitaryDivisors();
```

# --solutions--

```js
// solution required
```
