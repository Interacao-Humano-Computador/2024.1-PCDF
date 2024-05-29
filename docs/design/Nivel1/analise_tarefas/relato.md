# Introdução
Esse artefato tem como objetivo documentar os resultados que o grupo 4 de interação humano computador, obteve durante a avaliação das analise de tarefas, nesse artefato vai ser abordado todos os resultados obtidos nessa avaliação

# Metodologia
A avaliação do projeto foi conduzida através de entrevistas, storyboards e análise GOMS, permitindo uma compreensão das necessidades dos usuários. Utilizou-se acompanhamento presencial, observação direta, gravação das interações, questionários e análise de feedback para obter uma visão completa dos resultados.

# Participantes
Foi entrevistado 6 pessoas que aceitaram os termos de consentimento com 5 entrevistadores no total, pois um entrevistador entrevistou duas pessoas e duas funcionalidades diferentes, essas entrevista foram feitas presenciais. Neste Documento abordaremos as funcionalidades: Solicitar Antecedentes Criminais, 197-Denúncia Online, Retrato Falado

# Analise de Tarefas(GOMS)
## Solicitar Antecedentes Criminais 
Nessa tarefa o usuário pretende solicitar os seus antecedentes criminais pelo site do PCDF, foi analisada pela integrante [Renata Quadros](https://github.com/Renatinha28). Primeiro na página inicial como mostra na Figura 4, em seguida pede-se o código de verificação como mostra na Figura 5 e o preenchimento do formulário como mostra na figura 6.


![Página inicial para ocorrência](../../../assets/Analise_Requisitos/paginainicialsolicitarantecedentes.png)
<div align="center">
<p> Figura 2 - Página inicial de Antecedentes criminais. Fonte: Site PCDF  </p> 
</div>


![Página Seleção do Crime](../../../assets/Analise_Requisitos/codigosolicitarantecedentes.png)
<div align="center">
<p> Figura 3 - Código de verificação de Solicitação de Antecedentes. Fonte: Site PCDF  </p> 
</div>


![Página de Formulário para Ocorrência](../../../assets/Analise_Requisitos/formulariosolicitarantecedentes1.png)
<div align="center">
<p> Figura 4 - Formulário 1. Fonte: Site PCDF  </p> 
</div>


![Página de Formulário para Ocorrência](../../../assets/Analise_Requisitos/formulariosolicitarantecedentes2.png)
<div align="center">
<p> Figura 5 - Formulário 2. Fonte: Site PCDF  </p> 
</div>

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

 ### Aspéctos Éticos
Será feita a leitura dos do termo de consentimento e também será fornecido para o entrevistado ler, se ele preferir, no início da entrevista. Aspéctos Éticos disponível em: [Aspectos Éticos](../../../analise_requisitos1/aspectos_éticos.md).

### Questionário
- 1-Qual é seu nome? |Questão aberta |
- 2-Qual seu grau de experiência com tecnologias? | 
- 3-Você já utilizou o site da PCDF?  | 
- 4-Você acha essa funcionalidade importante? | 
- 5-Se a 4 for sim, por que você utilizaria essa funcionalidade?| 
- 6-O diagrama de tarefas corresponde de maneira precisa às suas expectativas sobre como o processo deve ser conduzido?  |  
- 7-Tem alguma parte que ficou confusa? | 
- 8-Se você pudesse mudar? O que mudaria no processo de tarefas?| 
- 9-De acordo com o diagrama, você o considera demorado de realizar as ações?|
- 10-Sugestões de melhorias?|

### Gravação

<p style="text-align: center"><iframe width="560" height="315" src="https://www.youtube.com/embed/frSFkkrWemk?si=O-rETQ07iw109nR6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></p>
<p style="text-align: center"><a href="https://youtu.be/frSFkkrWemk?si=O-rETQ07iw109nR6" target="blanket">Vídeo da Gravação</a></p>

### 197- Denúncia Online
Nessa tarefa o usuário pretende fazer uma denúncia no site da PCDF, foi analisada pela integrante  [Giovana Barbosa](https://github.com/gio221), como monstrado na figura 1. Ultilizando a CMN-GOMS

* GOAL 0: Fazer uma denuncia Online
    * GOAL 1: Entrar na parte de Denúncia Online
        * OP 1.1: Guiar o mouse para a aba de denuncia online
        * 0P 1.2: Pressionar o botão
    * GOAL 2: Selecionar a opção denuncia por meios de comunicação
        * OP 2.1: Guiar o mouse para a opção 'Denuncia de meios de comunicação'
        * OP 2.2: Pressionar o botão
        * OP 2.3: fazer a denuncia 
    * GOAL 3: Selecionar denucia Online
        * OP 3.1: Colocar as informações
        * OP 3.2: Clicar no botão denunciar 

# Retrato Falado Online: Descreva e Identifique
Nessa tarefa o usuário pretende fazer um retrato falado de forma online pelo site do PCDF, foi analisada pela integrante [Renata Quadros](https://github.com/Renatinha28). 

* GOAL 0: Acessar a funcionalidade de Denúncia Online:
    * METHOD 0.A: Navegar até o site da Polícia Civil do Distrito Federal (PCDF).
    
    (SEL. RULE: O usuário sabe que pode fazer denúncias online.)

* GOAL 1: Selecionar a opção de Retrato Falado Online:
    * METHOD 1.A: Identificar e clicar na seção "Denúncia Online".
        * OP. 1.A.1: Escanear visualmente a página inicial em busca da seção "Denúncia Online".
        * OP. 1.A.2: Clicar na seção identificada como "Denúncia Online".
    * METHOD 1.B: Escolher "Retrato Falado Online" dentre as opções disponíveis.
        * OP. 1.B.1: Procurar por opções de denúncia específicas, como "Retrato Falado Online".
        * OP. 1.B.2: Clicar na opção encontrada para selecioná-la.
    
    (SEL. RULE: O usuário procura a opção que corresponde à sua necessidade específica.)

* GOAL 2: Preencher o formulário de Retrato Falado Online:
    * METHOD 2.A: Fornecer os dados pessoais solicitados (nome, e-mail, CPF).
        * OP. 2.A.1: Digitar nome completo da pessoa. 
        * OP. 2.A.2: Digitar o CPF.
        * OP. 2.A.3: Digitar o e-mail.  
    * METHOD 2.B: Selecionar o tipo de denúncia (ex: Assalto/Roubo).
    * METHOD 2.C: Descrever detalhadamente o incidente e as características do suspeito.
        * OP. 2.C.1: Descrever detalhadamente o incidente. 
        * OP. 2.C.2: Descrever detalhadamente as características do suspeito.
    * METHOD 2.D: Criar o retrato falado do suspeito.
        * OP. 2.D.1: Apertar o botão de criar avatar. 
        * OP. 2.D.2: Selecionar um avatar criado. 
    * METHOD 2.E: Avaliar o avatar selecionado
        * OP. 2.E.1: Descrever a fidelidade do avatar de acordo com a lembrança do suspeito. 
    
    (SEL. RULE: O usuário segue o fluxo natural do formulário, preenchendo campos conforme necessário.)

* GOAL 3: Enviar a denúncia:
    * METHOD 3.A: Clicar no botão de envio após revisão completa dos dados fornecidos.

* GOAL 4: Receber confirmação da denúncia:
    * METHOD 4.A: Verificar a mensagem informativa e aguardar a confirmação por e-mail da recepção da denúncia.
    * METHOD 4.B: Aguardar atualizações dentro do prazo estipulado.

## Bibliografia
> BARBOSA, S.D.J.; SILVA, B.S. Interação Humano-Computador. Editora Campus-Elsevier, 2010.

## Referências bibliograficas

> Polícia Civil do Distrito Federal. Polícia Civil do Distrito Federal. Disponível em: [https://www.pcdf.df.gov.br/](https://www.pcdf.df.gov.br/). Acesso em: 14 abr 2024.

## Histórico de Versões

| Versão |          Descrição              |     Autor(es)      |      Data      |   Revisor(es)     |    Data de revisão    |  
|:------:|:-------------------------------:|:--------------:|:--------------:|:-------------:|:---------------------:|
|  1.0   | Criação do documento               |  [Giovana Barbosa](https://github.com/gio221)      | 29/05  |     |        |