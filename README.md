<!--

@license Apache-2.0

Copyright (c) 2018 The Stdlib Authors.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

-->


<details>
  <summary>
    About stdlib...
  </summary>
  <p>We believe in a future in which the web is a preferred environment for numerical computation. To help realize this future, we've built stdlib. stdlib is a standard library, with an emphasis on numerical and scientific computation, written in JavaScript (and C) for execution in browsers and in Node.js.</p>
  <p>The library is fully decomposable, being architected in such a way that you can swap out and mix and match APIs and functionality to cater to your exact preferences and use cases.</p>
  <p>When you use stdlib, you can be absolutely certain that you are using the most thorough, rigorous, well-written, studied, documented, tested, measured, and high-quality code out there.</p>
  <p>To join us in bringing numerical computing to the web, get started by checking us out on <a href="https://github.com/stdlib-js/stdlib">GitHub</a>, and please consider <a href="https://opencollective.com/stdlib">financially supporting stdlib</a>. We greatly appreciate your continued support!</p>
</details>

# Chi-squared

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Chi-squared distribution.



<section class="usage">

## Usage

```javascript
import chisquare from 'https://cdn.jsdelivr.net/gh/stdlib-js/stats-base-dists-chisquare@esm/index.mjs';
```
The previous example will load the latest bundled code from the esm branch. Alternatively, you may load a specific version by loading the file from one of the [tagged bundles](https://github.com/stdlib-js/stats-base-dists-chisquare/tags). For example,

```javascript
import chisquare from 'https://cdn.jsdelivr.net/gh/stdlib-js/stats-base-dists-chisquare@v0.3.0-esm/index.mjs';
```

You can also import the following named exports from the package:

```javascript
import { ChiSquare, cdf, entropy, kurtosis, logpdf, mean, median, mgf, mode, pdf, quantile, skewness, stdev, variance } from 'https://cdn.jsdelivr.net/gh/stdlib-js/stats-base-dists-chisquare@esm/index.mjs';
```

#### chisquare

Chi-squared distribution.

```javascript
var dist = chisquare;
// returns {...}
```

The namespace contains the following distribution functions:

<!-- <toc pattern="*+(cdf|pdf|mgf|quantile)*"> -->

<div class="namespace-toc">

-   <span class="signature">[`cdf( x, k )`][@stdlib/stats/base/dists/chisquare/cdf]</span><span class="delimiter">: </span><span class="description">Chi-squared distribution cumulative distribution function.</span>
-   <span class="signature">[`logpdf( x, k )`][@stdlib/stats/base/dists/chisquare/logpdf]</span><span class="delimiter">: </span><span class="description">evaluate the natural logarithm of the probability density function (PDF) for a chi-squared distribution.</span>
-   <span class="signature">[`mgf( t, k )`][@stdlib/stats/base/dists/chisquare/mgf]</span><span class="delimiter">: </span><span class="description">Chi-squared distribution moment-generating function (MGF).</span>
-   <span class="signature">[`pdf( x, k )`][@stdlib/stats/base/dists/chisquare/pdf]</span><span class="delimiter">: </span><span class="description">Chi-squared distribution probability density function (PDF).</span>
-   <span class="signature">[`quantile( p, k )`][@stdlib/stats/base/dists/chisquare/quantile]</span><span class="delimiter">: </span><span class="description">Chi-squared distribution quantile function.</span>

</div>

<!-- </toc> -->

The namespace contains the following functions for calculating distribution properties:

<!-- <toc pattern="*+(entropy|kurtosis|mean|median|mode|skewness|stdev|variance)*"> -->

<div class="namespace-toc">

-   <span class="signature">[`entropy( k )`][@stdlib/stats/base/dists/chisquare/entropy]</span><span class="delimiter">: </span><span class="description">Chi-squared distribution differential entropy.</span>
-   <span class="signature">[`kurtosis( k )`][@stdlib/stats/base/dists/chisquare/kurtosis]</span><span class="delimiter">: </span><span class="description">Chi-squared distribution excess kurtosis.</span>
-   <span class="signature">[`mean( k )`][@stdlib/stats/base/dists/chisquare/mean]</span><span class="delimiter">: </span><span class="description">Chi-squared distribution expected value.</span>
-   <span class="signature">[`median( k )`][@stdlib/stats/base/dists/chisquare/median]</span><span class="delimiter">: </span><span class="description">Chi-squared distribution median.</span>
-   <span class="signature">[`mode( k )`][@stdlib/stats/base/dists/chisquare/mode]</span><span class="delimiter">: </span><span class="description">Chi-squared distribution mode.</span>
-   <span class="signature">[`skewness( k )`][@stdlib/stats/base/dists/chisquare/skewness]</span><span class="delimiter">: </span><span class="description">Chi-squared distribution skewness.</span>
-   <span class="signature">[`stdev( k )`][@stdlib/stats/base/dists/chisquare/stdev]</span><span class="delimiter">: </span><span class="description">Chi-squared distribution standard deviation.</span>
-   <span class="signature">[`variance( k )`][@stdlib/stats/base/dists/chisquare/variance]</span><span class="delimiter">: </span><span class="description">Chi-squared distribution variance.</span>

</div>

<!-- </toc> -->

The namespace contains a constructor function for creating a [Chi-squared][chisquare-distribution] distribution object.

<!-- <toc pattern="*ctor*"> -->

<div class="namespace-toc">

-   <span class="signature">[`ChiSquare( [k] )`][@stdlib/stats/base/dists/chisquare/ctor]</span><span class="delimiter">: </span><span class="description">Chi-squared distribution constructor.</span>

</div>

<!-- </toc> -->

```javascript
var ChiSquare = require( 'https://cdn.jsdelivr.net/gh/stdlib-js/stats-base-dists-chisquare' ).ChiSquare;

var dist = new ChiSquare( 4.0 );

var mu = dist.mean;
// returns 4.0
```

</section>

<!-- /.usage -->

<section class="examples">

## Examples

<!-- TODO: better examples -->

<!-- eslint no-undef: "error" -->

```html
<!DOCTYPE html>
<html lang="en">
<body>
<script type="module">

import roundn from 'https://cdn.jsdelivr.net/gh/stdlib-js/math-base-special-roundn@esm/index.mjs';
import chisquare from 'https://cdn.jsdelivr.net/gh/stdlib-js/stats-base-dists-chisquare@esm/index.mjs';

// Define degrees of freedom:
var k = 5.0;

// Calculate distribution properties:
console.log( 'Mean: %d', chisquare.mean( k ) );
console.log( 'Median: %d', roundn( chisquare.median( k ), -4 ) );
console.log( 'Mode: %d', chisquare.mode( k ) );
console.log( 'Variance: %d', chisquare.variance( k ) );
console.log( 'Standard Deviation: %d', roundn( chisquare.stdev( k ), -4 ) );
console.log( 'Skewness: %d', roundn( chisquare.skewness( k ), -4 ) );
console.log( 'Excess Kurtosis: %d', roundn( chisquare.kurtosis( k ), -4 ) );
console.log( 'Entropy: %d', roundn( chisquare.entropy( k ), -4 ) );

// Evaluate probability functions:
var x = 3.0;
console.log( '\nEvaluating at x = %d', x );
console.log( 'PDF: %d', roundn( chisquare.pdf( x, k ), -4 ) );
console.log( 'logPDF: %d', roundn( chisquare.logpdf( x, k ), -4 ) );
console.log( 'CDF: %d', roundn( chisquare.cdf( x, k ), -4 ) );

// Calculate quantiles:
var p = 0.7;
console.log( '\nQuantile at p = %d: %d', p, roundn( chisquare.quantile( p, k ), -4 ) );

// Evaluate moment-generating function:
var t = 0.1;
console.log( 'MGF at t = %d: %d', t, roundn( chisquare.mgf( t, k ), -4 ) );

</script>
</body>
</html>
```

</section>

<!-- /.examples -->

<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

</section>

<!-- /.related -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2026. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/stats-base-dists-chisquare.svg
[npm-url]: https://npmjs.org/package/@stdlib/stats-base-dists-chisquare

[test-image]: https://github.com/stdlib-js/stats-base-dists-chisquare/actions/workflows/test.yml/badge.svg?branch=v0.3.0
[test-url]: https://github.com/stdlib-js/stats-base-dists-chisquare/actions/workflows/test.yml?query=branch:v0.3.0

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/stats-base-dists-chisquare/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/stats-base-dists-chisquare?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/stats-base-dists-chisquare.svg
[dependencies-url]: https://david-dm.org/stdlib-js/stats-base-dists-chisquare/main

-->

[chat-image]: https://img.shields.io/badge/zulip-join_chat-brightgreen.svg
[chat-url]: https://stdlib.zulipchat.com

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/stats-base-dists-chisquare/tree/deno
[deno-readme]: https://github.com/stdlib-js/stats-base-dists-chisquare/blob/deno/README.md
[umd-url]: https://github.com/stdlib-js/stats-base-dists-chisquare/tree/umd
[umd-readme]: https://github.com/stdlib-js/stats-base-dists-chisquare/blob/umd/README.md
[esm-url]: https://github.com/stdlib-js/stats-base-dists-chisquare/tree/esm
[esm-readme]: https://github.com/stdlib-js/stats-base-dists-chisquare/blob/esm/README.md
[branches-url]: https://github.com/stdlib-js/stats-base-dists-chisquare/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/stats-base-dists-chisquare/main/LICENSE

[chisquare-distribution]: https://en.wikipedia.org/wiki/Chi-squared_distribution

<!-- <toc-links> -->

[@stdlib/stats/base/dists/chisquare/ctor]: https://github.com/stdlib-js/stats-base-dists-chisquare-ctor/tree/esm

[@stdlib/stats/base/dists/chisquare/entropy]: https://github.com/stdlib-js/stats-base-dists-chisquare-entropy/tree/esm

[@stdlib/stats/base/dists/chisquare/kurtosis]: https://github.com/stdlib-js/stats-base-dists-chisquare-kurtosis/tree/esm

[@stdlib/stats/base/dists/chisquare/mean]: https://github.com/stdlib-js/stats-base-dists-chisquare-mean/tree/esm

[@stdlib/stats/base/dists/chisquare/median]: https://github.com/stdlib-js/stats-base-dists-chisquare-median/tree/esm

[@stdlib/stats/base/dists/chisquare/mode]: https://github.com/stdlib-js/stats-base-dists-chisquare-mode/tree/esm

[@stdlib/stats/base/dists/chisquare/skewness]: https://github.com/stdlib-js/stats-base-dists-chisquare-skewness/tree/esm

[@stdlib/stats/base/dists/chisquare/stdev]: https://github.com/stdlib-js/stats-base-dists-chisquare-stdev/tree/esm

[@stdlib/stats/base/dists/chisquare/variance]: https://github.com/stdlib-js/stats-base-dists-chisquare-variance/tree/esm

[@stdlib/stats/base/dists/chisquare/cdf]: https://github.com/stdlib-js/stats-base-dists-chisquare-cdf/tree/esm

[@stdlib/stats/base/dists/chisquare/logpdf]: https://github.com/stdlib-js/stats-base-dists-chisquare-logpdf/tree/esm

[@stdlib/stats/base/dists/chisquare/mgf]: https://github.com/stdlib-js/stats-base-dists-chisquare-mgf/tree/esm

[@stdlib/stats/base/dists/chisquare/pdf]: https://github.com/stdlib-js/stats-base-dists-chisquare-pdf/tree/esm

[@stdlib/stats/base/dists/chisquare/quantile]: https://github.com/stdlib-js/stats-base-dists-chisquare-quantile/tree/esm

<!-- </toc-links> -->

</section>

<!-- /.links -->
