# Практика 1

## Задание 1
``` grep -v "^\s*#" /etc/passwd | cut -d: -f1 | sort ```

## Задание 2
``` grep -v "^\s*#" /etc/protocols | awk '{print $2, $1}' | sort -rn | head -n 5 ```


