#CUSTOMIZANDO PENTAHO


##LOGIN

Para customizar a tela de login o arquivo principal é o PUCLogin.jsp que fica no diretório /opt/pentaho/biserver-ce/tomcat/webapps/pentaho/jsp.

**Imagem do título principal**: title_text.png no diretório /opt/pentaho/biserver-ce/tomcat/webapps/pentaho-style/images/login

**Imagem do background**: bg_pentaho_default.png no diretório /opt/pentaho/biserver-ce/pentaho-solutions/system/common-ui/resources/themes/onyx/images

##PÁGINA INICIAL

Para customizar a tela inicial do pentaho o arquivo principal é o mantle.jsp que fica no diretório /opt/pentaho/biserver-ce/tomcat/webapps/pentaho/mantle, e para alguns lugares específicos, utiliza-se os arquivos:

**Imagem do canto superior direito**: logo.png no diretório /opt/pentaho/biserver-ce/tomcat/webapps/pentaho/mantle/themes/onyx/images

**Imagem do background**: (é a mesma da tela de login) bg_pentaho_default.png no diretório /opt/pentaho/biserver-ce/pentaho-solutions/system/common-ui/resources/themes/onyx/images
    
 
**Barra superior de ferramentas** (Abrir, Salvar, Editar, Saiku, CTool, Marketplace, Etc…): adicionar a propriedade “display:none;” na tag .mainToolbar-Wrapper{ do arquivo mantleOnyx.css no diretório /opt/pentaho/biserver-ce/tomcat/webapps/pentaho/mantle/themes/onyx

**Barra esquerda** (Browser e Arquivos): 
  
- Adicionar a propriedade “display:none;” na tag .mainToolbar-Wrapper{ do arquivo mantleOnyx.css no diretório /opt/pentaho/biserver-ce/tomcat/webapps/pentaho/mantle/themes/onyx

- Adicionar a propriedade “display:none;” na tag .puc-horizontal-split-panel .hsplitter

**Menu** (Arquivo – Visualizar – Ferramentas – Ajuda): adicionar a propriedade “display:none;” na tag .gwt-MenuBar { do arquivo Widgets.css no diretório /opt/pentaho/biserver-ce/tomcat/webapps/pentaho/mantle



*FONTE: [https://pentahobrazil.wordpress.com](https://pentahobrazil.wordpress.com/2014/06/12/customizacao-do-layout-das-paginas-principais-do-pentaho-tela-de-login-e-tela-inicial/)*


