Recentemente vimos que as orações, frases ou parágrafos escritos em uma linguagem natural deveriam obedecer certas regras sintáticas. Mas o que acontece quando escrevemos código, ou seja, ordens para um computador escritos em uma linguagem formal? :thinking: Também precisamos respeitar as regras dele!

Por exemplo o seguinte código:
 
```python
def ola_mundo():
	print('olá mundo')
```

não é o mesmo que:

```python
Def Ola_mundo():
	Print('olá mundo')
```

o esto:

```python
def ola_mundo[]:
	print('olá mundo')
```

nem isso:

```python
def ola_mundo():
print('olá mundo')
```

Se não respeitamos estes princípios, aos quais chamaremos _sintaxe_, o computador não poderá interpretar nossa intenção e isto levará a que nossos programas não funcionem como havíamos planejado. :thumbsdown:

> Selecione qual parte do código é idêntica a:
>
```python
def dobro(numero):
   return numero * 2
```
