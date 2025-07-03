# 🧳 BAGAGGIO: Exercícios para Entrevista em Grupo – Estágio 🧳

## 🤔 Lógica de Programação
### O desafio requer que o candidato tenha as seguintes habilidades interpessoais:
- **Resolução de problemas**: Capacidade de enfrentar e resolver desafios lógicos.
- **Otimização de algoritmos**: Buscar soluções eficientes, não apenas corretas.
- **Depuração e análise**: Identificação e correção de erros no código.
- **Pensamento lógico estruturado**: Raciocínio passo a passo para chegar à solução.
- **Melhoria contínua**: Aprimoramento técnico por meio da prática.

---

## 📚 Linguagens permitidas para a realização dos exercícios
- Python
- Go
- JavaScript
- Java

---

## 1. 🔠 Frase Palíndroma

### 📝 Descrição:  
Uma frase é considerada um palíndromo se, após converter todas as letras para minúsculas e remover todos os caracteres não alfanuméricos, ela for igual lida da esquerda para a direita e vice-versa.

### ✅ Exemplos:
```python
Input: "A man, a plan, a canal: Panama"
Output: True  # "amanaplanacanalpanama" é igual ao reverso

Input: "race a car"
Output: False  # "racaecar" não é igual ao reverso

Input: " "
Output: True  # string vazia é considerada palíndroma
```

---

## 2. 🆎 Primeiro Caractere Único

### 📝 Descrição:  
Dada uma string `s`, retorne o **índice do primeiro caractere não repetido**.  
Se não houver caractere único, retorne -1.

### ✅ Exemplos:
```python
Input: "banana"
Output: 0   # 'b' aparece apenas uma vez, na posição 0

Input: "tomate"
Output: 1   # 'o' aparece apenas uma vez, na posição 1

Input: "aabbcc"
Output: -1  # Todos os caracteres se repetem
```

---

## 3. 🚫 Remover Duplicatas de um Array Ordenado

### 📝 Descrição:  
Dado um array de inteiros ordenado em ordem crescente, remova os **elementos duplicados** de forma que cada elemento único apareça apenas uma vez.

Retorne **apenas** o novo comprimento do array após a remoção.  

Você **não precisa** retornar o array modificado.

*Opcional:*
- Faça as modificações **in-place**.
- Garanta que os primeiros `k` elementos contenham os valores corretos.

### ✅ Exemplos:
```python
Input: [1, 1, 2]
Output: 2  # Os dois primeiros elementos são [1, 2, _]

Input: [0, 0, 1, 1, 1, 2, 2, 3, 3, 4]
Output: 5  # Array modificado: [0, 1, 2, 3, 4, _, _, _, _, _]
```

---

## 4. ➕ Dois Números que Somam um Alvo

### 📝 Descrição:  
Dado um array `nums[]` e um número `target`, retorne os **índices de dois números** cuja soma seja igual ao `target`.  
Assuma que sempre existe **exatamente uma** solução válida e que **não pode usar o mesmo índice duas vezes**.

### ✅ Exemplos:
```python
Input: nums = [2, 7, 11, 15], target = 9
Output: [0, 1]

Input: nums = [3, 2, 4], target = 6
Output: [1, 2]
```

---

## 5. 📈 Melhor Momento para Comprar e Vender Ação

### 📝 Descrição:  
Você recebe um array `precos[]` onde cada valor representa o preço de uma ação em um determinado dia.  
Seu objetivo é determinar o **maior lucro possível**, comprando e vendendo em dias diferentes (sempre comprar antes de vender).

### ✅ Exemplos:
```python
Input: [7, 1, 5, 3, 6, 4]
Output: 5  # Compra em 1 (índice 1), vende em 6 (índice 4)

Input: [7, 6, 4, 3, 1]
Output: 0  # Nenhuma oportunidade de lucro
```

---

## 🎯 Dica Final  
O foco aqui **não é ter o código perfeito, 100% funcional ou estilizado ao extremo**.  

Nosso objetivo é observar:
- **Como você estrutura e explica a lógica por trás de um problema**
- **Como você colabora, se comunica e interage com o grupo**
- Como você **organiza o raciocínio**, mesmo diante de incertezas
- Sua **capacidade de se adaptar**, propor caminhos e ajustar soluções em equipe

Mais importante do que acertar tudo é **mostrar como você pensa** e **como você contribui para o grupo**.

Boa sorte e se divirta no processo! 🚀
