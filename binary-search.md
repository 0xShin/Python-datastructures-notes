## Binary search algorithm is a half interval search algorithm that starts on the middle element of your array.

```python
arr= ['test','arf','bum','shen','lem']

mid=len(arr) // 2
first_half = arr[:mid]
second_half = arr[mid:]
print(first_half)
print(second_half)

```
##Result:
```python
['test', 'arf']
['bum', 'shen', 'lem']
```
