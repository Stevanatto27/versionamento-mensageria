# 📦 Projeto de Versionamento com Git e GitHub

> 🚀 Repositório criado para estudo e prática de **controle de versão**, utilizando **Git** e **GitHub**, desde conceitos básicos até boas práticas aplicadas em projetos reais.

---

## 📚 Sobre o Projeto

Este projeto tem como objetivo desenvolver habilidades em versionamento de código, permitindo:

- 📖 Entender os conceitos fundamentais de controle de versão;
- 🔄 Utilizar os principais comandos do Git no dia a dia;
- 🌿 Trabalhar com branches e estratégias de desenvolvimento;
- 🔀 Realizar merges e resolver conflitos;
- 🤝 Simular colaboração em equipe com GitHub;
- 🚀 Aplicar boas práticas em projetos reais.

---

## 🧰 Ferramentas Utilizadas

- 🐙 Git
- 🌐 GitHub
- 💻 Terminal / Prompt de Comando
- 📝 Markdown
- 💻 VS Code

---

## 📁 Estrutura do Projeto

```bash
versionamento/
├── README.md
├── docs/         # Documentações e anotações
├── exemplos/     # Exemplos práticos
├── atividades/   # Exercícios propostos
└── projetos/     # Aplicações práticas
```

---

## ⚙️ Conteúdos Abordados

- 🧾 Conceito de Versionamento
- 📌 Commits
- 🌿 Branches
- 🔀 Merge
- 🔁 Rebase
- 📥 Pull Requests
- 🧩 Resolução de conflitos
- 🏷️ Tags e Versionamento Semântico

---

## 📌 Pré-requisitos

Antes de começar, você precisa ter instalado em sua máquina:

- Git (versão 2.0 ou superior)
- Conta no GitHub
- Editor de código (recomendado: VS Code)

Verifique a instalação:

```bash
git --version
```

---

## 🚀 Como Executar

Clone o repositório:

```bash
git clone https://github.com/prof-andrericardo/versionamento.git
```

Acesse a pasta:

```bash
cd versionamento
```

---

## 🔄 Fluxo Básico com Git

```bash
# Verificar alterações
git status

# Adicionar arquivos
git add .

# Criar commit
git commit -m "feat: descrição da alteração"

# Enviar para o GitHub
git push origin main
```

---

## 🌿 Trabalhando com Branches

```bash
# Criar nova branch
git checkout -b nova-feature

# Trocar de branch
git checkout main

# Mesclar branch
git merge nova-feature
```

---

## 🛠️ Comandos Úteis do Git

```bash
# Ver histórico de commits
git log

# Histórico resumido
git log --oneline

# Atualizar repositório
git pull origin main

# Remover arquivo do stage
git reset nome-do-arquivo

# Deletar branch
git branch -d nome-da-branch
```

---

## 🔥 Principais Erros e Soluções

| Erro | Solução |
|------|---------|
| Merge conflict | Resolver manualmente e fazer novo commit |
| Commit errado | `git commit --amend` |
| Push rejeitado | `git pull origin main` |
| Arquivo errado adicionado | `git reset nome-do-arquivo` |

---

## 📈 Linha do Tempo do Versionamento

1. Criar ou clonar repositório
2. Fazer alterações no projeto
3. Adicionar arquivos com `git add`
4. Criar commit com `git commit`
5. Enviar para o GitHub com `git push`
6. Revisar mudanças remotamente

---

## 🧪 Boas Práticas

✔️ Faça commits pequenos e objetivos  
✔️ Utilize mensagens padronizadas (**Conventional Commits**)  
✔️ Trabalhe sempre em branches separadas  
✔️ Revise antes de enviar (`push`)  
✔️ Documente alterações importantes  
✔️ Utilize Pull Requests em trabalhos colaborativos  

---

## 📝 Exemplos de Commits

```bash
feat: adiciona tela de login
fix: corrige erro no cadastro
docs: atualiza documentação
refactor: melhora organização do código
style: ajusta formatação do código
```

---

## 🎓 Aprendizados Desenvolvidos

Ao concluir este projeto, foram desenvolvidas habilidades em:

- Organização de código
- Trabalho colaborativo
- Controle de mudanças
- Resolução de conflitos
- Planejamento de versões
- Boas práticas de desenvolvimento

---

## 🎯 Objetivo Final

Ao final deste projeto, espera-se que o desenvolvedor seja capaz de:

- 📈 Organizar o histórico do código;
- 🤝 Trabalhar em equipe com eficiência;
- 🚀 Aplicar versionamento em projetos reais;
- 🧩 Resolver conflitos de forma estratégica.

---

## 🤝 Contribuição

Contribuições são bem-vindas!

```bash
# Faça um fork
# Crie uma branch
git checkout -b minha-contribuicao

# Commit
git commit -m "feat: minha contribuição"

# Push
git push origin minha-contribuicao
```

---

## 🌍 Referências

- :contentReference[oaicite:0]{index=0}
- :contentReference[oaicite:1]{index=1}
- :contentReference[oaicite:2]{index=2}

---

## ⭐ Apoie o Projeto

Se este projeto te ajudou, deixe uma ⭐ no repositório!

---

## 📄 Licença

Este projeto está sob a licença **MIT**.

---

## 👨‍🏫 Autor

Desenvolvido para fins educacionais 💙  
**Professor & Desenvolvedor**

---

> 💬 *“Versionar não é apenas salvar código, é registrar a evolução do seu projeto.”* 🚀