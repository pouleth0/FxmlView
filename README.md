📌
# 📦️ ⭐PFXVIEW⭐

Este repositório contém classes úteis para o desenvolvimento de aplicações
📦JavaFX-19-
📦Spring Boot 3.0.2  ou <= 2.2.0 inferiro:-

O Build do  FxmlView.jar- foi compactado no 📦Java17 - para que seja implementado em versões anteriores deve ser 
Build nas versões do seu projeto.

Classes
#
Aqui estão as classes contidas neste repositório:
#
📚 PFXVIEW
#
Essa classe permite carregar e manipular arquivos FXML.

<a href=""><img height= "35" src= "https://img.shields.io/badge/loadFXML()-1F2E3E?label=loadFXML&style=for-the-badge&logo=eclipseide&logoColor=00FF00"></a>
- Carrega o arquivo FXML especificado.
<a ><img height= "35" src= "https://img.shields.io/badge/create()-1F2E3E?label=create&style=for-the-badge&logo=eclipseide&logoColor=00FF00"></a>
- Cria um controlador FXML.
#
📚 ControllerFXML

Essa classe define um controlador de FXML e fornece acesso ao controlador pai e a outros controladores.

#
📚 FxmlView

📄 Controle da View FXML do seu JavaFX: gerada diretamente em cada nome dado às classes no pacote **ViewFXML(M.V.C: MODEL VIEW CONTROLLER)** 
com as anotação **@ViewFXML("Caminho/dor/view.fxml")** onde será considerado o caminho 
padrão para localizar o seu .fxml javaFX ou **@ViewFXML()** com anotações o controller irá 
considerar que o nome da **Classe; Explo:(JavaFXLogin.class) e seu diretório (src/main/com/projeto/JavaFXLogin.class) 
Será o mesmo Caminho da do arquivo ?.fxml;** neste caso será convertido que existe 
um pacote em **(resources/com/projeto/JavaFXLogin.fxml),** lembrando que os caminhos lá em resources; precisam existir (resources/com/projeto/)
e dentro do "resources/com/projeto/" adicionar seu arquivo usando o mesmo nome da 
classe (JavaFXLogin.fxml), desta forma a anotação  @ViewFXML(), apenas sem ("???"). ira fazer à conversão, 
ira considerar que o caminho do pacote será o mesmo da classe, lá no "resources".
Métodos:

<a href=""><img height= "35" src= "https://img.shields.io/badge/getFXMLLoader()-1F2E3E?label=getFXMLLoader&style=for-the-badge&logo=eclipseide&logoColor=00FF00"></a>
 - Retorna o carregador FXML.
<a href=""><img height= "35" src= "https://img.shields.io/badge/setParentController()-1F2E3E?label=setParentController&style=for-the-badge&logo=eclipseide&logoColor=00FF00"></a>
- Define o controlador pai.
#
📚 ViewFXML

Essa classe define uma visualização de FXML e permite que ela seja incorporada a uma cena.

Métodos:

<a href=""><img height= "35" src= "https://img.shields.io/badge/getRoot()-1F2E3E?label=getRoot&style=for-the-badge&logo=eclipseide&logoColor=00FF00"></a>
 - Retorna a raiz da visualização FXML.
<a href=""><img height= "35" src= "https://img.shields.io/badge/getController()-1F2E3E?label=getController&style=for-the-badge&logo=eclipseide&logoColor=00FF00"></a>
 - Retorna o controlador FXML.
#
📚 LoaderFXMLP

Essa classe fornece métodos para carregar arquivos FXML e criar controladores FXML.

Métodos:

<a href=""><img height= "35" src= "https://img.shields.io/badge/loadFXML()-1F2E3E?label=loadFXML&style=for-the-badge&logo=eclipseide&logoColor=00FF00"></a>
 - Carrega o arquivo FXML especificado.
<a href=""><img height= "35" src= "https://img.shields.io/badge/createController()-1F2E3E?label=createController&style=for-the-badge&logo=eclipseide&logoColor=00FF00"></a>
- Cria um controlador FXML.

#
🧱 *ModelFXMLP*🎉

*Essa classe fornece métodos para carregar arquivos FXML e criar controladores FXML.*
<a href=""><img height= "35" src= "https://img.shields.io/badge/loadFXML()-1F2E3E?label=loadFXML&style=for-the-badge&logo=eclipseide&logoColor=00FF00"></a>
*Em Deploy*
Métodos:

Links úteis
[JavaFX][https://openjfx.io/]
[Spring Framework][https://spring.io/]
#
