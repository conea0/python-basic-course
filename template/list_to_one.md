# 00N

---
## 問題

lst にリストを代入して、リストの総和を出力してください。

## テストケース
input = list of int
[
	{
		"input": ["1 2 3 4 5"],
		"output": [15]
  	},
	{
		"input": ["1 2 3 4 5 6 7 8 9 10"],
		"output": [55]
  	},
]


## 模範回答
```python
lst = get_input()
sum = 0

for i in lst:
	sum += i

print(sum)
```