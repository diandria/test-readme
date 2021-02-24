<div style="align:center" >
  <img style="margin-right: 20px;" height="70" src="https://uploads-ssl.webflow.com/5d0a9843727236542bc670a9/5e42efe340f4174501d1eaf7_LogoGentrop%404x.png" />
  <img height="50" src="https://logodownload.org/wp-content/uploads/2018/07/mrv-logo-6-1.png" />

</div>
<div style="text-align: center">
	<h3 style="font-size:40px; "><b>Nome do Sistema</b></h3>
  <p style="margin:0px; padding: 0px;">Breve descrição explicando o propósito do sistema!</p>
  <a href=""><b>Explore a api >></b></a>
</div>
<br>
<div style="margin:15px">
  <a href="">Squad</a> ·
  <a href="">Report Bug</a> ·
  <a href="">Request Feature</a>
</div>

#### Selos de qualidade

****
Indíce

1. [Sobre o Sistema](#sobre_o_sistema "Sobre o Sistema")
	- [Feito Com](#feito_com "Feito Com")
2. [Build Local](#build_local "Build Local")
	- [Pré-Requisitos](#pre_requisitos "Pré-Requisitos")
	- [Build and Run](#build_and_run "Build and Run")
3. [Arquitetura](#arquitetura "Arquitetura")
4. [DevOps Links](#devops_links "DevOps Links")
5. [Dados](#dados "Dados")

****

#### <a name="sobre_o_sistema"><b>Sobre o Sistema</b></a>
Descrição geral do sistema, explicando além do seu propósito como ele foi construído e as principais partes do mesmo.

Deverá conter o desenho técnico geral da arquitetura do sistema, se já existir uma versão atual e uma versão futura (as-is e to-be) as duas versões devem ser descritas aqui.

<img src="https://dev.azure.com/mrvengenharia/5b21f6b8-9cd8-4214-8ad3-570126e43cf8/_apis/git/repositories/faee5458-0a56-4b5f-94c7-62e27608ce51/Items?path=%2F.attachments%2Fcontrato_digital-6fd54cd4-a09f-4066-bd1b-da9d51bc48c0.png&download=false&resolveLfs=true&%24format=octetStream&api-version=5.0-preview.1&sanitize=true&versionDescriptor.version=wikiMaster" />

O diagrama deve ser feito nesta ferramenta , para manter a consistência dos diagramas na MRV. Além disso, diagrama como código tem uma série de vantagens como, por exemplo: fácil manutenção, rastreabilidade e controle de versão

Usar os nomes dos grupos de recurso e recursos que foram provisionados.

##### <a name="feito_com"><b>Feito com</b></a>
Deverá contar uma lista das tecnologias e frameworks utilizados no projeto. Ideal ter um link para o site ou repositório. Por exemplo:

- [Bootstrap](http://bootstrap.com "Bootstrap")
- [JQuery](http://jquery.com "JQuery")
- [Laravel](http://lavarel.com "Laravel")

****
#### <a name="build_local"><b>Build local</b></a>
Essa seção deve conter instruções claras e objetivas de como realizar o build local e rodar a aplicação apontada para um ambiente de DEV. Utilização de auxiliares como `MAKEFILE` ou um `build.sh` são encorajados.

Configurações de ambiente devem estar salvas no repositório a fim de evitar a necessidade de um appsettings.configou um env externo (em muitos repositórios da MRV atualmente é necessário entrar em contato com um squad para obter as configurações de ambiente e isso é uma falha).

##### <a name="pre_requisitos"><b>Pré-requisitos</b></a>
Este é um exemplo de como listar as coisas que você precisa para usar o sistema e como instalá-las

- npm
```shell
npm install npm@latest -g
```

##### <a name="build_and_run"><b>Build and run</b></a>
1.  Obtenha uma chave de API em https://example.com
2. Clone o repositório
```shell
git clone https://github.com/your_username_/Project-Name.git
```
3. Instale os pacotes NPM
```shell
npm install
```
4. Coloque sua chave no arquivo `config.js`
```shell
const API_KEY = 'ENTER YOUR API';
```
5. Execute a aplicação, o frontend deve abrir em `localhost:3057`
```shell
npm start dev
```

****
#### <a name="arquitetura"><b>Arquitetura</b></a>
| Informação  |  Valor  |
| :------------ | :------------ |
| ☁️ Nuvem/Datacenter  | Azure |
| 💵 Custo Mensal Estimado  |  R$ 2.500,00  |
| 🔑 Autenticação  |  Identity Server  |

****
#### <a name="devops_links"><b>DevOps links</b></a>
- [SonarQube Backend](http://sonaqube.com "SonarQube Backend")
- [SonarQube Frontend](http://sonarqube.com.br "SonarQube Frontend")
- [Application Insights](http://application.com "Application Insights")
- [YAML Pipeline](http://yamlpipeline.com "YAML Pipeline")

****
#### <a name="dados"><b>Dados</b></a>
Conter o [Entity Relationship Diagram - ERD](http://erd.com "Entity Relationship Diagram - ERD")  do sistema e tabela com as seguintes informações:

| Informação  |  Valor  |
| :------------ | :------------ |
| Localização do banco  | Azure |
| Nome do banco  |  MRV-Exemplo-DB  |
| Tecnologia |  Azure SQL Server  |

##### ERD
<img src="https://i.stack.imgur.com/Exar9.png" />

[SoS]: #
