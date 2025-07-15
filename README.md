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

## 🔁 5. Criar um Pull Request (PR)

Depois de criar uma branch e subir para o GitHub, siga os passos abaixo para abrir um **Pull Request**:

1. Acesse o repositório no GitHub.
2. Clique em **"Compare & pull request"** (isso aparece automaticamente quando você sobe uma branch nova).
3. Escreva um título e uma descrição explicando as mudanças feitas.
4. Clique em **"Create pull request"**.


## 🔀 6. Fazer Merge de uma Branch

Após abrir o **pull request** e ele for aprovado (ou se estiver trabalhando sozinho):

1. No GitHub, vá até a aba **"Pull requests"**.
2. Selecione o PR aberto.
3. Clique em **"Merge pull request"**.
4. Confirme clicando em **"Confirm merge"**.
5. (Opcional) Delete a branch clicando em **"Delete branch"**.


## 🧼 7. Excluir uma Branch Localmente

Após fazer o merge, você pode excluir a branch localmente com:

```bash
git branch -d nome-da-branch
```

Se a branch ainda não foi mesclada e você quiser forçar a exclusão:

```bash
git branch -D nome-da-branch
```

## 8. Utilizando Tags

Comando para criar as tags e manter uma versõa estável

```bash
git tag a- v1.0 -m "Versão 1.0"
```

Para subir a tag para o github

```bash
git push origin v1.0
```

