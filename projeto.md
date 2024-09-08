<img src='/img/logo.png' alt='logo da empresa' width='50px' heidth='50px'/>

# *FIBONACCI MANAGEMENT SYSTEM*

# PROJETO DE SOFTWARE

## *Stakeholders*
|NOME|CARGO|E-MAIL|
|:---|:---|:---|
|Wagner da Silva Ferreira Filho|Gerente de Projeto|wagner.ferreira@ifro.edu.br|
|Wagner da Silva Ferreira Filho|Gerente de Projeto|wagner.ferreira@ifro.edu.br|
|Wagner da Silva Ferreira Filho|Gerente de Projeto|wagner.ferreira@ifro.edu.br|
|Wagner da Silva Ferreira Filho|Gerente de Projeto|wagner.ferreira@ifro.edu.br|
|Wagner da Silva Ferreira Filho|Gerente de Projeto|wagner.ferreira@ifro.edu.br|


# Sumário

* [RESUMO DO PROJETO](#resumo-do-projeto)
* [INTRODUÇÃO](#introdução)
  * [PROPÓSITO DESTE DOCUMENTO](#propósito-deste-documento)
* [DESCRIÇÃO GERAL](#descrição-geral)
  * [USUÁRIOS DO SISTEMA](#usuários-do-sistema)
  * [ABRANGÊNCIA E SISTEMAS SIMILARES](#abrangência-e-sistemas-similares)
  * [SUPOSIÇÕES E DEPENDÊNCIAS](#suposições-e-dependências)
* [METODOLOGIA ADOTADA NO DESENVOLVIMENTO](#metodologia-adotada-no-desenvolvimento)
* [REQUISITOS DO SOFTWARE](#requisitos-do-software)
  * [REQUISITOS FUNCIONAIS](#requisitos-funcionais)
  * [REQUISITOS NÃO FUNCIONAIS](#requisitos-não-funcionais)
* [PROTOTIPAGEM](#prototipagem)
* [DIAGRAMA DE CASOS DE USO](#diagrama-de-casos-de-uso)
* [DIAGRAMA DE CLASSES](#diagrama-de-classes)
* [REFERÊNCIAS](#referências)


# RESUMO DO PROJETO
| ITEM | DESCRIÇÃO|
|:---|:---|
| NOME DO PROJETO | Fibonacci Management System |
| GERENTE DO PROJETO | Wagner Ferreira |
| PRINCIPAL OBJETIVO | Auxiliar o sistema de ensino através de ferramentas síncronas e assíncronas que serão usadas por funcionários e alunos da instituição de ensino. |
| BENEFÍCIOS ESPERADOS |* Melhor acompanhamento pedagógico;<br/>* Redução da evasão escolar;<br/>* Aumento do número de matrículas;<br/>* Redução da inadimplência escolar;<br/>* Automatização dos processos financeiross|
| INÍCIO E TÉRMINO PREVISTOS | 14/03/2023 - 07/12/2023 |

[ [INÍCIO](#fibonacci-management-system) ]

# INTRODUÇÃO

## PROPÓSITO DESTE DOCUMENTO

Este documento destina-se aos clientes, engenheiros, gerentes e demais stakeholders deste projeto. O propósito deste documento é apresentar a descrição dos serviços e funções que o sistema **_Fibonacci Management System_** deve prover, bem como as suas restrições de operação e propriedades gerais, a fim de ilustrar uma descrição detalhada do sistema para um auxílio durante as etapas de análise, projeto e testes. O documento especifica todos os requisitos funcionais e não funcionais do sistema e contém a prototipagem, além de diagramas UML que foram construídos levando-se em conta as funcionalidades identificadas durante a fase de concepção do sistema.

[ [INÍCIO](#fibonacci-management-system) ]

# DESCRIÇÃO GERAL

## Usuários do sistema
|USUÁRIO|DESCRIÇÃO|
|:---|:---|
|**Usuário Padrão:**|Realizam as tarefas comuns a todos os usuários, tal como: logar e enviar mensagens. Todos demais usuários estendem as funcionalidades do UsuárioPadrão|
|**Administrador:**|Responsáveis pelo gerenciamento das entidades pertinentes à instituição e pela alocação de outros administradores|
|**Coordenador:**|Responsáveis pela aprovação de disciplinas, turmas e matrículas realizadas pela secretaria do curso, além de ser responsável pela alocação da secretaria|
|**Secretaria:**|Responsáveis pelo cadastramento de disciplinas e turmas, pela alocação de professores e monitores de um curso e matrículas dos alunos|
|**Professor:**|Responsáveis pela criação do programa da disciplina através de ferramentas de planejamento e criação de atividades|
|**Aluno:**|Seguem o programa da disciplina criada pelo professor, tendo como apoio ferramentas de comunicação, tal como: chat e fórum|


[ [INÍCIO](#fibonacci-management-system) ]

# Metodologia Adotada no Desenvolvimento


[ [INÍCIO](#fibonacci-management-system) ]

# Requisitos do Software

A especificação dos requisitos deste documento deve seguir as recomendações da norma IEEE Std-830-1998, levando em conta as recomentações do documento de [características dos requisitos](caracteristicas_requisitos.md).

## Requisitos Funcionais

A tabela a seguir contém a relação dos Requisitos Funcionais elicitados, com as colunas: identificador, nome, descrição e prioridade:
| IDENTIFICADOR | NOME | DESCRIÇÃO |
:---|:---|:---|
|RF-001 | Cadastrar usuários | O sistema possibilitará o usuário criar uma conta, colocando suas informações principais. |
|RF-002 | Sair da conta | O sistema possibilitará o usuário sair de sua conta em um dispositivo. |
|RF-003 | Deletar usuários | O sistema possibilitará o usuário deletar sua conta e seus dados cadastrados anteriormente. |
|RF-004 | Editar usuário | O sistema possibilitará o usuário a configurar e modificar a sua conta de acordo com seu gosto, podendo por uma foto, uma descrição, ou escolher o tema do site. |
|RF-005 | Visualizar usuário | O sistema possibilitará o usuário a acessar sua conta ou acessar a conta de outros usuários. |
|RF-006 | Restringir idade | O sistema irá restringir as ações e os conteúdos disponíveis ao usuário de acordo com a idade cadastrada, não permitindo algumas ações para menores de 18 anos.  |
|RF-007 | Adicionar amigo | O sistema possibilitará o usuário a adicionar amigos por meio dos nomes de usuário. |
|RF-008 | Restringir palavras  | O sistema irá restringir palavras de baixo calão que podem ser utilizadas para ofender alguém ou algum grupo étnico. |
|RF-009 | Logar usuário | O sistema possibilitará os usuários executarem o login através do nome cadastrado e de sua senha. |
|RF-0010 | Trocar senha | O sistema possibilitará ao usuário trocar a senha, caso ocorra alguma complicação. |
|RF-0011 | Avaliar comentários | O sistema possibilitará que os usuário avaliem os comentários através do sistema de likes. |
|RF-0012 | Adicionar comentários | O sistema possibilitará os usuários adicionarem comentários às postagens feitas por outros usuários. |
|RF-0013 | Remover comentários | O sistema possibilitará os usuários apagarem seus comentários e também possibilitará os operadores a deletar comentários permanentemente. |
|RF-0014 | Alterar comentários | O sistema possibilitará que os usuário alterem seus comentários. |
|RF-0015 | Visualizar comentário | O sistema possibilitará o usuário acessar uma tela onde estará os seus comentários, ou, dependendo do botão clicado,  os comentários de seus amigos. |
|RF-0016 | Cadastrar filmes | O sistema possibilitará o administrador cadastrar novos filmes no sistema. |
|RF-0017 | Deletar filmes | O sistema possibilitará o administrador deletar os filmes adicionados, caso necessário. |
|RF-0018 | Alterar filmes | O sistema possibilitará o administrador alterar a escrita feita por ele cadastro de filmes. |
|RF-0019 | Avaliar filmes | O sistema possibilitará o usuário avaliar os filmes disponíveis no sistema de estrelas. |
|RF-0020 | Buscar filmes | O sistema possibilitará o usuário buscar filmes pelo nome. |
|RF-0021 | Cadastrar gênero | O sistema possibilitará o administrador cadastrar novos gêneros cinemáticos. |
|RF-0022 | Deletar filmes | O sistema possibilitará o administrador deletar os gêneros já adicionados. |
|RF-0023 | Buscar gênero | O sistema possibilitará o usuário buscar filmes relacionados a determinado gênero e visualizar suas informações. |
|RF-0024 | Alterar gênero | O sistema possibilitará o administrador alterar as informações ou os filmes relacionados aos gêneros já adicionados. |
|RF-0024 | Adicionar favorito | O sistema possibilitará o usuário a adicionar filmes, gêneros e atores aos favoritos. |
|RF-0025 | Cadastrar ator | O sistema possibilitará o administrador cadastrar novos atores. |
|RF-0026 | Deletar ator | O sistema possibilitará o administrador deletar atores já adicionados. |
|RF-0027 | Consultar ator | O sistema possibilitará ao usuário visualizar os filmes feitos por determinado ator e visualizar suas informações. |
|RF-0028 | Alterar ator | O sistema possibilitará o administrador alterar as informações ou os filmes relacionados aos atores já adicionados. |
|RF-0029 | Visualizar telas | O sistema disponibilizará o usuário acessar as outras telas após o clique. |
|RF-0030 | Anexar imagem | O sistema permitirá ao operador anexar imagens durante a cadastração de filmes. |
|RF-0031 | Notificar | O sistema notificará as mudanças do site, como: filmes novos, comentários, avaliações. |
|RF-0032 | Buscar usuário | O sistema possibilitará o usuário a buscar outros. |
|RF-0033 | Buscar ator | O sistema possibilitará ao usuário buscar atores. |
|RF-0034 | Consultar filme | O sistema possibilitará ao usuário visualizar suas informações. |
|RF-0035 | Consultar favoritos | O sistema possibilitará ao usuário visualizar seus filmes e atores favoritos. |
|RF-0036 | Remover favoritos | O sistema possibilitará ao usuário remover dos favoritos. |
|RF-0037 | Voltar | O sistema possibilitará ao usuário voltar para a tela anterior. |
|RF-0038 | Remover amigo | O sistema possibilitará ao usuário remover uma pessoa de suas amizades. |


## Requisitos Não Funcionais
A tabela a seguir contém a relação com os Requisitos Não Funcionais identificados, contendo identificador, nome, descrição e prioridade:

| IDENTIFICADOR | NOME | DESCRIÇÃO |
|:---|:---|:---|
|RNF-001 |Nome do Requisito |Descreva aqui as informações sobre o requisito |
|RNF-002 |Nome do Requisito |Descreva aqui as informações sobre o segundo requisito |


[ [INÍCIO](#fibonacci-management-system) ]


# Prototipagem

[Protótipo criado no FIGMA em 2022 por estudantes](https://www.figma.com/file/iNC7wyX9zP7Kmn3BhiCFGf/Fals6Hood-(Prot%C3%B3tipo-criado-por-estudantes-em-2022)?node-id=0%3A1&t=B16hgeZP3MSURCCa-1)

![Imagem do Protótipo](/img/home.png)

[ [INÍCIO](#fibonacci-management-system) ]


# Diagrama de Casos de Uso


![Diagrama de Casos de Uso](/img/use_case_placas.png)

[ [INÍCIO](#fibonacci-management-system) ]

# Diagrama de Classes

![Diagrama](/img/diagrama_rate.png)

[ [INÍCIO](#fibonacci-management-system) ]


# REFERÊNCIAS

Esta subseção apresenta as referências aos documentos que utilizamos no auxílio à construção deste documento.
* [UML](https://www.omg.org/spec/UML/2.5/About-UML/)
* [Práticas para Especificação de Requisitos IEEE-830](https://ieeexplore.ieee.org/document/720574)
