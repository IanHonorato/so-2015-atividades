======================
Glossário de comandos
======================

:Disciplina: Fundamentos de Sistemas Operacionais
:Professor: Jurandy Soares
:Nome: Ian Honorato Pereira
:Matrícula: 20121144010257
:Data: 01/07/2015

cat
  Leitura de um arquivo.


cd
  Acessar Diretório ou somente voltar a um diretorio.
  cd /home/ianhonorato;

cowsay
  Animacao da Vaca, serve para enviar mensagens interligando com o write.
  cowsay -f

echo
  Imprime um valor
  echo %HOME%

env
  Cita as variáveis de ambiente e pode iniciar um ambiente vazio, exclui uma determinada variavel ambiente.
  -i; -u variavel;

exit
  Sair


help
  Ajuda
  help -l

HISTTIMEFORMAT="%d/%m/%y
  Modifica o formato do History, fazendo com que se adicione a hora em que o comando foi utilizado. 


hostname
  Exibe o nome da máquina


ifconfig
  Exibe configurações em uso da máquina. Visualizar os ips da nossa máquina, entre outras funções relacionadas com ips.


last
  Ultimos logs ao ssh ou servidor


lastb
  Guarda informações das ultimas tentativas mal sucedidas de logar no sistema.


ls
  Exibe os arquivos do diretorio atual


mkdir
  Criar diretorio, necessita de um argumento

nome="fulano"
  Atribui um valor a variável


passswd
  Altera a senha


pwd
  Indica o diretorio atual


set
  Exibe, define ou remove variáveis de ambiente do cmd.exe.

tree
  Mostra os processos em uso


tty
  Acesso em que você está.

vim
  Abre o arquivo e edita
  vim bin; vim bash; vim typespeed;

wait
  É um comando que faz uma pausa até que a execução de um processo de fundo terminou.


wall
  Envia uma mensagem a todos os usuários do sistema. Este comando faz a leitura de um arquivo ou entrada padrão e escreve o resultado em todos os terminais onde existem usuários conectados. Somente o usuário root pode utilizar este comando.
  wall /tmp/mensagem.txt, echo Teste de mensagem enviada a todos os usuários conectados ao sistema|wall


which
  which Exibe o caminho completo na hierarquia de diretórios para os comandos do sistema
”which firefox” para exibir o diretório onde se encontra o programa “firefox”.


while
 Cria um laço


who
  Itens logados


whoami
  Nome do seu usuario


    write
        Escrever

    wget
        baixa o codigo fonte
        gunzip || gzip: descompacta
        xvf desempacota
