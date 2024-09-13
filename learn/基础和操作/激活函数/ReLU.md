```python
from torch import nn
nn.ReLU(inplace=True)
```
inplace=True    表示直接在原始内存位置上修改数据，而不是新建新的对象，可以节省一些内存，但是修改了原始的输入张量