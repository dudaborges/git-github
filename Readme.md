Md é um arquivo presente em muitos projetos, porque ele é a instrução e informação do projeto que não estará presente no código.
 
Esse projeto é para aprender a usar o Git e Gihub.
 
O que é Git?
É um sistema de versionamento de arquivo, ele gerencia todas as diferentes versões de um código. Facilita um trabalho em grupo, já que desta forma é possível trabalhar no código ao mesmo tempo que o colega. É preciso baixar essa ferramenta.
 
O que é Github?
É uma plataforma para hospedar arquivos, para ter o controle de versionamento (de todas as versões/alterações do código. Ele trabalha com repositórios, que são pastas para armazenar projetos.
 
O que é branch?
É uma ramificação de um projeto. No Github, é possível desenvolver uma única linha cronológica e também adicionar ramificações. As ramificações são alterações a parte da linha cronológica principal. Depois que a ramificação estiver pronta, você pode adicioná-la na linha principal. Desta forma é possível fazer alterações mantendo o código principal, caso de algum erro.
 
O que é Commitar?
É postar as alterações feitas no projeto.
 
O que é Merge?
É a junção das branch com a linha principal. Assim é possível alterar o mesmo arquivo que outra pessoa e ambas as alterações ficarem salvas. Não é possível dar merge, se as duas alterações estiverem na mesma linha.
 
O que é Remote?
Faz a ligação do repositório que está na sua máquina (a pasta) para o repositório do Github.
 
O que é Push?
Ele é utilizado para colocar o commit que você fez no remote, ou seja no Github. Push é literalmente empurrar. Não adianta só commitar, precisa dar o push para atualizar no Github
 
O que é Pull?
É para puxar o repositório que está no github para sua máquina.
 
Git e Github na Prática!

Passo a passo detalhado:
1. git config –global user.email “you@gmail.com”: para se identificar
2. git config –global user.name “yourname”: para se identificar
3. git init: para criar um repositório git vazio. “Initialized empty Git repository”. O “(master)” significa que estamos dentro da linha cronológica principal, a branch master.
4. git add NomedoArquivo.tipoDoArquivo: É para adicionar o arquivo na área de ustage para quando ele estiver pronto comittar.
5. git status: para verificar se o arquivo foi adicionado. “new file: NomedoArquivo.Tipo”
6. git commit -m “nome do commit”: para commitar
7. git branch -M “main”: Para renomear a branch “master” para “main”, caso necessário, já que algumas empresas estão adotando esse nome.
8. git remote add origin https://github.com/dudaborges/ProjetoGit.git: para fazer a ligação do repositório da máquina com o github.

Básico:
1. git init
2. git add readme.md / git add . (para add todos os arquivos)
3. commit -m “meu primeiro commit”
4. git branch -m ‘main’
5. git remote add origin https://github.com/dudaborges/ProjetoGit.git
6. git push -u origin ‘main’ / git push origin nomeDaBranch
 
Não é preciso dar remote mais de uma vez. Assim que feito a ligação do repositório, não é necessário criar de novo.
 
"clear" para apagar
 
Para criar uma branch: git checkout -b "nome"
Desta forma, toda as alterações serão na branch criada, fora da branch principal (cuidado para não alterar a mesma linha da branch main, caso for dar merge depois)
 
Para voltar para a branch principal: git checkout main
Para voltar para alguma branch: git checkout nomeDaBrach

Para fazer a merge: git merge novo-botao (dentro da main/master)