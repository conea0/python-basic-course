<pre>
# 00N

---
## 問題

nに数値を代入して、1からnまでの偶数のリストと、奇数のリストを出力してください。

### inputの方法
いかのコードを利用してよい。
```python
a = input()
```

## テストケース
```
[
	{
		"inputs": [10],
  	},
	{
		"inputs": [5],
  	},
	{
		"inputs": [12],
  	},
]
```


## 模範回答
```python
n = input()
even = []
odd = []

for i in range(1,n+1):
	if i % 2 == 0:
		even.append(i)
	else:
		odd.append(i)

print(even)
print(odd)
```
</pre>