importance: 5

---

# 测试代码中有什么错误？

下面这个 `pow` 的测试代码有什么错误？

```js
it("Raises x to the power n", function() {
  let x = 5;

  let result = x;
  assert.equal(pow(x, 1), result);

  result *= x;
  assert.equal(pow(x, 2), result);

  result *= x;
  assert.equal(pow(x, 3), result);
});
```

附：从语法上来说这些测试代码是正确且通过的。
