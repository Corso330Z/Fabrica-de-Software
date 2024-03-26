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
|RF-001 |Cadastrar usuários | O sistema possibilitará o usuário criar uma conta, colocando suas informações principais. |
|RF-002 | Editar perfil | O sistema possibilitará o usuário a configurar e modificar a sua conta de acordo com seu gosto, podendo por uma foto, uma descrição, ou escolher o tema do site. |
|RF-003 | Cadastrar filmes  | O sistema possibilitará o operador ou o usuário cadastrar e adicionar novas opções de filmes para o site. |
|RF-004 | Filtrar filmes adicionados | O sistema irá filtra os filmes adicionados enviando para os operadores, que verificam se a postagem pode ser efetuada ou não. |
|RF-005 | Avaliar filmes | O sistema possibilitará o usuário avaliar os filmes disponíveis no sistema de estrelas. |
|RF-006 | Adicionar comentários | O sistema possibilitará os usuários adicionarem comentários às postagens feitas por outros usuários. |
|RF-007 | Remover comentários | O sistema possibilitará os usuários apagarem seus comentários e também possibilitará os operadores a deletar comentários permanentemente. |
|RF-008 | Filtrar comentários | O sistema irá filtrar os comentários, bloqueando algumas palavras agressivas e abusivas. |
|RF-009 | Burcar usuário | O sistema possibilitará a busca de usuários através do nome cadastrado ou pelo id. |
|RF-0010 | Buscar filmes por nome | O sistema possibilitará a busca de filmes através do nome. |
|RF-0011 | Burcar filmes por gênero | O sistema possibilitará a busca de filmes através de categorias, como: terror, romance. |
|RF-0012 | Categorizar por gênero | O sistema ordenará os filmes por gêneros. |
|RF-0013 | Apresentar informações gerais do filme | O sistema apresentá informações do filme, como: diretor, elenco, duração, síntase. |
|RF-0014 | Adicionar aos favoritos | O sistema possibilitará que o usuário adicione os filmes a pasta favoritos. |
|RF-0015 | Adicionar amigos | O sistema possibilitará que o usuário adicione amigos, para que possam compartilhar avaliações.|
|RF-0016 | Trocar senha | O sistema possibilitará ao usuário trocar a senha, caso ocorra alguma complicação. |
|RF-0017 | Avaliar comentários | O sistema possibilitará que os usuário avaliem os comentários através do sistema de likes. |
|RF-0018 | Visualizar lançamentos | O sistema disponibilizará os lançamentos dos filmes para o usuário. |
|RF-0019 | Anexar imagem | O sistema permitirá ao operador anexar imagens durante a cadastração de filmes. |
|RF-0020 | Notificar | O sistema notificará as mudanças do site, como: filmes novos, comentários, avaliações. |

 

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
