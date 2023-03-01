<!--

@license Apache-2.0

Copyright (c) 2022 The Stdlib Authors.

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

# log

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Output a message to the debugger console.

<!-- Section to include introductory text. Make sure to keep an empty line after the intro `section` element and another before the `/section` close. -->

<section class="intro">

</section>

<!-- /.intro -->

<!-- Package usage documentation. -->



<section class="usage">

## Usage

To use in Observable,

```javascript
log = require( 'https://cdn.jsdelivr.net/gh/stdlib-js/console-log@umd/browser.js' )
```

To vendor stdlib functionality and avoid installing dependency trees for Node.js, you can use the UMD server build:

```javascript
var log = require( 'path/to/vendor/umd/console-log/index.js' )
```

To include the bundle in a webpage,

```html
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/stdlib-js/console-log@umd/browser.js"></script>
```

If no recognized module system is present, access bundle contents via the global scope:

```html
<script type="text/javascript">
(function () {
    window.log;
})();
</script>
```

#### log( \[data]\[,..args] )

Outputs a message to the debugger console.

```javascript
log( 'Hello, World!' );
```

If the first argument is a string, the argument is the primary message and may include zero or more substitution strings.

```javascript
log( 'Hello, %s!', 'World' );
```

</section>

<!-- /.usage -->

<!-- Package usage notes. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="notes">

## Notes

-   In general, prefer formatting with [`@stdlib/string-format`][@stdlib/string/format], as string substitution support is not consistent across JavaScript environments.

    ```javascript
    var format = require( '@stdlib/string-format' );

    log( format( '%s: %.2f', 'Foo', 3.14 ) );
    ```

</section>

<!-- /.notes -->

<!-- Package usage examples. -->

<section class="examples">

## Examples

<!-- eslint-disable object-curly-newline -->

<!-- eslint no-undef: "error" -->

```html
<!DOCTYPE html>
<html lang="en">
<body>
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/stdlib-js/console-log@umd/browser.js"></script>
<script type="text/javascript">
(function () {

log( 'Hello, World!' );
log( 'Hello, %s!', 'World' );
log( '%d', 1 );
log( '%.2d', 1.1 );
log( '%i', 2 );
log( '%.2i', 2.2 );
log( '%f', 3.14 );
log( '%.2f', 4.13 );
log( '%o', { 'foo': 'bar' } );
log( '%O', [ 1, 2, 3, 4 ] );

})();
</script>
</body>
</html>
```

</section>

<!-- /.examples -->

<!-- Section to include cited references. If references are included, add a horizontal rule *before* the section. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="references">

</section>

<!-- /.references -->

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

[npm-image]: http://img.shields.io/npm/v/@stdlib/console-log.svg
[npm-url]: https://npmjs.org/package/@stdlib/console-log

[test-image]: https://github.com/stdlib-js/console-log/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/stdlib-js/console-log/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/console-log/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/console-log?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/console-log.svg
[dependencies-url]: https://david-dm.org/stdlib-js/console-log/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://gitter.im/stdlib-js/stdlib/

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/console-log/tree/deno
[umd-url]: https://github.com/stdlib-js/console-log/tree/umd
[esm-url]: https://github.com/stdlib-js/console-log/tree/esm
[branches-url]: https://github.com/stdlib-js/console-log/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/console-log/main/LICENSE

[@stdlib/string/format]: https://github.com/stdlib-js/stdlib/tree/umd

</section>

<!-- /.links -->
