## A excercise script that compares numbers that is in a list and tells if its in a ascending order or descending order.

```python
nums = [5,10,15,20]
counter = 0
if nums[0] < nums[1]:
  for num in nums[1:]:
    if nums[counter] < num:
      counter +=1
      a = 'asc'

    else:
      a = 'not asc'
      break

print(a)
```

### Result

```
asc```
