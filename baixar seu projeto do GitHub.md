Para baixar seu projeto do GitHub no trabalho e continuar de onde parou, siga estes passos:

### 1️⃣ **Clonar o repositório** (se ainda não tiver o projeto no trabalho)
Abra o terminal (ou Git Bash) e rode:
```bash
git clone https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git
```
Isso criará uma pasta com os arquivos do projeto.

### 2️⃣ **Entrar no diretório do projeto**
```bash
cd NOME-DO-REPOSITORIO
```

### 3️⃣ **Baixar as últimas atualizações da `main`**
```bash
git pull origin main
```
Isso garante que você está com a versão mais recente.

### 4️⃣ **Criar uma nova branch (opcional)**
Se quiser trabalhar sem alterar diretamente a `main`, crie uma branch para suas mudanças:
```bash
git checkout -b minha-nova-branch
```

### 5️⃣ **Fazer as alterações no código**
Edite seus arquivos normalmente.

### 6️⃣ **Adicionar e commitar suas mudanças**
```bash
git add .
git commit -m "Descrição das mudanças de hoje"
```

### 7️⃣ **Enviar as mudanças para o GitHub**
Se estiver na `main`, basta:
```bash
git push origin main
```
Se criou uma branch nova, envie com:
```bash
git push origin minha-nova-branch
```
Depois, se necessário, abra um Pull Request no GitHub para mesclar na `main`.

Pronto! Agora seu código atualizado estará no GitHub para continuar trabalhando em casa depois. 🚀
