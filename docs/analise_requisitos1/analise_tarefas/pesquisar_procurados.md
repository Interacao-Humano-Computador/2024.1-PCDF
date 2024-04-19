# Introdução
No site do PCDF escolhemos algumas funcionalidades, entre elas a de visualização, pesquisa e denúncia de _Procurados_ do Distrito Federal. A integrante  [Lara Giuliana](https://github.com/gravelylara) ficou responsável por essa funcionalidade. Para isso foi escolhida a Análise Hierárquica de Tarefas e a GOMS.

## Análise Hierárquica de Tarefas

A Análise de Tarefas Hierárquica (HTA) é uma técnica de análise usada principalmente no design de interfaces de usuário e sistemas interativos. Ela se concentra em entender como os usuários realizam tarefas complexas, dividindo-as em etapas menores e mais gerenciáveis. 

Assim, na funcionalidade de _Procurados_ da Polícia Civil do DF, os elementos de uma análise HTA seriam:

- Tarefa: Inserir nome completo de uma pessoa civil com passagem pela polícia
- Objetivo: Pesquisar procurados pela PCDF
- Plano (subbjetivo): Clicar no _input box_ da página, inserir caracteres e enviar o formulário para realizar a busca

## GOMS (Goals, Operators, Methods, And Selection Rules)

## Introdução 
O GOMS é um método para descrever uma tarefa e o conhecimento do usuário sobre
como realizá-la em termos de objetivos (goals), operadores (operators), métodos (methods)
e regras de seleção (selection rules).

Assim, na funcionalidade de _Procurados_ da PCDF, agora para realizar uma denúncia rápida de um crime, ainda na mesma página, os elementos seriam:

- Objetivos: denunciar delito
- Operadores: Inserir, via teclado, os seguintes dados:
    - Local
    - UF
    - Cidade
    - Bairro
    - Crimes
    - Histórico
    - O Autor é menor de idade? (Sim/Não)
- Métodos: Inserir dados via teclado, ou copiar essas informações de alguma outro local e colar na página presente.
- Regras de exeção: Enviar o formulário sem todas as partes preenchidas.

## Bibliografia
> BARBOSA, S.D.J.; SILVA, B.S. Interação Humano-Computador. Editora Campus-Elsevier, 2010.

## Histórico de Versões

| Versão |          Descrição              |     Autor(es)      |      Data      |   Revisor(es)     |    Data de revisão    |  
|:------:|:-------------------------------:|:--------------:|:--------------:|:-------------:|:---------------------:|
|  1.0   | Criação do documento Analise de Tarefas - Procurados                |  [Lara Giuliana](https://github.com/gravelylara)   |   19/04   |   ||
