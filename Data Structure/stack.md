# 스택 Stack

설명 어쩌구 저쩌구

### 장점

- ㄹㅁㄴㅇㅇㄴㄹ

### 단점

- ㅇㄹㅁㄴㅇㅁ

시간복잡도 :

## 구현

javaScript

```js
class Stack {
  constructor() {
    this.storage = {};
    this.length = 0;
  }
  push(element) {
    this.storage[this.length++] = element;
  }

  pop() {
    if (this.length > 0) {
      let removed = this.storage[--this.length];
      return removed;
    }
  }

  size() {
    return this.length;
  }

  empty() {
    return this.length ? 0 : 1;
  }

  top() {
    return this.length === 0 ? -1 : this.storage[this.length];
  }
}
```

## Reference

링크
