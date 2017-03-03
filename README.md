# memobird-python
unofficial memobird python sdk


# example
```python
from memobird import Memobird, Paper

paper = Paper()
paper.add_text("中文测试")
paper.add_image('1.png')

memobird = Memobird(ak)
memobird.setup_device(device_id)
memobird.print_paper(paper)
```
