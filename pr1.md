# Практика 1

## Задание 1
``` grep -v "^\s*#" /etc/passwd | cut -d: -f1 | sort ```

<img width="929" height="483" alt="Снимок экрана — 2026-09-18 в 21 43 10" src="https://github.com/user-attachments/assets/b69aebf4-311c-44e6-8def-981ff8c5c66d" />


## Задание 2
``` grep -v "^\s*#" /etc/protocols | awk '{print $2, $1}' | sort -rn | head -n 5 ```

<img width="860" height="87" alt="Снимок экрана — 2026-09-18 в 11 56 13" src="https://github.com/user-attachments/assets/b0a78def-6075-4496-a360-dbe7d47dddcf" />


## Задание 3

<img width="449" height="188" alt="Снимок экрана — 2026-09-21 в 13 33 01" src="https://github.com/user-attachments/assets/126719d9-e375-413c-beda-d14ae93dacd2" />

<img width="327" height="58" alt="Снимок экрана — 2026-09-21 в 13 34 21" src="https://github.com/user-attachments/assets/ebfa9668-1ca7-4dd1-8f33-cf5f783686b8" />


