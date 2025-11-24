# Random Password Generator

Código escrito em Python 3 para gerar senhas completamente aleatórias de 8 digitos baseados no [ASCII code](https://pt.wikipedia.org/wiki/ASCII).

* Códigos, sinais, letras e algorismos sinalizados abaixo!


# O que é "ASCII Code" ? 
 Densenovlvido a partir de 19560 o American Standard Code for Information Interchange - ASCII, É um sistema de representação de letras, algarismos e sinais de pontuação e de controle. Através de um sinal codificado em forma de código binário (cadeias de bits formada por vários 0 e 1), que representa um conjunto de 128 sinais: 95 sinais gráficos (letras do alfabeto latino, algarismos arábicos, sinais de pontuação e sinais matemáticos) e 33 sinais de controle, utilizando 7 bits para representar todos os seus símbolos.

* [Wikipedia](https://pt.wikipedia.org/wiki/ASCII) - Fonte das informações acima.

## 🚀 Começando

Essas instruções permitirão que você entenda como funciona o projeto e modifique para suas necessidades.

Consulte **[ASCII Table](https://www.101computing.net/wp/wp-content/uploads/ASCII-Table.pdf)** para saber quais códigos foram utilizados e alterar por conta própria.


* Randomizador de Strings em Python :

```
import random

def shuffle(string):
    templist = list(string)
    random.shuffle(templist)
    return ''.join(templist)

```

* Escolhe aleatóriamente uma letra (maiúscula ou minúscula), um digito e um sinal de pontuação :
* ##### Caso precise de mais de 8 digitos adicione uma linha como abaixo, alterando a identificação numérica. (Letter1, Letter2, Letter3...)

```
uppercaseLetter1=chr(random.randint(65,90))

lowercaseLetter1=chr(random.randint(97,122))

digit1=chr(random.randint(48,57))

punctuationSign1=chr(random.randint(32,152))

```
* Randomizador da senha final :
* ###### Se adicionou mais digitos como foi ensinado acima, é necessário colocar abaixo também! Apenas siga o padrão abaixo ( uppercaseLetter1 + uppercaseLetter2 + .... )

```
password = uppercaseLetter1 + uppercaseLetter2 + lowercaseLetter1 + lowercaseLetter2 + digit1 + digit2 + punctuationSign1 + punctuationSign2
password = shuffle(password)

```


## 🛠️ Construído com

Mencione as ferramentas que você usou para criar seu projeto

* [101computing](https://www.101computing.net/random-password-generator/) - Baseado neste desafio da plataforma "101computing"
* [ASCII Table](https://www.101computing.net/wp/wp-content/uploads/ASCII-Table.pdf) - Tabela dos Códigos ASCII utilizados
* [ascii-code.com](https://www.ascii-code.com/) - Site de referência para o ASCII

## ✒️ Autores

Mencione todos aqueles que ajudaram a levantar o projeto desde o seu início

* **Maurício Santos**  **-** [GitHub](https://github.com/mauricioscc) - [LinkedIn](https://www.linkedin.com/in/mauriciosantosc/)
* **101computing.net** - *Tutorial* - [101computing.net](https://www.101computing.net/)

---
