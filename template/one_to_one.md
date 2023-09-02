# 00N

ここはmarkdownを自由に記述できる。

ここまで
---
## 問題

nameに自分の名前を代入して、`hello (自分の名前)` を出力してください。

## テストケース

input = str
```json
[
	{
		"input": ["shuya"],
		"output": ["hello shuya"]
  	},
	{
		"input": ["taro"],
		"output": ["hello taro"]
	}
]
```

## 模範回答
```python
name = get_input()
print("hello " + name)
```