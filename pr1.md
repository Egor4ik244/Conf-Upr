# Практика 1

## Задание 1
``` grep -v "^\s*#" /etc/passwd | cut -d: -f1 | sort ```

## Задание 2
``` grep -v "^\s*#" /etc/protocols | awk '{print $2, $1}' | sort -rn | head -n 5 ```
<img width="860" height="87" alt="Снимок экрана — 2026-09-18 в 11 56 13" src="https://github.com/user-attachments/assets/b0a78def-6075-4496-a360-dbe7d47dddcf" />


