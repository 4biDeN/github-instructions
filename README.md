# 📝 Instruções para Utilizar o GitHub Criado via [DIO.me](https://www.dio.me)

## 📁 1. Criar a Pasta no PC e o Repositório no GitHub

Após criar a pasta no seu computador e o repositório no GitHub, execute os comandos abaixo:

```bash
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:4biDeN/github-instructions.git
git push -u origin main
```

## 📥 2. Clonar um Repositório

Para clonar um repositório existente, utilize:

```bash
git clone <url-do-repositório>
```

Exemplo:

```bash
git clone git@github.com:4biDeN/github-instructions.git
```

## 💾 3. Comitar Alterações

Para salvar e enviar suas alterações para o repositório remoto:

```bash
git add .
git commit -m "comentário"
git push origin main
```
## 🌿 4. Criar uma Branch

Para criar a branch:

```bash
git branch teste-branch
```

Para alternar para a branch criada:

```bash
git checkout branch teste-branch
```

Para enviar a nova branch para o GitHub:

```bash
git push origin nome-da-branch
```