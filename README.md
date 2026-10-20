# HelpEnem! – Diagnóstico de Habilidades Escolares para o ENEM

Projeto de **Projeto de Tecnologia da Informação e Comunicação (PTIC)** do curso Técnico em Desenvolvimento de Sistemas (1º ano) da **ETEC de Cidade Tiradentes** – Centro Paula Souza, orientado pelos professores Everson e Erika.

> **Observação:** esta etapa do projeto é de **especificação e prototipação**. O repositório reúne a documentação e os protótipos do sistema; o código da plataforma ainda não foi desenvolvido.

## Integrantes

- Denis Luango Rodrigues
- Felipe de Melo Bordim
- Gustavo Eduardo dos Santos Zacharias
- João Lucas Margarido De Souza
- Marcio Marques de Oliveira Junior
- Yuri Grassiotto Haguihara

## Finalidade

O HelpEnem! é uma plataforma voltada a estudantes do ensino médio que se preparam para o Exame Nacional do Ensino Médio (ENEM). A proposta é ajudar o aluno a **identificar seus pontos fracos** por meio de simulados baseados na matriz de referência do exame.

Ao final de cada simulado, o sistema analisa acertos e erros e gera um relatório mostrando em quais disciplinas e assuntos o aluno foi melhor e em quais tem mais dificuldade. Com base nisso, a plataforma indica os temas que precisam de mais atenção e sugere materiais de apoio, para que o estudante direcione melhor seu tempo de preparação.

## Principais funcionalidades

- **Cadastro e login** de usuários, com validação de dados e aviso de e-mail já cadastrado.
- **Cronograma de estudos** personalizado, que pode ser editado (matérias, dias e horários).
- **Simulados configuráveis:** quantidade de questões, matérias e uso de cronômetro.
- **Questões exibidas uma por vez**, com correção e explicação da resposta.
- **Pausa do simulado**, que exige responder a questão atual antes, e opção de **sair e salvar o progresso**.
- **Correção automática** com base no gabarito.
- **Relatórios por matéria e por assunto**, destacando onde houve mais erros, com atualização dos indicadores de evolução.
- **Sugestão de materiais de estudo** conforme os pontos fracos identificados.
- **Histórico de simulados**, com relatório detalhado e possibilidade de **retomar simulados incompletos**.

## Recursos e artefatos produzidos

| Artefato | Descrição |
|---|---|
| Fluxograma do sistema | Fluxo completo em 4 partes: cadastro/login, painel principal, simulado e resultados/relatórios |
| Diagrama de caso de uso | Ações do usuário, com relações `include` e `extend` |
| Descritivo de casos de uso | 12 casos de uso (CSU-01 a CSU-12) com pré-condições, fluxo básico e alternativo |
| Protótipo de baixa fidelidade | Esboços feitos à mão das telas do sistema |
| Protótipo de alta fidelidade | Telas digitais com a identidade visual do HelpEnem! (tema escuro com destaque em verde) |
| Matriz de rastreabilidade | Relação entre regras de negócio, requisitos funcionais e não funcionais |
| Lista de requisitos | 20 requisitos funcionais (RF-01 a RF-20) e 5 não funcionais (RNF-01 a RNF-05: segurança, eficiência, confiabilidade, usabilidade e manutenibilidade) |

## Documentação completa

Toda a documentação do projeto está no arquivo [`Help Enem - Projeto de PTIC.pdf`](./Help%20Enem%20-%20Projeto%20de%20PTIC.pdf).
