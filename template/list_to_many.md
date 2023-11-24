<pre>
# 00N

---
## 問題

lstにリストを代入して、リストの中身を出力してください。

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
		"input": ["1 2 3 4"],
  	},
	{
		"input": ["ichigo mikan ringo"],
  	},
]
```

## 模範回答
```python
lst = list(map(int, input().split()))

for i in lst:
  print(i)
```
</pre>
