# 🔮 Projeto: Descobridor de Signo Zodiacal

Este projeto é uma aplicação web desenvolvida em PHP que permite ao usuário descobrir seu signo zodiacal a partir da data de nascimento.

---

## 📌 Funcionalidades

* Inserção da data de nascimento
* Consulta automática do signo
* Leitura de dados a partir de um arquivo XML
* Exibição de informações do signo
* Interface estilizada com Bootstrap

---

## 🛠️ Tecnologias utilizadas

* PHP
* HTML5
* CSS3
* Bootstrap
* XML
* XAMPP (ambiente local)

---

## 📁 Estrutura do projeto

```
PROJECT/
│
├── assets/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   └── imgs/
│
├── layouts/
│   └── header.php
│
├── index.php
├── show_zodiac_sign.php
└── signos.xml
```

---

## ⚙️ Pré-requisitos

Antes de começar, você precisa ter instalado:

* [XAMPP](https://www.apachefriends.org/download.html)
* Navegador web (Chrome, Edge, etc.)

---

## 🚀 Como executar o projeto

### 1. Clonar o repositório

```bash
git clone https://github.com/higorMalaquias/signos.git
```

---

### 2. Mover para o diretório do XAMPP

Após clonar, mova a pasta para:

```
C:\xampp\htdocs\
```

O caminho final deve ficar assim:

```
C:\xampp\htdocs\signos
```

---

### 3. Iniciar o XAMPP

* Abra o XAMPP
* Inicie o módulo **Apache**

---

### 4. Acessar o projeto

Abra o navegador e acesse:

```
http://localhost/signos
```

---

## 📄 Como funciona

* O usuário insere sua data de nascimento
* O sistema envia os dados via POST
* O PHP lê o arquivo `signos.xml`
* A aplicação verifica em qual intervalo de datas o usuário se encaixa
* O signo correspondente é exibido na tela

---

## 🧠 Lógica utilizada

A aplicação utiliza:

* `simplexml_load_file()` para leitura do XML
* Comparação de datas para identificar o signo
* Separação de layout com `header.php`

---

## ✅ Checklist do projeto

* ✔️ Formulário funcional
* ✔️ Leitura de XML
* ✔️ Lógica de verificação de datas
* ✔️ Página de resultado
* ✔️ Estilização com Bootstrap
* ✔️ Testado em ambiente localhost

---

## 💡 Possíveis melhorias

* Validação de data mais robusta
* Interface mais moderna
* Uso de banco de dados вместо XML
* Deploy online

---

## 👨‍💻 Autor

Desenvolvido por **Higor Malaquias**

---

## 📎 Licença

Este projeto é apenas para fins educacionais.
