<p align="center">
  <img src="https://github.com/DolphinDatabase/SGBD_Health/blob/Sprint-4/Images%20Sprint%204/Cards%20Sprint%204.png?w=400"height="400" width="700" />

</p>
<h1 align="center"> Story Card  </h1>  

![Badge](https://img.shields.io/badge/STATUS-CONCLU%C3%8DDO-green)


## Tabela de Conteúdos  


 * [Como executar a aplicação](#como-executar-a-aplicação)
 * [Descrição](#descrição)
 * [User story](#user-story)  
 * [Funcionalidades a serem desenvolvidas](#funcionalidades-a-serem-desenvolvidas)
 * [Ilustração das funcionalidades](#ilustração-das-funcionalidades)
 * [Benefícios](#benefícios)
 * [Gráfico de Burndown](#gráfico-de-burndown)  


## Como executar a aplicação

### Para executar a aplicação:
 
 1 - Documentação do tutorial acesse [aqui](https://github.com/DolphinDatabase/SGBD_Health/blob/Sprint-4/Documenta%C3%A7%C3%A3o%20sprint%204/MANUAL%20SGBDHEALTH%20.pdf)  
 2 - Arquivo executável da aplicação acesse [aqui](https://drive.google.com/file/d/1A1-pADaB350oxTsHmCnbaGrH6kgtUnUb/view)

## Descrição  
Nessa sprint apresentaremos os relatórios gerais gerados por cada servidor para monitoramento do status do SGBD.

<p align="justified"> 

  
## User story  
  
 
 | Como | Eu quero | Para que |
 | ------- | ------- | ------- |
 | Diretor da Necto System | que seja gerado relatórios gerais sobre cada servidor  | seja possível monitorar o status do SGBD. |
  
 
## Funcionalidades a serem desenvolvidas  
  
  
 ### 1. Relatório do Servidor 
 - Desenvolver um relatório diário que possua um TOP 5 do espaço ocupado pelos bancos dos servidores, das queries mais lentas, dos índicies que mais ocupam e das transações que    mais deram rollback.
  
 ### 2. Armazenar parâmetro de conexão
 - Armazenar os parâmetros de conexão que deveram ser informados através do SHELL.
  
 ### 3. Conexão ao Servidor 
 - Se conectar com o servidor através dos parâmetros de conexão inseridos no banco de dados da aplicação.
  
 ### 4. Desenvolver alertas por parâmetro
 - Alertar o usuário no e-mail informado dentro do arquivo de configuração, caso exista algum erro no servidor e deverá ser possível ajustar o parâmetro via "txt" que irá      acionar o alarme. Dentro do e-mail deverá ser anexado o relatório do dia.
  
  

  
 ## Ilustração das funcionalidades   
  
  ### Arquivo Parâmetro - Configurações do SGBDHealth    
  
   <p align="left">
  <img src="https://github.com/DolphinDatabase/SGBD_Health/blob/Sprint-4/Images%20Sprint%204/PARAMETRO.png"height="800" width="1100" /> 
   
  ### Relatório Diário do Servidor   
  
   <p align="left">
  <img src="https://github.com/DolphinDatabase/SGBD_Health/blob/Sprint-4/Images%20Sprint%204/RELATORIO.png"height="700" width="1100" /> 
     
  ### Alerta recebido por E-mail
     
   <p align="left">
    <img src="https://github.com/DolphinDatabase/SGBD_Health/blob/Sprint-4/Images%20Sprint%204/imagem_2021-11-23_194146.png"height="400" width="700" /> 
     
      
 #### Para acessar o vídeo de apresentação da aplicação clique [aqui](https://www.youtube.com/watch?v=IhyabBKAMbA)
     
 ## Benefícios
  
   Com o relatório é possível analisar de maneira geral a situação do servidor pois possui um TOP 5 das métricas coletadas, além disso o relatório é gerado diariamente contendo os momentos que a aplicação foi utilizada separada pela hora. Sendo assim quando um alarme que é ajustado conforme a necessidade do usuário for acionado, é possível analisar o erro através dos dados anteriores disponíveis. 
  
    
 ## Gráfico de Burndown
     
 <p align="left">
  <img src="https://github.com/DolphinDatabase/SGBD_Health/blob/Sprint-4/Images%20Sprint%204/burndown%204.png?w=200"height="500" width="1300" /> 
  


  
  

  
  
  
  
 
