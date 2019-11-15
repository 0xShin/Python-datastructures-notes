## Stack - is a data structure that acts like a container that the elements are inserted and removed based on a last-in first-out principle.

```python
class Stack:
  def __init__(self):
    self.items=[]

  def push(self,item):
    self.items.append(item)
  def pop(self):
    self.items.pop()
  def show(self):
    print(self.items)

stack = Stack()
stack.push('hello')
stack.show()
stack.pop()
stack.show()
```
## Result:
```
['hello']
[]
```
