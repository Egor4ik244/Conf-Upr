# Практика 2

## Задание 1
```python
from importlib.metadata import metadata

meta = metadata('matplotlib')

print(f"Пакет:     {meta['Name']}")
print(f"Версия:    {meta['Version']}")
print(f"Лицензия: {meta['License']}")
```
<img width="596" height="198" alt="Снимок экрана — 2026-10-06 в 10 17 32" src="https://github.com/user-attachments/assets/0a6e15ce-a2be-4a6e-a969-b06e2a1b8ec0" />
