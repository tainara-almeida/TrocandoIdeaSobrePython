# Variável

Uma variável é como uma caixa no seu computador com uma etiqueta, ou seja, é um espaço limitado para guardar informações.
Trazendo este conceito para o cenário do computador, uma variável é um espaço reservado de memória RAM (não se preocupe tanto com o que isso significa) onde dados são armazenados.

O nome deve começar com uma letra ou sublinhado "_";

Um nome de variável não pode começar com um número

Um nome de variável pode conter apenas caracteres alfanuméricos e sublinhados (Az, 0-9 e _)

Os nomes das variáveis ​​diferenciam maiúsculas de minúsculas (idade, idade e idade são três variáveis ​​diferentes)

---

### **Atribuição de valor** 

A forma mais comum de atribuir valor a uma variável é usar o operador **=** 
```
nome_da_variavel = valor
```

No exemplo acima, o valor pode ser um número, um texto ou outro tipo de variável definida em Python (pode até ser o tipo de coisa que você define! Mas isso é uma conversa mais avançada).

---

### **Tipos Básicos de Variáveis**

Texto: str 

```
nome da variável = “texto”
````


Numérico: int e float
```
int_variavel = 15   
```
```
float_variavel = 15.35
```

Sequências: list
```
lista = [1,2,3,4,5]
````

Mapas: dict
```
dicionario = {
	“Nome”: “Larissa”,
	“Idade”: 19,
	“Saldo_conta”: 1200.45,
	“lista_desejos”: [“Rica”, “Saude”]
}
```
Booleana: boo
```
True, False
```

Existe uma linda regra que, para duas variáveis de tipos diferentes, tem que haver transformação de uma delas para que se torne o mesmo tipo. 

Uma função em Python que mostra qual é o tipo de variável é um tipo de função. 
A resposta dela é no formato <class 'tipo'>. 


```
type(nome_da_variavel)
```

```
text = "Hello"
tipo_text = type(text)
print(tipo_text)

```
Espera-se que a saída mostrada no terminal seja <class 'str'>


# Atividade

```
#Primeiro passo

print(numero)

# ========================
# Segundo passo

# ========================
# Terceiro passo

```

No código acima, a função print(numero) é usada para escrever o conteúdo da variável número no terminal.

---

**Sua missão é:**

- [ ] No primeiro passo você deve atribuir um tipo int com valor 10 à variável número;

- [ ] No segundo passo você deve atribuir um tipo str com valor 10 à variável número;

- [ ] No terceiro passo você deve atribuir um tipo str com valor Dez à variável número;

Lembrando que para atribuir valores do tipo str deve-se utilizar aspas no início e no final do valor

---