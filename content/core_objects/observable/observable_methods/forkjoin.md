# forkJoin

`Rx.Observable.forkJoin(...args)`
<a href="#rxobservableforkjoinargs">#</a> [&#x24C8;](https://github.com/Reactive-Extensions/RxJS/blob/master/tests/observable/forkjoin.js "View in source")

Runs all observable sequences in parallel and collect their last elements.

![forkJoin](https://github.com/Netflix/RxJava/wiki/images/rx-operators/forkJoin.png)

#### Arguments
1. `args` *(Arguments | Array)*: An array or arguments of Observable sequences or Promises to collect the last elements for.

#### Returns
*(`Observable`)*: An observable sequence with an array collecting the last elements of all the input sequences.

#### Example

[](http://jsbin.com/sudura/1/embed?js,console)

### Location

File:
- [`/src/core/observable/forkjoin.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/src/core/linq/observable/forkjoin.js)

Dist:
- [`rx.all.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.all.js)
- [`rx.all.compat.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.all.compat.js)
- [`rx.experimental.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.experimental.js)

Prerequisites:
- If using `rx.experimental.js` - [`rx.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/dist/rx.js) | [`rx.compat.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/dist/rx.compat.js) | [`rx.lite.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.lite.js) | [`rx.lite.compat.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.lite.compat.js)

NPM Packages:
- [`rx`](https://www.npmjs.org/package/rx)

NuGet Packages:
- [`RxJS-Complete`](http://www.nuget.org/packages/RxJS-Complete)
- [`RxJS-Experimental`](http://www.nuget.org/packages/RxJS-Experimental)

Unit Tests:
- [`/tests/observable/forkjoin.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/tests/observable/forkjoin.js)
