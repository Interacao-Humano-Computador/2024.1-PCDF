# Modelo GOMS: Registro de Ocorrência

## Introdução
Dentro do escopo do aprimoramento do site da Polícia Civil do Distrito Federal (PCDF), uma das funcionalidades prioritárias abordadas é o registro de ocorrências. Esta função desempenha um papel fundamental na facilitação da comunicação entre os cidadãos e as autoridades policiais, permitindo relatar eventos como roubos, furtos, acidentes e outras ocorrências relevantes.

Para este projeto, foi atribuída a responsabilidade de analisar o processo de registro de ocorrências à integrante [Rayene Almeida](https://github.com/rayenealmeida). Com o objetivo de compreender as interações dos usuários com essa funcionalidade, optamos por empregar uma das duas abordagens de análise: Análise Hierárquica de Tarefas (AHT) ou o modelo GOMS (Goals, Operators, Methods, and Selection rules).

## Análise Hierárquica de Tarefas (HTA)
A HTA é uma abordagem utilizada no design de interfaces de usuário e sistemas interativos, visando compreender como os usuários realizam tarefas complexas. No contexto do estudo de Barbosa e Silva (2010), a HTA é apresentada como uma técnica estruturada para analisar e representar hierarquicamente as tarefas executadas pelos usuários.
Os elementos-chave da HTA incluem:

1. Tarefas: São as atividades que os usuários realizam para alcançar um objetivo específico dentro de um sistema interativo.

2. Subtarefas: São as etapas menores que compõem uma tarefa maior. As subtarefas são organizadas hierarquicamente para representar a estrutura da atividade.

3. Objetivos: Representam os resultados que os usuários desejam alcançar ao realizar uma tarefa. Os objetivos são fundamentais para orientar a análise e garantir que as subtarefas estejam alinhadas com as necessidades dos usuários.

4. Planos: São as sequências de subtarefas e ações necessárias para atingir um objetivo específico. Os planos descrevem o fluxo de trabalho ou a sequência de atividades que os usuários devem seguir para realizar uma tarefa com sucesso.

## Modelo Goals, Operators, Methods, and Selection rules (GOMS)
O modelo GOMS, também abordado por Barbosa e Silva (2010), oferece uma estrutura sistemática para descrever as interações do usuário com um sistema. Este modelo divide a interação em quatro componentes: objetivos (Goals), operadores (Operators), métodos (Methods) e regras de seleção (Selection rules).

[Rayene Almeida](https://github.com/rayenealmeida) aplicará o modelo GOMS para analisar detalhadamente as ações cognitivas e motoras dos usuários ao realizar o registro de ocorrências no site da PCDF. A integrante identificará os objetivos que os usuários buscam alcançar ao usar essa funcionalidade, os operadores cognitivos e motores necessários para realizar as tarefas, os métodos sequenciais utilizados para atingir esses objetivos e as regras de seleção que orientam o comportamento do usuário diante de diferentes opções disponíveis na interface.

## Meta: Registrar uma ocorrência no site da PCDF

### Passos GOMS:

#### Objetivo (Goal):
- Identificar a necessidade de registrar uma ocorrência e decidir usar o site da PCDF para fazer isso.

#### Operadores (Operators):
- **Cognitivos:**
  - Selecionar a Opção de Registrar Ocorrência.
  - Ler e compreender as instruções fornecidas na página de registro de ocorrência.
  - Identificar os campos obrigatórios no formulário de registro.
  - Decidir quais informações são relevantes e devem ser fornecidas.

![Página inicial para ocorrência](../../assets/Analise_Requisitos/registraocorrencia.png)
<div align="center">
<p> Figura 1 - Página inicial do Registro de Ocorrência. Fonte: Site PCDF  </p> 
</div>

![Página Seleção do Crime](../../assets/Analise_Requisitos/registraocorrencia2.png)
<div align="center">
<p> Figura 2 - Seleção de Natureza para a Ocorrência. Fonte: Site PCDF  </p> 
</div>


- **Motoras:**
  - Mover o cursor para clicar nos campos de entrada do formulário.
  - Digitar as informações necessárias nos campos do formulário.
  - Clicar no botão de envio para submeter o formulário.


![Página de Formulário para Ocorrência](../../assets/Analise_Requisitos/registraocorrencia3.png)
<div align="center">
<p> Figura 3 - Formulário da Ocorrência. Fonte: Site PCDF  </p> 
</div>

#### Métodos (Methods):
- **Passos Sequenciais:**
  1. Acessar a seção de "Registro de Ocorrência" no site da PCDF.
  2. Ler as instruções e requisitos fornecidos.
  3. Preencher os campos obrigatórios do formulário (como dados pessoais, descrição da ocorrência, etc.).
  4. Revisar as informações inseridas para garantir que estejam corretas e completas.
  5. Clicar no botão "Enviar" para submeter a ocorrência.
- **Ações de Correção:**
  - Corrigir erros de digitação nos campos do formulário.
  - Revisar e editar as informações inseridas, se necessário, antes de enviar.

#### Regras de Seleção (Selection rules):
- Decidir quais informações incluir no relato da ocorrência com base nas instruções fornecidas e na relevância para o caso.
- Escolher entre digitar manualmente as informações ou usar recursos como copiar e colar, se aplicável e disponível.

## Bibliografia
> BARBOSA, S.D.J.; SILVA, B.S. Interação Humano-Computador. Editora Campus-Elsevier, 2010.

## Referências bibliograficas

Polícia Civil do Distrito Federal. Delegacia Eletrônica. Capturado em 18 de abril de 2024, de https://www.pcdf.df.gov.br/servicos/delegacia-eletronica.

 **Histórico de Versões**
 
| Versão |          Descrição              |     Autor(es)      |      Data      |   Revisor(es)     |    Data de revisão    |  
|:------:|:-------------------------------:|:--------------:|:--------------:|:-------------:|:---------------------:|
|  1.0   | Versão Inicial                    |   [Rayene Almeida](https://github.com/rayenealmeida)      |   18/04   |               |                    |
