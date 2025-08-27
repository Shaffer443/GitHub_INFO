Boa! 🚀 Isso é clássico do Git.
Se você quer que **um arquivo ou pasta não suba pro repositório**, você precisa usar o arquivo **`.gitignore`**.

### Passo a passo:

1. Na raiz do seu projeto (onde está a pasta `.git`), crie um arquivo chamado **`.gitignore`** (se já não existir).

   ```bash
   touch .gitignore
   ```

2. Dentro dele, coloque o que você não quer que seja versionado.
   Exemplos:

   ```gitignore
   # Ignorar arquivos de configuração
   config.json

   # Ignorar pastas
   /node_modules
   /venv

   # Ignorar qualquer .log
   *.log
   ```

3. Se você já **tinha feito commit** desse arquivo antes, o Git já está rastreando ele, então só o `.gitignore` não resolve.
   Nesse caso, você precisa **remover do controle de versão** (sem apagar do seu disco local):

   ```bash
   git rm --cached nome_do_arquivo
   ```

   Depois faz commit disso.

---

💡 **Resumo rápido**:

* Adiciona no `.gitignore` antes de dar commit → Git nunca vai rastrear.
* Se já comitou → precisa tirar do tracking com `git rm --cached`.

Quer que eu te mostre um **modelo de `.gitignore` pronto** para projetos comuns (Python, Node, etc.) ou prefere só um exemplo básico?
