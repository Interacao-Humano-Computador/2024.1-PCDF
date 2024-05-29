# Introdução
Esse artefato tem como objetivo documentar os resultados que o grupo 4 de interação humano computador, obteve durante a avaliação das analise de tarefas, nesse artefato vai ser abordado todos os resultados obtidos nessa avaliação

# Metodologia
A avaliação do projeto foi conduzida através de entrevistas, storyboards e análise GOMS, permitindo uma compreensão das necessidades dos usuários. Utilizou-se acompanhamento presencial, observação direta, gravação das interações, questionários e análise de feedback para obter uma visão completa dos resultados.

# Participantes
Foi entrevistado 6 pessoas que aceitaram os termos de consentimento com 5 entrevistadores no total, pois um entrevistador entrevistou duas pessoas e duas funcionalidades diferentes, essas entrevista foram feitas presenciais. Neste Documento abordaremos as funcionalidades: Solicitar Antecedentes Criminais, 197-Denúncia Online, Retrato Falado

# Analise de Tarefas(GOMS)
### Solicitar Antecedentes Criminais 
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
