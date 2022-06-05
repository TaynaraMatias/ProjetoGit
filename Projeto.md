O GitHub é uma plataforma onde podemos hospedar nossos projetos. Quando acessamos o repositório, encontramos nossos projetos feitos, cada um contendo seus respectivos arquivos de código. Dessa forma, podemos compartilhar nosso código em uma plataforma em que outros programadores também possuem acesso e podem visualizar seu código. Além de ter controle do versionamento do seu código, codificar em equipe permitindo alterar um arquivo, também é possível encontrar códigos de outras pessoas que podem te auxiliar de alguma forma. Hoje, o GitHub também está servindo como uma espécie de portifólio para empresas contratantes.
Branch – Se trata de uma ramificação que fazemos em nosso projeto, que fazemos a partir da linha cronológica principal (cronograma dos eventos presentes no código). Sua vantagem é nítida em trabalhos em equipe, onde cada um pode estar trabalhando em uma funcionalidade diferentes cada um na sua linha cronológica e posteriormente em sua linha principal.
Commit – É o post de alteração do projeto. O GitHub não vai atualizar automaticamente se alterarmos nosso código no computador, para isso precisamos do commit, para salvarmos as alterações feitas.
Merge – Seria a junção da branch alternativa, ramificada com a branch principal (linha cronológica principal). No momento em que fazemos o merge em um mesmo arquivo que está sendo alterado por pessoas diferentes, se as mesmas linhas não foram alteradas o merge funciona sem problemas, o único problema seria se alterassem a mesma linha de código.
Remote – Ele faz com que o repositório que temos em nossa máquina, seja acessível também na plataforma que utilizarmos, nesse caso, o GitHub.
Push – É utilizado para colocar o commit que fizemos no remote, no GitHub.
Pull – É o contrário do push, ele puxa o código que está no GitHub para nossa máquina.
Depois de instalar o Git em nossa máquina, acessamos o Git Bash, que funciona como um terminal do Git onde inserimos alguns comandos como os descritos acima e controlamos nossos repositórios.
O comando git –version nos mostra a versão do Git que está sendo usada, se instalado corretamente ele mostra a versão baixada, caso contrário, informará erro.
 
Readme.md – MD é uma extensão markdown, uma linguagem de marcação que normalmente utilizamos para escrever o readme, que é um arquivo presente em muitos projetos. O readme é toda a instrução presente em um projeto, é um arquivo de texto com informações sobre os arquivos em um repositório. 
Com a comanda git init é usado para inicializar um repositório Git vazio.
 
O master significa que já nos encontramos dentro da nossa branch principal. 
Com o git init é criada uma pasta dentro do nosso arquivo, que contem várias informações necessárias para o projeto funcionar.
O git add é responsável por mandar os arquivos para a área de staging. Ele diz ao Git que queremos incluir atualizações a um arquivo específico no próximo commit.
Git status – Nos mostra o status do seu repositório naquele momento. Ele mostra a staging area com todos os arquivos em cada uma das áreas e qual o estado de cada um deles.
 
Git commit -m (com o -m escrevemos um título para o commit).
O Git tem mudado a nomenclatura da branch principal (master) para main, para fazer essa alteração, de master para main, usamos o comando git branch -M “main”.
 
Git remote add origin link do repositório – Git é usado para iniciar um comando git, o remote, para conectar o repositório da máquina com o repositório do GitHub, add, para adicionar, origin, o nome que damos para o repositório do GitHub.
Git push -u origin main faz com que o repositório local, da máquina, seja “empurrado” para o repositório do GitHub que endereçamos.
 
Git add . faz com que todos os arquivos que estiverem disponíveis sejam enviados para a área de staging. Para alterarmos algo e subirmos para o Git, seguimos o mesmo esquema, git add, git commit e git push. As alterações apresentadas são em relação ao commit anterior e o atual.
Git checkout “nome da branch” é usado para criar uma nova branch, com o checkout saímos da branch que estamos e vamos para a nova branch ramificada. Para voltarmos a nossa branch principal, usamos o git checkout main. Git merge nome da branch com o git push origin main junta as duas branches, a principal e a ramificada.
Para acessarmos as alterações feitas no GitHub, colocamos cd e nome da pasta em que se encontra o repositório local, seguido de git pull.
Pull request – Solicita uma pessoa a fazer um pull de alguma alteração que fizemos.

