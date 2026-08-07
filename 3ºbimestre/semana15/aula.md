# 🚀 Aula 1 - Git Básico: Repositório, Commit e Histórico

## 📚 Objetivo da Aula

Aprender os conceitos fundamentais do **Git**, criando um repositório, registrando alterações através de commits e visualizando o histórico de versões de um projeto.

---

## 🤔 Por que usar controle de versão?

Quando salvamos arquivos manualmente, é comum criar versões como:

```text
trabalho_final.docx
trabalho_final_agora_vai.docx
trabalho_final_versao2.docx
trabalho_final_DEFINITIVO.docx
```

Esse método pode causar confusão, perda de informações e dificuldade para recuperar versões anteriores.

O **Git** resolve esse problema registrando todas as alterações realizadas no projeto de forma organizada.

---

## 🔍 O que é Git?

O Git é um sistema de **controle de versão distribuído**, utilizado para acompanhar mudanças em arquivos e projetos.

### Principais características:

* ✅ Registra alterações ao longo do tempo.
* ✅ Mantém um histórico completo do projeto.
* ✅ Permite recuperar versões anteriores.
* ✅ Funciona offline.
* ✅ Cada usuário possui uma cópia completa do repositório.

---

## 📸 Conceito de Snapshot

O Git trabalha com **snapshots (instantâneos)**.

Em vez de salvar apenas as diferenças entre arquivos, ele registra uma "foto" completa do estado do projeto em determinado momento.

---

## 🔄 Ciclo de Vida dos Arquivos no Git

### 1️⃣ Working Directory

Área onde os arquivos são criados, editados ou removidos.

### 2️⃣ Staging Area

Área de preparação onde escolhemos quais alterações irão para o próximo commit.

### 3️⃣ Repository

Local onde o Git armazena os commits e todo o histórico do projeto.

### Analogia

📷 Working Directory → Tirar fotos

🖼️ Staging Area → Escolher as melhores fotos

📚 Repository → Guardar as fotos em um álbum

---

## ⚙️ Configurando o Git

Antes de criar commits, é necessário informar seu nome e e-mail:

```bash
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@email.com"
```

Verificar configuração:

```bash
git config --list
```

---

## 📁 Criando um Repositório

Criar uma pasta para o projeto e inicializar o Git:

```bash
git init
```

Resultado esperado:

```text
Initialized empty Git repository
```

---

## ➕ Adicionando Arquivos

Criar um arquivo:

```text
index.txt
```

Verificar status:

```bash
git status
```

Adicionar à área de preparação:

```bash
git add index.txt
```

---

## 💾 Criando o Primeiro Commit

Registrar a alteração no histórico:

```bash
git commit -m "Cria o arquivo inicial do projeto"
```

Verificar situação atual:

```bash
git status
```

Resultado:

```text
nothing to commit, working tree clean
```

---

## 🚫 Ignorando Arquivos com .gitignore

Alguns arquivos não devem ser enviados para o repositório, como:

```text
senhas.txt
```

Criar um arquivo:

```text
.gitignore
```

Adicionar:

```text
senhas.txt
```

Assim o Git ignorará esse arquivo automaticamente.

---

## 📜 Visualizando o Histórico

Exibir todos os commits realizados:

```bash
git log
```

Informações disponíveis:

* Autor do commit
* Data
* Hash identificador
* Mensagem do commit

---

## 🧠 Boas Práticas

* Escrever mensagens claras nos commits.
* Fazer commits pequenos e frequentes.
* Utilizar `.gitignore` para arquivos sensíveis.
* Consultar o histórico regularmente.

### Exemplo de boa mensagem:

```bash
git commit -m "Adiciona tela de login"
```

### Evite:

```bash
git commit -m "Atualização"
```

---

## ✅ Resumo Final

Durante a aula aprendemos a:

* Configurar o Git com nome e e-mail.
* Criar um repositório usando `git init`.
* Adicionar arquivos com `git add`.
* Registrar versões com `git commit`.
* Ignorar arquivos usando `.gitignore`.
* Consultar o histórico através de `git log`.
* Entender o fluxo:

```text
Working Directory
       ↓
Staging Area
       ↓
Repository
```

---

## 🏆 Conclusão

O Git é uma ferramenta essencial para qualquer desenvolvedor, permitindo controlar versões, recuperar alterações e trabalhar em equipe de forma organizada e segura.
