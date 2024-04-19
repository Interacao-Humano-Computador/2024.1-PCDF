# GOMS (Goals, Operators, Methods, And Selection Rules)

## Introdução 
O GOMS é um método para descrever uma tarefa e o conhecimento do usuário sobre
como realizá-la em termos de objetivos (goals), operadores (operators), métodos (methods)
e regras de seleção (selection rules).

 * Os objetivos representam o que o usuário quer realizar utilizando o software
 * Operadores: são as ações cognitivas ou físicas que o sistema permite que o usuário execute, como inserir dados via teclado
 * Os métodos são sequências bem conhecidas de subobjetivos e operadores que permitem atingir um objetivo maior.
 * Regras de exeção: Referem-se a tomada de decisão por parte do usuário diante da possibilidade de possuir mais de um
 método para utilizar


## GOMS-KLM
 O KLM é a técnica mais simples de GOMS, limitada a um conjunto predefinido de operadores primitivos descrito na tabela 1

![KLM-GOMS](../../assets/Analise_Requisitos/klm-goms.png)<div>
<p>Tabela 1 </p>
</div>

## Funcionalidades Avaliadas pela GOMS
     Tabela que monstra quais funcionalidades foram avaliadas pela HTA
 Funcionalidade    |    Integrante Responsável             |  
|:------:|:-------------------------------:|
| Registro de Ocorrência   | Rayene        |
| 197- Denúncia Online   | Giovana          |  
| Solicitar Antecedentes Criminais | Renata |

# Registro de Ocorrência

## Modelo Goals, Operators, Methods, and Selection rules (GOMS)

[Rayene Almeida](https://github.com/rayenealmeida) aplicará o método GOMS no modelo CMN para analisar detalhadamente as ações cognitivas e motoras dos usuários ao realizar o registro de ocorrências no site da PCDF. A integrante identificará os objetivos que os usuários buscam alcançar ao usar essa funcionalidade, os operadores cognitivos e motores necessários para realizar as tarefas, os métodos sequenciais utilizados para atingir esses objetivos e as regras de seleção que orientam o comportamento do usuário diante de diferentes opções disponíveis na interface.

## Meta: Registrar uma ocorrência no site da PCDF

### Passos GOMS:

* GOAL 0: Registrar uma Ocorrência
    * GOAL 1: Acessar a seção de "Registro de Ocorrência" no site da PCDF
        * OP 1.1: Guiar o mouse para a seção "Delegacia Eletrônica"
        * OP 1.2: Pressionar o botão para acessar a seção
    * GOAL 2: Ler as instruções e requisitos fornecidos
        * OP 2.1: Ler as instruções na página de registro de ocorrência
        * OP 2.2: Selecionar a natureza da ocorrência
    * GOAL 3: Preencher o formulário de registro
        * OP 3.1: Identificar os campos obrigatórios no formulário de registro
            * Cognitivos:
                * Identificar os campos obrigatórios
        * OP 3.2: Decidir quais informações são relevantes e devem ser fornecidas
            * Cognitivos:
                * Decidir quais informações são necessárias para a ocorrência
        * OP 3.3: Mover o cursor para clicar nos campos de entrada do formulário
            * Motoras:
                * Mover o cursor para os campos de entrada
        * OP 3.4: Digitar as informações necessárias nos campos do formulário
            * Motoras:
                * Digitar as informações necessárias
    * GOAL 4: Revisar e enviar o formulário de registro
        * OP 4.1: Revisar as informações inseridas para garantir que estejam corretas e completas
            * Cognitivos:
                * Revisar as informações inseridas
        * OP 4.2: Clicar no botão "Enviar" para submeter a ocorrência
            * Motoras:
                * Mover o cursor para clicar no botão de envio

![Página inicial para ocorrência](../../assets/Analise_Requisitos/registraocorrencia.png)
<div align="center">
<p> Figura 1 - Página inicial do Registro de Ocorrência. Fonte: Site PCDF  </p> 
</div>

![Página Seleção do Crime](../../assets/Analise_Requisitos/registraocorrencia2.png)
<div align="center">
<p> Figura 2 - Seleção de Natureza para a Ocorrência. Fonte: Site PCDF  </p> 
</div>


![Página de Formulário para Ocorrência](../../assets/Analise_Requisitos/registraocorrencia3.png)
<div align="center">
<p> Figura 3 - Formulário da Ocorrência. Fonte: Site PCDF  </p> 
</div>




# 197- Denúncia Online
Nessa tarefa o usuário pretende fazer uma denúncia no site da PCDF, foi analisada pela integrante  [Giovana Barbosa](https://github.com/gio221), como monstrado na figura 1. Ultilizando a CMN-GOMS

* GOAL 0: Fazer Denúncia
    * GOAL 1: Denúncia Online
        * OP 1.1: Guiar o mouse para a aba de denuncia online
        * 0P 1.2: Pressionar o botão
    * GOAL 2: Selecionar a opção denuncia por meios de comunicação
        * OP 2.1: Guiar o mouse para a opção 'Denuncia de meios de comunicação'
        * OP 2.2: Pressionar o botão
    * GOAL 3: Fazer Denuncia
        * OP 3.1: Colocar as informações
        * OP 3.2: Clicar no botão denunciar 

# Solicitar Antecedentes Criminais 
* GOAL 0: Descobrir se a pessoa possui antecedentes criminais.
  * GOAL 1: Solicitar os antecedentes criminais.
    * METHOD 1.A: Acessar o sistema de solicitação de antecedentes criminais da PCDF.

    (SEL. RULE: O usuário possui acesso ao sistema e sabe como navegar nele.)

    * METHOD 1.B: Entrar em contato com a Polícia Civil do Distrito Federal por telefone ou e-mail para obter instruções sobre como solicitar os antecedentes criminais.

    (SEL.RULE: O usuário não está familiarizado com o sistema online ou não possui acesso a ele.)

  * GOAL 2: Preencher corretamente os dados necessários para a solicitação de antecedentes criminais.
    * METHOD 2.A: Inserir os dados pessoais da pessoa para quem os antecedentes criminais estão sendo solicitados.

    (SEL. RULE: O usuário possui os dados pessoais da pessoa.)

      * OP. 2.A.1: Digitar o nome completo da pessoa.
      * OP. 2.A.2: Inserir o nome completo dos pais da pessoa (se aplicável).
      * OP. 2.A.3: Preencher o CPF (Cadastro de Pessoa Física) da pessoa.
      * OP. 2.A.4: Fornecer o RG (Registro Geral) da pessoa.
      * OP. 2.A.5: Indicar a data de nascimento da pessoa.
      * OP. 2.A.6: Especificar a naturalidade (cidade e estado de nascimento) da pessoa.
      * OP. 2.A.7: Selecionar o sexo da pessoa.
      * OP. 2.A.8: Informar o estado civil da pessoa.
      * OP. 2.A.9: Se aplicável, inserir o número da CNH (Carteira Nacional de Habilitação) da pessoa.
      * OP. 2.A.10: Se aplicável, fornecer o número do passaporte da pessoa.
      * OP. 2.A.11: Inserir o endereço residencial completo da pessoa.
      * OP. 2.A.12: Se aplicável, incluir o endereço comercial completo da pessoa.
      * OP. 2.A.13: Indicar o CEP (Código de Endereçamento Postal) tanto do endereço residencial quanto do endereço comercial.

    * METHOD 2.B: Revisar os dados fornecidos para garantir que estejam corretos e completos.

    (SEL. RULE: O usuário deseja evitar erros na solicitação.)

      * OP. 2.B.1: Verificar se todos os campos foram preenchidos corretamente.
      * OP. 2.B.2: Revisar se não há erros de digitação nos dados fornecidos.
      * OP. 2.B.3: Confirmar se os dados estão atualizados e correspondem à pessoa correta.
      * OP. 2.B.4: Corrigir qualquer informação incorreta ou incompleta identificada durante a revisão.
  * GOAL 3: Confirmar o envio da solicitação.
    * METHOD 3.A: Enviar a solicitação através do sistema online e aguardar a confirmação.

    (SEL. RULE: O usuário tem acesso à internet e confia na eficácia do sistema.)

    * METHOD 3.B: Entrar em contato com a PCDF para confirmar o recebimento da solicitação.

    (SEL. RULE: O usuário prefere confirmar pessoalmente.)

  * GOAL 4: Receber um código de acompanhamento da solicitação.
    * METHOD 4.A: Aguardar o recebimento do código de acompanhamento através do e-mail fornecido na solicitação.

    (SEL. RULE: O usuário confia na eficácia do sistema de envio de e-mails.)

    * METHOD 4.B: Entrar em contato com a PCDF para solicitar o código de acompanhamento, caso não seja recebido dentro do prazo esperado.

    (SEL.RULE: O usuário prefere confirmar pessoalmente.)

## Agendamento de Carteira de Identidade 

Essa atividade tem como objetivo os usuários ao acessar a funcionalidade de marcação de carteira de identidade é agendar um horário para emissão ou renovação do documento de identidade. Feita por [Raissa Andrade](https://github.com/RaissaAndradeS).

* GOAL 0: Solicitar Carteira de Identidade.
* GOAL 1: entrar no site da PCDF.
    * OP 1.1: Navegar por serviços.
    * OP 1.1: Clicar em carteira de identidade.
    * OP 1.1: Solicitar CIN.
    * OP 1.1: Li e quero agendar a CIN.
* GOAL 2: Escolher serviço solicitado e unidade de atendimento.
    * OP 1.1: Preencher formulário online. 
    * OP 1.1: Aguardar confirmação.

Regras de seleção nesse caso, pode incluir a seguinte situação, caso o usuário esteja com pressa ou necessitar de um agendamento rápido, ele pode optar por procurar por horários disponíveis nos próximos dias.



## Bibliografia
> BARBOSA, S.D.J.; SILVA, B.S. Interação Humano-Computador. Editora Campus-Elsevier, 2010.

## Referências bibliograficas

>Polícia Civil do Distrito Federal. Delegacia Eletrônica. Capturado em 18 de abril de 2024, de https://www.pcdf.df.gov.br/servicos/delegacia-eletronica.

## Histórico de Versões

| Versão |          Descrição              |     Autor(es)      |      Data      |   Revisor(es)     |    Data de revisão    |  
|:------:|:-------------------------------:|:--------------:|:--------------:|:-------------:|:---------------------:|
|  1.0   | Criação do documento de hta                  |  [Giovana Barbosa](https://github.com/gio221)      |   18/04   |        |             |
|  1.1   | Registro de Ocorrência                    |   [Rayene Almeida](https://github.com/rayenealmeida)      |   18/04   |               |                    |
|  1.2   | 197               |   [Giovana Barbosa](https://github.com/gio221)        |   18/04   |   [Renata Quadros](https://github.com/Renatinha28)    |  19/04              |
| 1.3 | Solicitar antecedentes criminais | [Renata Quadros](https://github.com/Renatinha28) | 19/04 | | |
|1.4| Solicitar Carteira de Identidade| [Raissa Andrade](https://github.com/RaissaAndradeS)| 19/04|||