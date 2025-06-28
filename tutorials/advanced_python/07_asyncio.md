# AsyncIO

AsyncIO is a library to write concurrent code using the `async`/`await` syntax.

**Example:**

```python
import asyncio

async def main():
    print('Hello')
    await asyncio.sleep(1)
    print('world')

asyncio.run(main())
```
