# Tabuada em Python

Um programa simples em Python que gera:

- Tabuada de multiplicação
- Soma
- Subtração
- Divisão

O usuário escolhe:
- O número da tabuada
- Até onde a tabuada vai

## Código

```python
n = int(input("Digite o número que você quer fazer a tabuada: "))
lim = int(input("Digite até onde vai parar: "))

for i in range(1, lim + 1):
    resultado = n * i
    print(f"{n} X {i} = {resultado}")

print(" ")

for i in range(1, lim + 1):
    resultado = n + i
    print(f"{n} + {i} = {resultado}")

print(" ")

for i in range(1, lim + 1):
    resultado = n - i
    print(f"{n} - {i} = {resultado}")

print(" ")

for i in range(1, lim + 1):
    resultado = n / i
    print(f"{n} / {i} = {resultado}")
```

## Linguagem usada:

- Python 3

## Autor

Feito por Luan Gadelha 😎
