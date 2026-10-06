# Практика 2

## Задание 1
```python
from importlib.metadata import metadata

meta = metadata('matplotlib')

print(f"Пакет:     {meta['Name']}")
print(f"Версия:    {meta['Version']}")
print(f"Лицензия: {meta['License']}")
```
