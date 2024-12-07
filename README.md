# Instrumentação Industrial I
## 🐍 Aula Prática 01: Introdução ao Python

## 📖 Sumário
1. [O que é Python?](#o-que-é-python)
2. [Principais Recursos do Python](#principais-recursos-do-python)
3. [Instalação do Python](#instalação-do-python)
4. [Primeiros Passos](#primeiros-passos)
5. [Estrutura Básica de Código](#estrutura-básica-de-código)
6. [Recursos Avançados](#recursos-avançados)
7. [Principais Bibliotecas e Frameworks](#principais-bibliotecas-e-frameworks)
8. [Próximos Passos e Comunidade](#próximos-passos-e-comunidade)
9. [Links Úteis](#links-úteis)

---

## O que é Python?

Python é uma linguagem de programação de alto nível, interpretada e multiparadigma, amplamente utilizada em diferentes áreas, como:

- 🌐 **Desenvolvimento Web**
- 📊 **Análise de Dados**
- 🤖 **Inteligência Artificial e Machine Learning**
- 🛠️ **Automação de Tarefas**
- 📱 **Aplicações Desktop**

Foi criada por **Guido van Rossum** em 1991 e possui uma sintaxe simples e direta, ideal para iniciantes e profissionais.

---

## Principais Recursos do Python

- **Sintaxe Simples e Legível**: Fácil de aprender e escrever.
- **Linguagem Multiparadigma**: Suporte para programação procedural, orientada a objetos e funcional.
- **Ampla Biblioteca Padrão**: Ferramentas prontas para manipulação de arquivos, redes, matemática, etc.
- **Portabilidade**: Disponível para diversos sistemas operacionais, como Windows, Linux e macOS.
- **Comunidade Ativa**: Milhões de desenvolvedores contribuem com bibliotecas, frameworks e suporte.

---

## Instalação do Python

### 🖥️ Windows, macOS e Linux

1. Acesse o site oficial do Python: [Python.org](https://www.python.org/).
2. Baixe e instale a versão mais recente compatível com seu sistema operacional.
3. Durante a instalação, marque a opção **"Add Python to PATH"**.

### Verifique a instalação

No terminal, execute:

```bash
python --version
`````

Se instalado corretamente, você verá a versão do Python. O python pode ser utilizado na nuvem através do [google colab](https://colab.research.google.com/drive/1yXpXdn4heN9eIu7nd65hKVLudxkSb9Vd?usp=sharing#scrollTo=xdGC2NSuyt4e).

Outra forma de trabalhar é com o VSCode tanto usando o **codigo bruto** com extensões *.py quanto usando o **jupiter notebook** (ambiente base do google colab no VSCode) com extensões *.ipynb.

---

## Primeiros Passos

### 🐍 "Hello, World!" em Python

Crie um arquivo `hello.py` com o seguinte conteúdo:

```python
print("Hello, World!")
`````

### Execute o arquivo no terminal:

```bash
python hello.py
`````
---

## Estrutura Básica de Código

### 1. Variáveis e Tipos

```python
nome = "Alice"  # String  
idade = 25      # Inteiro  
altura = 1.68   # Float  
eh_programadora = True  # Booleano  
`````

### 2. Estruturas Condicionais

```python
if idade >= 18:  
    print("Você é maior de idade.")  
else:  
    print("Você é menor de idade.")  
`````

### 3. Laços de Repetição

```python
for i in range(5):  
    print(f"Contagem: {i}")  
`````

### 4. Funções

```python
def soma(a, b):  
    return a + b  

resultado = soma(10, 20)  
print(f"A soma é: {resultado}")  
`````

---

## Recursos Avançados

### 1. Classes e Objetos

```python
class Pessoa:  
    def __init__(self, nome, idade):  
        self.nome = nome  
        self.idade = idade  

    def apresentar(self):  
        print(f"Olá, meu nome é {self.nome} e tenho {self.idade} anos.")  

pessoa = Pessoa("Alice", 25)  
pessoa.apresentar()  
`````

### 2. Trabalhando com Arquivos

```python
with open("arquivo.txt", "w") as arquivo:  
    arquivo.write("Hello, Python!")  
`````

### 3. Bibliotecas Externas

Instale bibliotecas com o pip:

```python
pip install requests
`````

Use a biblioteca:

```python
import requests

response = requests.get("https://api.github.com")  
print(response.json())
`````

---

## Principais Bibliotecas e Frameworks

| **Categoria**       | **Bibliotecas Populares**          |
|----------------------|------------------------------------|
| **Web**             | Flask, Django                     |
| **Análise de Dados**| NumPy, Pandas, Matplotlib         |
| **IA/ML**           | TensorFlow, PyTorch, Scikit-learn |
| **Automação**       | Selenium, BeautifulSoup           |
| **Testes**          | pytest, unittest                  |

---

## Próximos Passos e Comunidade

- Participe de meetups e conferências como a **PyCon**.
- Explore a [documentação oficial do Python](https://docs.python.org/3/).
- Contribua com projetos de código aberto no GitHub.

---
## Tarefa a ser executada: 

 - Insira mais uma faixa de **660 Volts** na simulação do arquivo 04_Simulação_do_Voltímetro_no_Python.ipynb.

---

## Links Úteis

- [Site Oficial do Python](https://www.python.org/)
- [Documentação Oficial](https://docs.python.org/3/)
- [Tutorial Python no W3Schools](https://www.w3schools.com/python/)
- [PyPI - Repositório de Pacotes Python](https://pypi.org/)
- [Guia para Iniciantes no Python](https://realpython.com/)
