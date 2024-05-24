# README
Manual passo-a-passo para usar o GitHub nos pcs do Labin


 ## Gerenciador de Credenciais
 - Abra o gerenciador de credenciais, selecione Credenciais do Windows.
 <img src="./exemplo/img/image.png" alt="Imagem do Gerenciador de Credenciais">

 ---

 - Em `Credenciais do Windows`, selecione `Git:https://github.com`.
 <img src="./exemplo/img/image-01.png" alt="Imagem do Gerenciador de Credenciais com uma seleção em amarelo">

---

 - Remova a credencial selecionada.
 <img src="./exemplo/img/image-02.png" alt="Logo da Minha Empresa">

---

## Sua Identidade

Configurar seu nome de usuário e endereço de e-mail. Isto é importante porque cada commit usa esta informação, e ela é carimbada de forma imutável nos commits que você começa a criar:
```bash
 git config --global user.name "Fulano de Tal"
 git config --global user.email fulanodetal@exemplo.br
 ```

 ## Git Clone

 Você deseja clonar um repositório existente no git:
 ```bash
 git clone https://github.com/EderRosso/exerciciosJS.git
 ```
 ## Acessando o caminho do seu repositório local `PC`
- Abra o PowerShell, Git Bash, Prompt ou Terminal do pc para listar todos os diretórios digite:
```bash
    ls 
```
- Escolha o diretório onde está o repositório Git `Seu Projeto`.
```bash
    cd Documents/exerciciosJS
```
 ## Gravando Alterações em Seu Repositório

- Adicionar todas as atualizações feitas:
 ```bash
git add .
```
- Mostrar o estado atual das atualizações:
``` bash
git status
```
- Captura as modificações efetuadas e identifica sua modificação:
``` bash
git commit -m "Identificação da atualização"
```
- Envia os commits do repositório local para o repositório remoto:
``` bash
git push -u origin main
```

 ## Download Git Bash
 [Git Bash](https://git-scm.com/download).