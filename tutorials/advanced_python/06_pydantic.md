# Pydantic

Pydantic is a library for data validation and settings management using Python type annotations.

**Example:**

```python
from pydantic import BaseModel

class User(BaseModel):
    id: int
    name: str = 'John Doe'
    signup_ts: datetime | None = None
    friends: list[int] = []


user = User(id=123, name='John Doe', signup_ts='2024-06-28 12:00', friends=[1, 2, 3])
print(user.model_dump_json(indent=4))

```
