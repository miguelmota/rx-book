# while | whileDo

`Rx.Observable.while(condition, source)`
<a href="#rxobservablewhilecondition-source">#</a> [&#x24C8;](https://github.com/Reactive-Extensions/RxJS/blob/master/src/core/linq/observable/while.js "View in source") 

Repeats source as long as condition holds emulating a while loop.  There is an alias for this method called 'whileDo' for browsers <IE9.

![while](https://github.com/Netflix/RxJava/wiki/images/rx-operators/whileDo.png)

### Arguments
1. `condition` *(`Function`)*: The condition which determines if the source will be repeated.
2. `source` *(`Observable`)*: The observable sequence that will be run if the condition function returns true.

#### Returns
*(`Observable`)*: An observable sequence which is repeated as long as the condition holds. 

#### Example

[](http://jsbin.com/serat/1/embed?js,console)

### Location

File:
- [/src/core/observable/while.js](https://github.com/Reactive-Extensions/RxJS/blob/master/src/core/linq/observable/while.js)

Dist:
- [`rx.experimental.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.experimental.js)

Prerequisites:
- [`rx`](https://www.npmjs.org/package/rx).experimental.js
- [`rx.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/dist/rx.js) | [`rx.compat.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/dist/rx.compat.js) | [`rx.lite.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.lite.js) | [`rx.lite.compat.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.lite.compat.js)

NPM Packages:
- [`rx`](https://www.npmjs.org/package/rx)

NuGet Packages:
- [`RxJS-Experimental`](http://www.nuget.org/packages/RxJS-Experimental)

Unit Tests:
- [/tests/observable/while.js](https://github.com/Reactive-Extensions/RxJS/blob/master/tests/observable/while.js)