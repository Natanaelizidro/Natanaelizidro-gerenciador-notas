# Natanaelizidro-gerenciador-notas
Sistema de Gerenciamento Acadêmico
Descrição do Projeto

Este projeto consiste em um sistema simples de gerenciamento acadêmico desenvolvido em Python. O objetivo da aplicação é realizar o cadastro de estudantes, armazenar suas notas e gerar relatórios contendo a média final e a situação de aprovação de cada aluno.

O sistema foi desenvolvido utilizando conceitos fundamentais de programação, como:

Listas e dicionários
Funções
Modularização
Estruturas de repetição
Condicionais
Boas práticas de documentação e padronização PEP 8
Estrutura dos Dados

Os estudantes são armazenados em uma lista de dicionários, contendo:

nome: nome do estudante
notas: lista de notas do estudante

Exemplo:

estudantes = [
    {
        "nome": "Ana",
        "notas": [8.0, 7.5, 9.0]
    }
]
Funcionalidades

O sistema possui as seguintes funcionalidades:

Cadastro de estudantes
Armazenamento das notas
Cálculo da média aritmética
Verificação de aprovação
Geração de relatório acadêmico
Pré-requisitos

Antes de executar o projeto, é necessário possuir:

Python 3 instalado na máquina

Para verificar se o Python está instalado, execute no terminal:

python --version

ou

python3 --version
Como Executar o Projeto
1. Salvar o arquivo

Salve o código principal em um arquivo chamado:

sistema_academico.py
2. Executar o sistema

Abra o terminal na pasta onde o arquivo foi salvo e execute:

python sistema_academico.py

ou

python3 sistema_academico.py
Exemplo de Execução

Ao executar o sistema, será exibido um relatório semelhante ao exemplo abaixo:

===== RELATÓRIO DOS ESTUDANTES =====

Nome: Ana
Média: 8.17
Situação: Aprovado
-----------------------------------

Nome: Carlos
Média: 6.50
Situação: Reprovado
-----------------------------------
Testes das Funções

Os testes podem ser realizados diretamente no código principal, criando listas de estudantes com diferentes notas.

Exemplo:

estudantes = [
    {
        "nome": "Mariana",
        "notas": [10.0, 9.5, 8.0]
    },
    {
        "nome": "João",
        "notas": [5.0, 6.0, 4.5]
    }
]

gerar_relatorio(estudantes)
Organização do Projeto

O sistema foi estruturado de forma modular, separando as responsabilidades em funções específicas:

calcular_media()
verificar_aprovacao()
gerar_relatorio()

Essa abordagem facilita:

manutenção do código
reutilização das funções
legibilidade
futuras expansões do sistema
Tecnologias Utilizadas
Linguagem Python 3
Terminal/Console para execução
