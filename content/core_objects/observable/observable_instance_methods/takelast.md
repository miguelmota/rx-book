# takeLast

`Rx.Observable.prototype.takeLast(count)`
<a href="#rxobservableprototypetakelastcount">#</a> [&#x24C8;](https://github.com/Reactive-Extensions/RxJS/blob/master/src/core/linq/observable/takelast.js "View in source") 

Returns a specified number of contiguous elements from the end of an observable sequence, using an optional scheduler to drain the queue.
  
This operator accumulates a buffer with a length enough to store elements count elements. Upon completion of the source sequence, this buffer is drained on the result sequence. This causes the elements to be delayed.

#### Arguments
1. `count` *(`Number`)*: Number of elements to bypass at the end of the source sequence.

#### Returns
*(`Observable`)*: An observable sequence containing the source sequence elements except for the bypassed ones at the end.   
  
#### Example

[](http://jsbin.com/pulit/1/embed?js,console)

### Location

File:
- [`/src/core/observable/takelast.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/src/core/linq/observable/takelast.js)

Dist:
- [`rx.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/dist/rx.js)
- [`rx.compat.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/dist/rx.compat.js)
- [`rx.lite.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.lite.js)
- [`rx.lite.compat.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.lite.compat.js)

Prerequisites:
- None

NPM Packages:
- [`rx`](https://www.npmjs.org/package/rx)

NuGet Packages:
- [`RxJS-Main`](http://www.nuget.org/packages/RxJS-Main/)
- [`RxJS-Lite`](http://www.nuget.org/packages/RxJS-Lite/)

Unit Tests:
- [`/tests/observable/takelast.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/tests/observable/takelast.js)