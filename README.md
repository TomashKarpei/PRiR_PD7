# PRiR_PD7
Dla n = 1000:
GPU: 4 sek.
CPU: 1 sek.
Dla n = 10000:
GPU: 4 sek.
CPU: 1 sek.
Dla n = 100000:
GPU: 4 sek.
CPU: 1 sek.
Dla n = 1000000:
GPU: 4 sek.
CPU: 1 sek.
Dla n = 10000000:
GPU: 4 sek.
CPU: 3 sek.
Dla n = 100000000:
GPU: 6 sek.
CPU: 16 sek.
Z powyszych wyników możemy zauważyć, że zaczynając od n = 100000000 GPU wykonuje operacji szybciej, niż CPU. Ale dla takiej ilości operacji wyniki nie są poprawne. Z tego powodu, że w poprzednich wynikach GPU potrzebuje czasu na podkręcenie, CPU wykonuje to szybciej i dla takich zadań lepiej będzie używać CPU.
