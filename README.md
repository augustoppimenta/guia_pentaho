#Instalação

##Ambiente

O Pentaho é uma Suite que pode ser utilizanda em Windows, Linux e MacOS.

Para podermos utilizar o Pentaho, devemos ter o ambiente Java instalado e configurado. 

Então vamos lá...

1. Baixe o pacote JDK pelo [clicando aqui](http://www.oracle.com/technetwork/pt/java/javase/downloads/index.html) ou pelo terminal Linux.

2. Instale o pacote JDK

3. Configure as variáveis:
  
  * JAVA_HOME
  * PATH
  * CLASSPATH


##Pentaho BI Server


1. Acesse o diretório do Pentaho no [SouceForce](http://sourceforge.net/projects/pentaho/files/?source=navbar)

2. Baixe o BI Server (.zip para Windows ou tar.gz para Linux)

3. Descompacte o arquivo em uma pasta de sua preferência. (Dica: Não é recomendado a instalação do Pentaho no diretório *opt*, por problemas de permissão)

4. Inicie o Pentaho executando o arquivo **start-pentaho.sh** (Linux) ou o arquivo **start-pentaho.bat** (Windows) que se encontra na pasta *biserver-ce*

5. Se tudo ocorrer como previsto, você já pode acessar o BI Server pelo endereço [http://localhost:8080/pentaho](http://localhost:8080/pentaho) e realizar o login com o usuário adminstrador:

  * Usuário: joe
  * Senha: password

**Obs:** Para parar o servidor, basta executar o *stop-pentaho.sh* (Linux) ou *stop-pentaho.bat* (Windows)


##Pentaho Administration Console

O BI Server possui um Paniel Adminstrativo, onde é possível adicionar conexões, gerenciar contas dos usuários, etc.

1. Inicie o serviço executando o arquivo **start-pac.sh** (Linux) **start-pac.bat** (Windows) que se encontra na pasta *administration-console*

2. Se tudo ocorrer como previsto, você já pode acessar o Administration Console pelo endereço [http://localhost:8099](http://localhost:8099) e realizar o login com o usuário adminstrador:

  * Usuário: admin
  * Senha: password

**Obs:** Para parar o servidor, basta executar o *stop-pac.sh* (Linux) ou *stop-pac.bat* (Windows)


##Pentaho Data Integration

1. Acesse o diretório do Pentaho no [SouceForce](http://sourceforge.net/projects/pentaho/files/?source=navbar)

2. Baixe o Data Integration (.zip para Windows ou tar.gz para Linux)

3. Descompacte o arquivo em uma pasta de sua preferência. (Dica: Não é recomendado a instalação do Pentaho no diretório *opt*, por problemas de permissão). **Sugestão:** Colocar no mesmo diretório que se encontra o BI Server e o Administration Console.

4. Inicie o PDI executando o arquivo **spoon.sh** (Linux) ou *spoon.bat** (Windows)


##Schema Workbench

1. Acesse o diretório do Modrian no [SouceForce](http://sourceforge.net/projects/mondrian/files/?source=navbar)

2. Baixe o Schema Workbench (.zip para Windows ou tar.gz para Linux)

3. Descompacte o arquivo em uma pasta de sua preferência. (Dica: Não é recomendado a instalação do Pentaho no diretório *opt*, por problemas de permissão). **Sugestão:** Colocar no mesmo diretório que se encontra o BI Server, Administration Console e do Data Integration.

4. Inicie o Schema Workbench executando o arquivo **workbench.sh** (Linux) ou *workbench.bat** (Windows)



###Fim!
