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


## Задание 4
``` grep -ioE '[a-zA-Z_][a-zA-Z0-9_]*' Car.java | awk '!seen[tolower($0)]++' | tr '\n' ' ' && echo "" ```

<img width="843" height="43" alt="Снимок экрана — 2026-09-21 в 13 54 16" src="https://github.com/user-attachments/assets/0274894e-e8e7-4ddc-80be-ede1b3062ea9" />


## Задание 5

<img width="594" height="358" alt="Снимок экрана — 2026-09-22 в 14 57 44" src="https://github.com/user-attachments/assets/617b9346-f5d5-417f-a48c-b18c56b787b7" />


<img width="639" height="118" alt="Снимок экрана — 2026-09-22 в 15 02 16" src="https://github.com/user-attachments/assets/bb37007a-bf37-4a31-a54f-8bf598882268" />

