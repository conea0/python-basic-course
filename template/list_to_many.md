<pre>
# 00N

---
## 問題

lstにリストを代入して、リストの中身を出力してください。

## テストケース
input = list of str
```json
[
	{
		"input": ["1 2 3 4 5"],
		"output": ["1","2","3","4","5"]
  	},
	{
		"input": ["ichigo mikan ringo"],
		"output": ["ichigo","mikan","ringo"]
  	},
]
```

## 模範回答
```python
lst = get_input()

for i in lst:
	print(i)
```
</pre>