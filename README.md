<!--

@license Apache-2.0

Copyright (c) 2023 The Stdlib Authors.

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

# invcase

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Convert a string to inverse case.

<!-- Package usage documentation. -->

<section class="installation">

## Installation

```bash
npm install @stdlib/string-base-invcase
```

Alternatively,

-   To load the package in a website via a `script` tag without installation and bundlers, use the [ES Module][es-module] available on the [`esm` branch][esm-url].
-   If you are using Deno, visit the [`deno` branch][deno-url].
-   For use in Observable, or in browser/node environments, use the [Universal Module Definition (UMD)][umd] build available on the [`umd` branch][umd-url].

The [branches.md][branches-url] file summarizes the available branches and displays a diagram illustrating their relationships.

</section>

<section class="usage">

## Usage

```javascript
var invcase = require( '@stdlib/string-base-invcase' );
```

#### invcase( str )

Converts a string to inverse case.

```javascript
var str = invcase( 'foo bar' );
// returns 'FOO BAR'

str = invcase( 'Foo Bar Baz' );
// returns 'fOO bAR bAZ'

str = invcase( 'foo BAR' );
// returns 'FOO bar'
```

</section>

<!-- /.usage -->

<!-- Package usage examples. -->

<section class="examples">

## Examples

```javascript
var invcase = require( '@stdlib/string-base-invcase' );

var str = 'Hello World!';
var out = invcase( str );
// returns 'hELLO wORLD!'

str = 'I am a tiny little teapot';
out = invcase( str );
// returns 'i AM A TINY LITTLE TEAPOT'

str = 'with BIG problems';
out = invcase( str );
// returns 'WITH big PROBLEMS'

str = 'To Be, Or NoT To Be: ThAt Is ThE QuEsTiOn.';
out = invcase( str );
// returns 'tO bE, oR nOt tO bE: tHaT iS tHe qUeStIoN.'

str = 'isMobile';
out = invcase( str );
// returns 'ISmOBILE'
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

This package is part of [stdlib][stdlib], a standard library for JavaScript and Node.js, with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2023. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/string-base-invcase.svg
[npm-url]: https://npmjs.org/package/@stdlib/string-base-invcase

[test-image]: https://github.com/stdlib-js/string-base-invcase/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/stdlib-js/string-base-invcase/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/string-base-invcase/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/string-base-invcase?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/string-base-invcase.svg
[dependencies-url]: https://david-dm.org/stdlib-js/string-base-invcase/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://app.gitter.im/#/room/#stdlib-js_stdlib:gitter.im

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/string-base-invcase/tree/deno
[umd-url]: https://github.com/stdlib-js/string-base-invcase/tree/umd
[esm-url]: https://github.com/stdlib-js/string-base-invcase/tree/esm
[branches-url]: https://github.com/stdlib-js/string-base-invcase/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/string-base-invcase/main/LICENSE

</section>

<!-- /.links -->
