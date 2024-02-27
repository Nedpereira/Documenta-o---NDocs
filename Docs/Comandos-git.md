# Git - Comandos Básicos e Para Que Servem
&nbsp;

## git init
&nbsp;

Uso: 
&nbsp;

`git init`
 Descrição: Inicializa um novo repositório Git local. Este comando cria um novo subdiretório chamado .git, que contém todos os arquivos necessários para o repositório. Deve ser usado no diretório raiz do seu projeto.
&nbsp;


## git clone
&nbsp;

Uso: 
&nbsp;

`git clone [URL]`

Descrição: Faz uma cópia local de um repositório que está hospedado em algum servidor (como GitHub, GitLab, etc.). Substitua [URL] pela URL do repositório que você deseja clonar.
&nbsp;


## git add
&nbsp;

Uso: 

`git add [arquivo] ou git add`

Descrição: Adiciona arquivos ao índice do Git. Use git add [arquivo] para adicionar um arquivo específico ou git add . para adicionar todos os arquivos modificados e novos (não os que estão para serem deletados).
&nbsp;


## git commit
&nbsp;

Uso: 
`git commit -m "mensagem de commit"`

Descrição: Salva suas alterações no repositório local. A mensagem de commit deve ser clara e descrever o que suas alterações fazem.
&nbsp;


## git status
&nbsp;

Uso: 
`git status`

Descrição: Mostra o estado atual do repositório, incluindo quais arquivos foram modificados ou estão preparados para o commit.
&nbsp;


## git push
&nbsp;

Uso: 
`git push origin [nome-da-branch]`

Descrição: Envia as alterações da sua branch local para a branch remota no servidor. Substitua [nome-da-branch] pelo nome da sua branch.
&nbsp;


## git pull
&nbsp;

Uso: 
`git pull origin [nome-da-branch]`

Descrição: Atualiza sua branch local com as alterações da branch remota correspondente. Basicamente, é uma combinação dos comandos git fetch e git merge.
&nbsp;


## git branch
&nbsp;

Uso: 
`git branch ou git branch [nome-da-branch]`

Descrição: Sem argumentos, lista todas as branches locais. Com um nome de branch, cria uma nova branch com esse nome.
&nbsp;


## git checkout
&nbsp;

Uso: 
`git checkout [nome-da-branch]`

Descrição: Muda para a branch especificada. Também pode ser usado para descartar mudanças em arquivos específicos.
&nbsp;


## git merge
&nbsp;

Uso: 
`git merge [nome-da-branch]`

Descrição: Une a branch especificada à branch atual. É usado para integrar as alterações de uma branch para outra.
&nbsp;


## git diff
&nbsp;

Uso: 
`git diff ou git diff [nome-do-arquivo]`

Descrição: Mostra as diferenças de conteúdo que não foram adicionadas ao índice. Pode ser usado para ver as diferenças em arquivos específicos.
&nbsp;


## git log
&nbsp;

Uso: 
`git log`

Descrição: Mostra o histórico de commits na branch atual. Muito útil para ver o que foi feito e por quem.
&nbsp;


## git restore
&nbsp;

Uso: 
`git restore [nome-do-arquivo] ou git restore --staged [nome-do-arquivo]`

Descrição: Desfaz alterações em arquivos. Sem --staged, descarta mudanças no diretório de trabalho. Com --staged, remove mudanças da área de preparação (stage), mantendo as alterações no diretório de trabalho.
&nbsp;


## git revert
&nbsp;

Uso: 
`git revert [commit]`

Descrição: Cria um novo commit que desfaz as alterações introduzidas por um commit anterior. Útil para reverter mudanças de maneira segura sem alterar o histórico de commits existente.
&nbsp;
