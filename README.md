"# python_note" 
# 4 数据类型

## 4.1 整形(int)
- 整形，整数。
```python
print(666) # 1 
```
- 计算
```python 
print(2 + 1)
print(2* 10)
print(10 / 2)
print(10 % 4)
print(2 ** 4)
```
## 4.2 字符串(str)
- 字符串
```python
print("春眠不觉晓")
print('我是"小精灵"')
print(""" 我是"小精灵",他是'小麻雀' """)
```
- 计算
```python 
print("东方" + "明珠")# +拼接
print("*"*10) # *重复字符串多次
```
## 4.3 逻辑值(boolean)
- 值
```python 
print(True) # 真
print(False) # 假
```
- 计算
```python
print(1==1) # True
print(1<>1) # False
print(1)    # True
print(1 == "abc")    # False
print(1 > "abc")    ## TypeError
```
## 5 类型转换
```python 
print(type( int("666") ))  # str -> int 


```