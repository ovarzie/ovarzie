```python
from Github import README, ReadmeLoader

class Ovarz(README):
  def __init__(self):
    super().__init__()
    self.name = "milo | darta/alice"
    self.description = "an passionate latvian python developer"
    self.pronouns = "she/her"
    self.efficiency = "python"
    self.workingon = "aerith"
    self.interests = "billie eilish and once human"
    self.theloml = "lukas"

if __name__ == "__main__":
  ovarz = Ovarz()
  ReadmeLoader.load(Ovarz)
```
