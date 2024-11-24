# Contribuindo com nosso Repositório no GitHub

## 1. Fazer o Fork do Repositório
- No repositório original (que você quer contribuir), clique no botão **"Fork"** na parte superior direita do GitHub.
- Isso cria uma cópia do repositório no seu perfil GitHub.

## 2. Clonar o Repositório Forkado
Após o fork, você precisa clonar o repositório para sua máquina local. Use o comando:

```bash
git clone https://github.com/seu-usuario/seu-fork.git
```
- Substitua seu-usuario pelo nome do seu perfil GitHub.

## 3. Criar uma Nova Branch

- Antes de começar a trabalhar, crie uma branch separada para suas alterações:

```bash
Copiar código
git checkout -b minha-branch
```
## 4. Fazer as Alterações
- Realize as alterações no código em sua máquina local.

## 5. Commitar e Subir as Alterações

Salve as mudanças no repositório local com:

```bash
Comandos abaixo:

git add .
git commit -m "Descrição das alterações"

```
Suba as alterações para o seu repositório no GitHub:

```bash
Comando abaixo:

git push origin minha-branch

```

## 6. Criar a Pull Request
- No GitHub, vá até o repositório original (aquele do qual você fez o fork).
- Clique em Pull Requests e depois em New Pull Request.
- Escolha sua branch no repositório forkado como base para enviar a PR.

## Resumindo
 - Após criar a PR, os responsáveis pelo repositório original analisarão suas alterações e poderão aprová-las ou pedir ajustes.

## Apos Aprovação faça o pull


- Sim! Após enviar suas alterações (push) na branch que você criou e criar a Pull Request (PR), se quiser fazer o pull para atualizar o seu repositório local com as mudanças do repositório original ou sincronizar sua branch principal (main), você precisa voltar para a branch main antes de fazer o pull.

- Passos para Fazer o Pull:

Volte para a branch main: Primeiro, volte para a branch principal (geralmente chamada de main ou master):

```bash
Copiar código

git checkout main

```
- Sincronize com o repositório original (upstream):
- Baixe as alterações do repositório original (se ainda não configurou o upstream, veja o comando abaixo):

```bash
Copiar código
git remote add upstream https://github.com/Programmer-Girls/progirls
```
```bash
Copiar código

git fetch upstream
```
Mescle as mudanças na branch main: Atualize sua branch main local com as alterações do repositório original:

```bash
Copiar código

git merge upstream/main
```
Atualize o seu fork no GitHub: Suba as alterações da sua branch main para o repositório forkado no GitHub:

```bash
Copiar código

git push origin main
```


## Veja o vídeo explicativo abaixo:

 [![Título do Vídeo](https://img.youtube.com/vi/q-QTbNu8Ybc/maxresdefault.jpg)](https://www.youtube.com/watch?v=q-QTbNu8Ybc)
