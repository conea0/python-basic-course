<pre>
# 00N

---
## 問題

lst にリストを代入して、リストの総和を出力してください。

### inputの方法
配列のinputは`1 2 3 4`という形式で行われる。
これをpythonの配列にするために、以下のコードを利用してよい。
```python
a = list(map(int, input().split()))
```

## テストケース
```json
[
	{
		"input": ["1 2 3 4 5"],
  	},
	{
		"input": ["1 2 3 4 5 6 7 8 9 10"],
  	},
]
```


## 模範回答
```python
lst = list(map(int, input().split()))
sum = 0

for i in lst:
	sum += i

print(sum)
```
</pre>
