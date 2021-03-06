importance: 5

---
# 피보나치 수 계산하기

[피보나치 수](https://ko.wikipedia.org/wiki/%ED%94%BC%EB%B3%B4%EB%82%98%EC%B9%98_%EC%88%98) 는 첫째 및 둘째 항이 1이며 그 뒤의 모든 항은 바로 앞 두 항의 합인 수열로, <code>F<sub>n</sub> = F<sub>n-1</sub> + F<sub>n-2</sub></code>이라는 공식으로 표현됩니다. 

수열의 처음 두 숫자는 `1`이고, 그 다음 항들은 `2(1+1)`,`3(1+2)`,`5(2+3)`가 됩니다(`1, 1, 2, 3, 5 , 8, 13, 21 ...`).

피보나치 수는 [황금 비율](https://en.wikipedia.org/wiki/Golden_ratio) 등의 우리 주변을 둘러싼 수많은 자연 현상과 관련이 있습니다.

`n 번째` 피보나치 수를 반환하는 함수 `fib(n)`을 작성해보세요.

예시:

```js
function fib(n) { /* 답안은 여기에 작성 */ }

alert(fib(3)); // 2
alert(fib(7)); // 13
alert(fib(77)); // 5527939700884757
```

참고: `fib (77)`를 호출하면 연산 시간이 1초도 걸리지 않게 빨라야 합니다. 
