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


## Задание 6

<img width="476" height="72" alt="Снимок экрана — 2026-09-22 в 15 29 23" src="https://github.com/user-attachments/assets/d86d0829-edc1-49b0-81b6-6081657b8612" />

<img width="1375" height="319" alt="Снимок экрана — 2026-09-22 в 15 30 15" src="https://github.com/user-attachments/assets/7bf8667b-65f1-4fb0-b3cb-a104fe977b1a" />


## Задание 7

<img width="748" height="630" alt="Снимок экрана — 2026-09-24 в 11 57 27" src="https://github.com/user-attachments/assets/553ed9da-5a1e-4a5b-b521-feade502cc61" />

<img width="473" height="50" alt="Снимок экрана — 2026-09-24 в 11 57 54" src="https://github.com/user-attachments/assets/ddbeb854-2977-4fdf-a24e-8b46acba7ee7" />


## Задание 8


<img width="925" height="163" alt="Снимок экрана — 2026-09-24 в 12 13 39" src="https://github.com/user-attachments/assets/8460ffa9-6cf0-408e-b7ed-a4eaec27093e" />

<img width="448" height="50" alt="Снимок экрана — 2026-09-24 в 12 22 58" src="https://github.com/user-attachments/assets/8e15f24d-206e-408e-bad1-6da4663668c4" />


## Задание 9

<img width="446" height="125" alt="Снимок экрана — 2026-09-24 в 12 30 51" src="https://github.com/user-attachments/assets/0717a03d-959d-4778-877b-89c28ca53ea1" />

<img width="661" height="20" alt="Снимок экрана — 2026-09-24 в 12 30 33" src="https://github.com/user-attachments/assets/aee97a78-8263-4ebc-824b-a4b5d4364fad" />


## Задание 10


<img width="680" height="103" alt="Снимок экрана — 2026-09-24 в 14 41 01" src="https://github.com/user-attachments/assets/b8fbdc57-7fd7-4bd6-8281-ca7003939906" />


<img width="462" height="69" alt="Снимок экрана — 2026-09-24 в 14 40 44" src="https://github.com/user-attachments/assets/9d9aea66-6cd0-44a4-95fa-8ffa57d83658" />
