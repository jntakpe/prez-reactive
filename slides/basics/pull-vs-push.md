## Pull vs Push

| Pull           | Push  |
|:-------------:| :-----:|
| `Iterable` | `Publisher` |
| `T next()` | `onNext(T)` |
| `throws Exception` | `onError(Exception)` |
| `returns;` | `onCompleted()` |
