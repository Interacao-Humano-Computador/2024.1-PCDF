# Análise Hierárquica de Tarefas

## Introdução 
A Análise de Tarefas Hierárquica (HTA) é uma técnica de análise usada principalmente no design de interfaces de usuário e sistemas interativos. Ela se concentra em entender como os usuários realizam tarefas complexas, dividindo-as em etapas menores e mais gerenciáveis. Na HTA, a tarefa é decomposta em subtarefas menores, formando uma hierarquia que representa a estrutura da atividade. Cada subtarefa é detalhada até um nível em que possa ser facilmente compreendida e executada. Além disso, a análise pode incluir informações sobre os objetivos da tarefa, as condições em que é realizada, os recursos necessários e as possíveis interações com o ambiente e outros sistemas.

## Elementos de uma análise HTA


1. __Tarefas__: São as atividades que os usuários realizam para alcançar um objetivo específico dentro de um sistema interativo.

2. __Subtarefas__: São as etapas menores que compõem uma tarefa maior. As subtarefas são organizadas hierarquicamente para representar a estrutura da atividade.

3. __Objetivos__: Representam os resultados que os usuários desejam alcançar ao realizar uma tarefa. Os objetivos são fundamentais para orientar a análise e garantir que as subtarefas estejam alinhadas com as necessidades dos usuários.

4. __Planos__: São as sequências de subtarefas e ações necessárias para atingir um objetivo específico. Os planos descrevem o fluxo de trabalho ou a sequência de atividades que os usuários devem seguir para realizar uma tarefa com sucesso.

Como definido na figura 1.
### Tabela
![tabela](../../assets/Analise_Requisitos/índice.png)
<div align="center">
<p> Figura 1 - Tabela Elementos de um diagrama HTA. </p> 
</div>
Fonte :  BARBOSA, S.D.J.; SILVA, B.S. Interação Humano-Computador. Editora Campus-Elsevier, 2010.

## Funcionalidades Avaliadas pela HTA

    Tabela que mostra quais funcionalidades foram avaliadas pela HTA
 Funcionalidade    |    Integrante Responsável             |  
|:------:|:-------------------------------:|
|Pesquisar Procurados|Lara|  
| Solicitar Antecedentes Criminais | Renata |
| Validar Antecedentes Criminais | Joao |
| 197- Denúncia Online   | Giovana          |
| Solicitar Carteira de Identidade| Raissa
| Registrar Ocorrência | Rayene |
|Retrato Falado Online|Renata|

### Pesquisar Procurados

    Tabela HTA da pesquisa por pessoas procuradas pela polícia 

|         Objetivos/operações         | Problemas e recomendações|
|:-----------------------------------:|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 0. Pesquisar os nomes de procurados no registro policial 1>2  | **input**: formulário de busca, com nome ou apelido, sexo, crime, cidade/área, situação.<br> **Feedback**: busca retorna resultado ou se não encontrou nada<br> **Plano**: informar dados do indivíduo procurado e depois enviar mensagem de confirmação de busca.<br> **Recomendação**: permitir que o usuário tenha uma lista prévia e mais ampla de criminosos da região, podendo acessar mais detalhes de cada um deles.<br>|
| 1. Informar dados do indivíduo procurado 1+2  | **Plano**: nome ou apelido, sexo, crime, cidade/área, situação, de forma que pelo menos um destes inputs é necessário |
| 1.1 Informar nome ou apelido, sexo, crime, cidade/área, situação|
| 2.  Enviar formulário 1>2 | **Plano**: Clicar no botão "Pesquisar" (ou "Ver Todos")|
| 2.1 Clicar no botão "Pesquisar" | **Feedback**: Muda para uma página com os dados da certidão, indicando se tal certidão é válida ou não.<br> **Recomendação**: tornar a caixa de retorno da busca mais evidente com uma mensagem mais clara.<br>|

### Solicitar Antecedentes Criminais
Nessa tarefa o usuário pretende solicitar os antecedentes criminais no site da PCDF, foi analisada pela integrante  [Renata Quadros](https://github.com/Renatinha28) e feito o diagrama como monstrado na figura 2.

![tabela](../../assets/Analise_Requisitos/analise_Solicitar_Ant.png)
<div align="center">
<p> Figura 3- Diagrama de Analise de Solicitar Antecedentes Criminais. </p> 

</div>
Fonte: [Renata Quadros](https://github.com/Renatinha28) 

    Tabela que descreve Diagrama de Analise de Solicitar Antecedentes Criminais

|         Objetivos/operações         | Problemas e recomendações                                                                                                                                                                                      |
|:-----------------------------------:|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 0. Solicitar antecedentes criminais 1>2  | **input**: formulário de solicitação de antecedentes criminais com os dados pessoais.<br> **Feedback**: antecedentes criminais.<br> **Plano**: informar email, confirmar e depois preencher os dados e depois confirmar.<br> **Recomendação**: permitir que o usuário preencha o formulário online. |
| 1. Informar email 1>2                    | **Plano**: informar email pessoal                                                                                                                                                                               |
| 1.1. Informar código de autorização 1>2  | **Plano**: informar código enviado no email inserido                                                                                                                                                             |
| 2. Solicitação                           |                                                                                                                                                                                                                |
| 2.1. Informar dados pessoais 1+2         | **Plano**: informar nome, nome da mãe, nome do pai, email, CPF, estado civil, RG, data de expedição, órgão expedidor, UF, data de nascimento, UF, naturalidade, sexo, CNH, passaporte                                                                                           |
| 2.1.1. Informar detalhes pessoais        |                                                                                                                                                                                                                |
| 2.2. Informar endereço residencial 1+2   | **Plano**: Informar CEP, endereço, complemento, UF, cidade, telefone celular, telefone fixo                                                                                                                                                        |
| 2.2.1. Informar detalhes residenciais    |                                                                                                                                                                                                                |
| 2.3. Informar endereço comercial 1+2     | **Plano**: Informar órgão/empresa, profissão, cargo, telefone comercial, CEP, endereço, complemento, UF, cidade                                                                                                 |
| 2.3.1. Informar detalhes comerciais      |                                                                                                                                                                                                                |
| 2.4. Informar finalidade da solicitação  | **Plano**: informar a finalidade da solicitação de antecedentes criminais                                                                                                                                       |
| 3. Enviar respostas                      |                                                                                                                                                                                                                |
| 4. Recibo                                | **Ação**: conferir solicitação<br> **Recomendação**: após 3 dias úteis conferir solicitação            |                                                                


### Validar Antecedentes Criminais

    Tabela HTA da validação de antecedentes criminais 

|         Objetivos/operações         | Problemas e recomendações|
|:-----------------------------------:|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 0. Validar antecedentes criminais 1>2  | **input**: formulário de validação de antecedentes criminais com os dados da certidão.<br> **Feedback**: Muda para uma página com os dados da certidão, indicando se tal certidão é válida ou não<br> **Plano**: informar dados da certidão e responder o captcha, depois clicar em "Pesquisar".<br> |
| 1. Informar dados da certidão 1+2  | **Plano**: informar número da certidão, ano da certidão e data de nascimento na certidão |
| 1.1 Informar número da certidão, informar ano da certidão, informar data de nascimento na certidão|
| 1.2 Validar o CAPTCHA 1>2    | **Plano**: Responder o CAPTCHA, realizando a tarefa aleatória que ele exigir, se exigir |
| 1.2.1  Resolver o desafio do CAPTCHA |
| 2.  Enviar dados 1>2 | **Plano**: Clicar no botão "Pesquisar"|
| 2.1 Clicar no botão "Pesquisar" |


### 197- Denúncia Online

Nessa tarefa o usuário pretende fazer uma denúncia no site da PCDF, foi analisada pela integrante  [Giovana Barbosa](https://github.com/gio221), como monstrado na figura 3.
O obejtivo dessa analise é que qualuqer pessoa possa entender como fazer uma denúncia online no site da PCDF

![tabela](../../assets/Analise_Requisitos/analise_197online.png)
<div align="center">
<p> Figura 4- Diagrama de Analise da Denúncia Online. </p> 

</div>
Fonte :[Giovana Barbosa](https://github.com/gio221)  

    Tabela que descreve Diagrama de Analise da Denúncia Online

|     Objetivos/Operações      | Problemas e recomendações                                                                                                                                                                               |
| :--------------------------: | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 0. Entrar no site da PCDF  |  **input**: Digitar o endereço  do site da PCDF no navegador <br>**feedback**:Página inicial do site da PCDF <br> **plano**: Procurar pela aba serviços
|  1.Acessar "Serviços" |  **input**: Acessar a aba serviços <br>**feedback**:Página de serviços da PCDF <br> **plano**: Procurar pela 197-Denuncia Online                                                                                    |
|      2.Acessar "197 Denúncia"   | **input**: Acessar a aba de denuncia <br>**feedback**: usuário redirecionado para a página de denúncias<br> **plano**: procurar qual denúncia                                        |
|     2.1.Acessar "197-Denúnica-Online"      | **input**: Selecionar denuncia online<br>**feedback**: Vai ser redirecionado para a página de denuncias online <br> **plano**: selecionar qual denúncia vai fazer                                             |
|     2.1.1Acessar o tipo de denuncia   | **input**: Selecionar qual tipo de denuncia deseja.<br>**feedback**: vai ser redirecionado para a pagina de coletar infromações.<br>  **plano**: Preencher localização                  |
| 2.1.2 Informar localização | **input**: preencher localização da denuncia <br>**feedback**: usuário vai receber uma confirmação <br>                                                                                   | 
| 2.1.3 descrever o crime | **input**: preencher sobre a denuncia <br>**feedback**: usuário vai receber uma confirmação <br>                                                                                   | 
|       2.1.Fazer denuncia      | **input**: enviar denuncia<br>**feedback**: usuário deve receber uma confirmação de envio.<br>  |
| 2.2Acessar "Denúncia email"| **input**: acessar denuncia por email <br>**feedback**: usuário vai ser reedirecionado para o email da PCDF <br>                          **plano**: Preencher informações da denuncia no email                  |                                                         | 
|       2.1.Fazer denuncia      | **input**: enviar denuncia<br>**feedback**: usuário deve receber uma confirmação de envio.<br>  |
| 2.3Acessar "Denúncia 197-Whatssapp"| **input**: acessar denuncia por whatssap <br>**feedback**: usuário vai ser reedirecionado para o whatssap da PCDF <br>                          **plano**: Preencher informações da denuncia no whatssap                |                                                         | 
|       2.1.Fazer denuncia      | **input**: enviar denuncia<br>**feedback**: usuário deve receber uma confirmação de envio.<br>  |
|2.4Acessar "Denúncia ligação 197-opção (0)"| **input**: acessar denuncia por ligação <br>**feedback**: usuário vai ser reedirecionado para o telefone da PCDF <br>                          **plano**: Dar informações da denuncia para o atendente da PCDF             |                                                         | 
|       2.1.Fazer denuncia      | **input**: enviar denuncia<br>**feedback**: usuário deve receber uma confirmação de envio.<br>  |



### Solicitar Carteira de Identidade 
Nessa tabela o usuário quer Solicitar a Carteira de identidade
![Carteira de Identidade](../../assets/Analise_Requisitos/DiagramaCart.png)

<div align="center">
<p> Figura 5- Solicitar Carteira de Identidade  </p> 

</div>
Fonte :[Raissa](https://github.com/RaissaAndradeS)  

     Tabela que descreve Diagrama de Analise de Solicitar Carteira de Identidade 

|         Objetivos/operações         | Problemas e recomendações                                                                                                                                                                                      |
|:-----------------------------------:|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1.  Acessar o Site da PCDF | **input**: Digitar o endereço correto do site da PCDF no navegador ou clicar em um link fornecido. <br> **Feedback**: Página inicial do site da PCDF é exibida.<br> **Plano de Ação**: Abrir o navegador e digitar o endereço do site ou clicar em um link pré-fornecido.<br>  |
| 2.         Localizar o Serviço de Emissão de Carteira de Identidade.          | **Input**: Navegar pela aba de "Serviços" para encontrar a solicitação do serviço. <br> **Feedback**: O serviço é encontrado e acessado. <br> **Plano de Ação**: Navegar pelos aba para encontrar o serviço específico de emissão de carteira de identidade.|
| 3.  Informar-se sobre os Requisitos e Procedimentos |**Input**: Ler as informações fornecidas sobre os requisitos, documentos necessários e procedimentos para solicitar a carteira de identidade. <br> **Feedback**: Entendimento claro dos requisitos e procedimentos.<br> **Plano de Ação**: Ler atentamente as informações fornecidas no site sobre os documentos necessários e os passos a serem seguidos para solicitar a carteira de identidade.                                                                       |
| 4. Preencher o Formulário de Solicitação Online   | **Input**: Preencher o formulário online com as informações pessoais necessárias. <br> **Feedback**: Confirmação de envio bem-sucedido do formulário. <br>  **Plano de Ação**: Preencher corretamente o formulário online com os dados solicitados, incluindo informações pessoais e dados de contato.  |
| 5.Comparecer ao Posto de Atendimento | **Input**: Comparecer pessoalmente ao posto de atendimento na data e horário agendados, levando os documentos necessários. <br> **Feedback**: Verificação dos documentos e procedimentos para coleta de dados biométricos e fotográficos, se aplicável. <br> **Plano de Ação**: Comparecer ao posto de atendimento na data e horário agendados, levando todos os documentos solicitados. |
| 6. Acompanhar o Status da Solicitação   |  **Input**: Verificar o status da solicitação online. <br> **Feedback**: Atualizações sobre o andamento da solicitação. <br> **Plano de Ação**: Verificar regularmente o status da solicitação no site da PCDF.|            

### Registrar Ocorrência

|        Objetivos/operações                     | Problemas e Recomendações                                                                                                                                                                                                                                    |
|:----------------------------------------------:|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 0. Acessar a seção "Registro de Ocorrência"   | **Input:** Navegar até a seção "Delegacia Eletrônica" através do menu de serviços.<br> **Feedback:** Localizar o botão "Registrar Ocorrência" após rolar a página.<br> **Plano:** Navegar pelo menu de serviços até encontrar a seção relevante.<br> **Recomendação:** Melhorar a visibilidade do botão "Registrar Ocorrência". |
| 1. Escolher a natureza da ocorrência          | **Input:** Selecionar uma das opções de natureza de ocorrência listadas.<br> **Feedback:** Navegar para o formulário de registro correspondente à natureza selecionada.<br> **Plano:** Escolher a natureza da ocorrência com base na situação.                                                                             |
| 1.1. Informar dados pessoais                  | **Input:** Fornecer informações pessoais no formulário de registro.<br> **Feedback:** Conclusão bem-sucedida do formulário de registro.<br> **Plano:** Preencher todas as seções do formulário com informações precisas.                                                                                             |
| 1.2. Informar detalhes da ocorrência          | **Input:** Fornecer detalhes específicos sobre a ocorrência no formulário.<br> **Feedback:** Conclusão bem-sucedida dos detalhes da ocorrência.<br> **Plano:** Preencher todas as seções relevantes do formulário com informações precisas.                                                                 |
| 2. Revisar e enviar o formulário              | **Input:** Revisar as informações inseridas e enviar o formulário.<br> **Feedback:** Submissão bem-sucedida da ocorrência.<br> **Plano:** Revisar todas as informações fornecidas antes de enviar.<br> **Recomendação:** Incluir uma etapa de confirmação antes do envio final.                                               |
| 2.1. Receber confirmação da ocorrência        | **Input:** Receber confirmação da submissão da ocorrência.<br> **Feedback:** Receber uma confirmação por email ou na própria página.<br> **Plano:** Aguardar pela confirmação após o envio do formulário.                 

### Retrato Falado Online: Descreva e Identifique 
Nessa tarefa o usuário pretende fazer um retrato falado de forma online no site da PCDF, foi analisada pela integrante  [Renata Quadros](https://github.com/Renatinha28) e feito o diagrama como monstrado na figura 4.

![tabela](../../assets/Analise_Requisitos/analise_Retrato_Falado.png)
<div align="center">
<p> Figura 6- Diagrama de Analise de Retrato Falado. </p> 

</div>
Fonte: [Renata Quadros](https://github.com/Renatinha28) 

    Tabela que descreve Diagrama de Analise do Retrato Falado Online

|         Objetivos/operações         | Problemas e recomendações                                                                                                                                                                                      |
|:-----------------------------------:|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 0. Acessar "Denúncia Online" 1>2 | |
| 1. Selecionar "Retrato Falado Online" |  **Plano:** Identificar e selecionar a opção de "Retrato Falado Online" dentro da seção de "Denúncia Online". <br> **Feedback:** Página do Retrato Faldado Online é exibida |
| 2. Preencher o formulário de Retrato Falado Online 1+2 | **input**: formulário de retrato falado online.<br> **Feedback:** Confirmação do envio do formulário após o preenchimento. |
| 2.1. Informar dados pessoais 1+2 | **Plano**: informar nome, email, CPF |                                                               
| 2.2. Selecionar o tipo de denúncia 1+2 | **Plano**: informar o tipo de denúncia |
| 2.3. Descrever o incidente e o suspeito 1+2 | **Plano**: Descrever detalhadamente o incidente e as características do suspeito com base nas observações do denunciante. |
| 2.4. Criar o retrato falado do suspeito 1+2 | **input**: apertar o botão de criar avatar.<br> **Recomendação**: Fornecer uma interface de criação intuitiva e fácil de usar.|
| 2.4.1. Selecionar um avatar gerado 1>2 | **Plano**: selecionar um avatar dentre as 6 opções dadas pela IA |
| 2.4.2. Avaliar avatar selecionado 1+2 | **Plano**: avaliar o avatar selecionado descrever a fidelidade da imagem de acordo com a lembrança do suspeito |
| 3. Enviar a denúncia | |
| 4. Receber confirmação da denúncia | **Ação**: conferir solicitação e informações necessárias <br> **Feedback:** Confirmação da solicitação <br> **Recomendação**: Enviar uma confirmação clara da recepção da denúncia e informar sobre os próximos passos no processo de investigação, incluindo prazos para atualizações.  |



## Bibliografia
> BARBOSA, S.D.J.; SILVA, B.S. Interação Humano-Computador. Editora Campus-Elsevier, 2010.

## Histórico de Versões

    Tabela que descreve o Histórico de Versões
| Versão |          Descrição              |     Autor(es)      |      Data      |   Revisor(es)     |    Data de revisão    |  
|:------:|:-------------------------------:|:--------------:|:--------------:|:-------------:|:---------------------:|
|  1.0   | Criação do documento de hta                  |  [Giovana Barbosa](https://github.com/gio221)      |   18/04   |     [Renata Quadros](https://github.com/Renatinha28), [Raissa Andrade](https://github.com/RaissaAndradeS)   |        18/04     |
|  1.1   | Registro de Ocorrência                    |   [Rayene Almeida](https://github.com/rayenealmeida)      |   18/04   |      [Renata Quadros](https://github.com/Renatinha28), [Raissa Andrade](https://github.com/RaissaAndradeS)        |          18/04          |
|  1.2   | 197               |   [Giovana Barbosa](https://github.com/gio221)        |   18/04   |    [Renata Quadros](https://github.com/Renatinha28)   | 19/04               |
| 1.3 | Solicitar antecedentes criminais | [Renata Quadros](https://github.com/Renatinha28) | 19/04 | [Rayene Almeida](https://github.com/rayenealmeida) | 19/04 |
|1.4| Solicitação de Carteira de Identidade|[Raissa Andrade](https://github.com/RaissaAndradeS)|19/04| [Renata Quadros](https://github.com/Renatinha28) | 19/04 |
|1.5| Atualização do Índice|[Rayene Almeida](https://github.com/rayenealmeida)|09/05|  [Renata Quadros](https://github.com/Renatinha28) | 09/05  |
| 1.6 | Retrato falado online | [Renata Quadros](https://github.com/Renatinha28) | 09/05 | [Giovana Barbosa](https://github.com/gio221)   |10/05 |
| 1.7 | Adição do Diagrama de Carteira de Identidade | [Raissa Andrade](https://github.com/RaissaAndradeS) | 11/05 |    [Renata Quadros](https://github.com/Renatinha28), [Giovana Barbosa](https://github.com/gio221)   |11/05 |
| 1.8 | Correção na seção "Procurados"| [Lara Giuliana](https://github.com/gravelylara) | 21/05 |   [Renata Quadros](https://github.com/Renatinha28), [Giovana Barbosa](https://github.com/gio221), [Rayene Almeida](https://github.com/rayenealmeida)   |11/05 |
| 1.9 | Correção HTA de retrato falado | [Renata Quadros](https://github.com/Renatinha28) | 27/06 | |