# Priorização 

## Introdução

A Three-Level Scale é uma abordagem prática para priorizar requisitos com base em duas dimensões: importância e urgência (Covey, 2004). Essa escala considera que cada requisito pode ser avaliado como importante ou não importante, e urgente ou não urgente, resultando em quatro combinações possíveis. Esse método permite classificar e organizar os requisitos de forma relativa, auxiliando no alinhamento estratégico e na tomada de decisões eficientes. O artefato proposto utiliza essa metodologia para definir uma escala de prioridades clara, orientando a execução de atividades e o alcance de objetivos de negócios. A Figura 1 determina a lógica da técnica visualmente. 

<center>

<font size="3"><p><b>Figura 1:</b> Priorização de requisitos baseada na importância e urgência.</p></font>
![Quadro three-level scale](../assets/three_level.png)
<font size="3"><p><b>Fonte:</b> Software Requirements, Third Edition. Karl Wiegers and Joy Beatty.</p></font>
</center>

## Metodologia

Como descrito por Wiegers e Beatty, os requisitos serão classificados nas categorias:

1. **Alta prioridade:** Urgente e importante. Os requisitos dessa categoria são extremamente importantes e urgentes, ou seja, os clientes e usuários precisam deles presente na próxima release. Existe também uma alternativa onde um requisito é categorizado como de alta prioridade por um contrato ou acordo. Se o requisito pode esperar a implementação sem prejudicar o andamento do projeto, então ele não se encaixa nessa categoria.
2. **Média prioridade:** Não Urgente e importante. São requisitos importantes mas que não são urgentes, ou seja, mesmo precisando ser implementados eles podem esperar uma próxima release.
3. **Baixa prioridade:** Não urgente e não importante. São requisitos que não são nem importantes e nem urgentes, podendo ser adiados e nem implemntados, se for o caso.

Também existe uma quarta categoria que diz a respeito de requisitos que podem parecer de extrema importância para o cliente, mas que no fim são completamente desnecessários para o funcionamento do projeto.

## Legenda para tabela de requisitos

1. **Identificador:** Código único para cada requisito, usado para identificação e referência rápida, onde RE significa Requisito Elicitado.
2. **Requisito:** Descrição do que o sistema deve realizar.
3. **Tipo:** Qual o tipo de requisito, onde RF significa Requisito Funcional e RNF significa Requisito Não Funcional.
4. **Implementado:** se foi implementado pelo ATS da Mindsight ou não.
5. **Origem:** indica de maniera rastreável de onde o requisito é proveniente.
6. **Prioridade:** Prioridade fornecida por Vitor Feijó, Alta ou Média ou Baixa.

## Resultados

<center>

<font size="3"><p><b>Tabela 1:</b> Requisitos priorizados.</p></font>

| Identificador do requisito | Requisito| Tipo | Implementado | Origem | Prioridade |
|:-:|:-:|:-:|:-:|:-:|:-:|
| RE-001                     | O sistema deve permitir o cadastro de vagas, incluindo informações como Nome da vaga, quantidade de posições, quantos dias se deseja finalizar a vaga, faixa salarial, cargo, empresa e departamento. | RF   | Sim          | [AD](../foco1/mindsight.md)           | Alta |
| RE-002                     | O sistema deve possibilitar o gerenciamento de vagas por status, categorizando-as como Atrasada, Em andamento ou Concluída. | RF   | Sim          | [AD](../foco1/mindsight.md)           | Alta |
| RE-003                     | O sistema deve oferecer uma inscrição simplificada para os candidatos, coletando nome completo, E-mail, Linkedin, Telefone, currículo, Portifólio, se é uma pessoa PCD, País, Estado, Cidade, Possibilidade de mudança, Aceita viajar pela empresa, Data de nascimento, pretensão salarial, CPF, Como ficou sabendo da vaga.    | RF   | Sim          | [AD](../foco1/mindsight.md)           | Alta |
| RE-004                     | O sistema deve permitir ações em massa nos candidatos, como mover de etapa, reprovar, enviar notificação por email, adicionar à vaga.         | RF   | Sim          | [AD](../foco1/mindsight.md)           | Alta |
| RE-005                     | O sistema deve permitir a inclusão de perguntas adicionais de requisitos durante a inscrição dos candidatos. | RF   | Sim          | [AD](../foco1/mindsight.md)           | Alta |
| RE-006                     | O sistema deve integrar-se com a Central de Oportunidades Mindsight para a divulgação automática de vagas.   | RF   | Sim          | [AD](../foco1/mindsight.md)           | Alta |
| RE-007                     | O sistema deve integrar-se com o LinkedIn, permitindo a publicação de vagas diretamente na plataforma.        | RF   | Sim          | [AD](../foco1/mindsight.md)           | Alta |
| RE-008                     | O sistema deve integrar-se com o Google For Jobs, otimizando a visibilidade das vagas publicadas.            | RF   | Sim          | [AD](../foco1/mindsight.md)           | Alta |
| RE-009                     | O sistema deve integrar-se com o Indeed, permitindo a sincronização de vagas.                               | RF   | Sim          | [AD](../foco1/mindsight.md)           | Alta |
| RE-010                     | O sistema deve integrar-se com o NetVagas para a divulgação de vagas.                                       | RF   | Sim          | [AD](../foco1/mindsight.md)           | Alta |
| RE-011                     | O sistema deve enviar testes automáticos da Mindsight aos candidatos inscritos, conforme definido no fluxo de seleção. | RF   | Sim          | [AD](../foco1/mindsight.md)           | Alta |
| RE-012                     | O sistema deve permitir a criação e personalização de uma página de carreira para a empresa.                 | RF   | Sim          | [AD](../foco1/mindsight.md)           | Alta |
| RE-013                     | O sistema deve manter um banco de talentos com dados de candidatos para futuras oportunidades.               | RF   | Sim          | [AD](../foco1/mindsight.md)           | Alta |
| RE-014                     | O sistema deve registrar o histórico de ações realizadas pelos candidatos no processo seletivo.              | RF   | Sim          | [AD](../foco1/mindsight.md)           | Alta |
| RE-015                     | O sistema deve possibilitar a extração de relatórios detalhados sobre o processo seletivo.                   | RF   | Sim          | [AD](../foco1/mindsight.md)           | Alta |
| RE-016                     | O sistema deve oferecer uma matriz inteligente para triagem em massa, avaliando Match técnico e Fit cultural. | RF   | Sim          | [AD](../foco1/mindsight.md)           | Alta |
| RE-017                     | O sistema deve permitir a filtragem de candidatos com base nas respostas às perguntas de requisitos.         | RF   | Sim          | [AD](../foco1/mindsight.md)           | Alta |
| RE-018                     | O sistema deve permitir a filtragem de candidatos com base nos resultados obtidos nos testes aplicados.      | RF   | Sim          | [AD](../foco1/mindsight.md)           | Alta |
| RE-019                     | O sistema deve possibilitar a gestão de acessos de usuários, definindo permissões específicas.               | RF   | Sim          | [AD](../foco1/mindsight.md)           | Alta |
| RE-020                     | O sistema deve permitir a criação e edição de modelos de e-mail personalizados para comunicação com candidatos. | RF   | Sim          | [AD](../foco1/mindsight.md)           | Alta |
| RE-021                     | O sistema deve disponibilizar acesso a uma API para integração com outros sistemas.                         | RF   | Sim          | [AD](../foco1/mindsight.md)           | Alta |
| RE-022                     | O sistema deve oferecer uma visão em pipeline do processo de contratação, mostrando o estágio de cada candidato (triagem, entrevista, revisão, oferta, contratação). | RF   | Não          | [AC Zoho](../concorrentes/zoho.md)   | Média |
| RE-023                     | O sistema deve permitir a automação de fluxos de trabalho com regras automáticas para tarefas como notificações de entrevistas e rejeições de candidatos com base em critérios. | RF   | Não          | [AC Zoho](../concorrentes/zoho.md)   | Média |
| RE-024                     | O sistema deve gerar relatórios sobre a origem dos candidatos e o status de cada um no recrutamento, incluindo gráficos para análise de desempenho. | RF   | Não          | [AC Zoho](../concorrentes/zoho.md)   | Média |
| RE-025                     | O sistema deve facilitar a comunicação interna entre a equipe de recrutamento por meio de menções e comentários. | RF   | Não          | [AC Zoho](../concorrentes/zoho.md)   | Baixa |
| RE-026                     | O sistema deve oferecer uma comunidade para interação, discussão de dúvidas e compartilhamento de soluções para o uso do ATS. | RF  | Não          | [AC Zoho](../concorrentes/zoho.md)   | Média |
| RE-027                     | O sistema deve disponibilizar uma biblioteca de vídeos tutoriais para configuração e otimização das funcionalidades, como agendamento de entrevistas e integração com portais. | RF  | Não          | [AC Zoho](../concorrentes/zoho.md)   | Alta |
| RE-028                     | O sistema deve oferecer suporte via chat, e-mail, webinars, central de ajuda, guia de API para desenvolvedores, perguntas frequentes e blog. | RF  | Não          | [AC Zoho](../concorrentes/zoho.md)   | Alta |
| RE-029                     | O sistema deve ser compatível com extensões para navegadores e complementos para Gmail e Outlook. | RF  | Não          | [AC Zoho](../concorrentes/zoho.md)   | Baixa |
| RE-030                     | O sistema deve fornecer uma página inicial (dashboard) com visão geral e métricas sobre o processo de recrutamento. | RF   | Não          | [AC Zoho](../concorrentes/zoho.md)   | Média |
| RE-031                     | O sistema deve incluir uma área para agendamento e gerenciamento de entrevistas, com funcionalidades de calendário e sincronização com outras ferramentas. | RF   | Não          | [AC Zoho](../concorrentes/zoho.md)   | Média |
| RE-032                     | O sistema deve permitir a configuração de regras que automatizem ações, como cancelamento de entrevistas e mudança de status, adaptáveis a diferentes módulos. | RF   | Não          | [AC Zoho](../concorrentes/zoho.md)   | Média |
| RE-033                     | O sistema deve oferecer funcionalidades de importação e exportação de dados, backup, armazenamento, lixeira, registro de auditoria e log de atividade. | RF  | Não          | [AC Zoho](../concorrentes/zoho.md)   | Média |
| RE-034                     | O sistema deve permitir o agendamento e autoagendamento de entrevistas, com seleção de entrevistadores, recursos e horários. | RF   | Não          | [AC Greenhouse](../concorrentes/greenhouse.md)   | Baixa |
| RE-035                     | O sistema deve organizar entrevistas colaborativas, oferecendo planos estruturados e integração com ferramentas como Zoom. | RF   | Não          | [AC Greenhouse](../concorrentes/greenhouse.md)   | Baixa |
| RE-036                     | O sistema deve automatizar tarefas relacionadas à integração de novos colaboradores.                          | RF   | Não          | [AC Greenhouse](../concorrentes/greenhouse.md)   | Baixa |
| RE-037                     | O sistema deve alertar sobre candidatos duplicados e realizar o rastreamento de suas aplicações para evitar redundâncias no pipeline. | RF   | Não          | [AC Greenhouse](../concorrentes/greenhouse.md)   | Alta |
| RE-038                     | O sistema deve oferecer programas estruturados de referência de funcionários, com incentivos integrados ao processo de recrutamento. | RF   | Não          | [AC Greenhouse](../concorrentes/greenhouse.md)   | Baixa |
| RE-039                     | O sistema deve incluir um painel consolidado para análise de qualidade por canal de recrutamento.             | RF   | Não          | [AC Greenhouse](../concorrentes/greenhouse.md)   | Média |
| RE-040                     | O sistema deve centralizar informações para equipes de recrutamento, facilitando a colaboração no processo seletivo. | RF   | Não          | [AC Greenhouse](../concorrentes/greenhouse.md)   | Baixa |
| RE-041                     | O sistema deve permitir a tradução de linguagem e disponibilizar quadros de vagas em 19 idiomas.              | RF   | Não          | [AC Greenhouse](../concorrentes/greenhouse.md)   | Baixa |
| RE-042                     | O sistema deve oferecer fluxos de trabalho escaláveis com etapas personalizáveis por cargo ou departamento.   | RF   | Não          | [AC Greenhouse](../concorrentes/greenhouse.md)   | Média |
| RE-043                     | O sistema deve disponibilizar ferramentas para organização de entrevistas, incluindo preparação de perguntas e scorecards. | RF   | Não          | [AC Greenhouse](../concorrentes/greenhouse.md)   | Média |
| RE-044                     | O sistema deve prever datas de aceitação de ofertas e início de trabalho usando aprendizado de máquina baseado em dados históricos. | RF   | Não          | [AC Greenhouse](../concorrentes/greenhouse.md)   | Média |
| RE-045                     | O sistema deve fornecer formulários de kickoff para capturar objetivos do negócio, habilidades e times de contratação. | RF   | Não          | [AC Greenhouse](../concorrentes/greenhouse.md)   | Média |
| RE-046                     | O sistema deve incluir um painel de análise demográfica do pipeline, incluindo gênero, para medir diversidade no processo seletivo. | RF   | Não          | [AC Greenhouse](../concorrentes/greenhouse.md)   | Média |
| RE-047                     | O sistema deve possibilitar a exportação e customização de relatórios, permitindo a criação de relatórios personalizados e integração com ferramentas de BI como Tableau. | RF   | Não          | [AC Greenhouse](../concorrentes/greenhouse.md)   | Média |
| RE-048                     | O sistema deve possibilitar a integração com mais de 529 ferramentas de terceiros, organizadas por categorias como HRIS & onboarding, Job distribution, Sourcing, entre outras. | RF   | Não          | [AC Greenhouse](../concorrentes/greenhouse.md)   | Média |
| RE-049                     | O sistema deve permitir atualizações importantes no processo de contratação, como aprovações e lembretes, diretamente no Slack. | RF   | Não          | [AC Greenhouse](../concorrentes/greenhouse.md)   | Média |
| RE-050                     | O sistema deve oferecer funcionalidades para candidatos gravarem a pronúncia de seus nomes, facilitando a comunicação personalizada. | RF   | Não          | [AC Greenhouse](../concorrentes/greenhouse.md)   | Baixa |
| RE-051                     | O sistema deve incluir ferramentas para incentivar práticas inclusivas, como testes anônimos e seleção de pronomes preferidos. | RF   | Não          | [AC Greenhouse](../concorrentes/greenhouse.md)   | Média |
| RE-052                     | O sistema deve coordenar tarefas como testes práticos, verificações de antecedentes e assinaturas digitais de forma centralizada. | RF   | Não          | [AC Greenhouse](../concorrentes/greenhouse.md)   | Baixa |
| RE-053                     | O sistema deve permitir a adição de comentários e interações diretas entre membros da equipe de recrutamento sobre candidatos. | RF   | Não          | [AC Bamboohr](../concorrentes/bamboohr.md)   | Baixa |
| RE-054                     | O sistema deve exibir métricas gerais do processo seletivo em um dashboard centralizado, incluindo status de candidatos e insights sobre o funil de recrutamento. | RF   | Não          | [AC Bamboohr](../concorrentes/bamboohr.md)   | Média |
| RE-055                     | O sistema deve permitir o envio de cartas de oferta com preenchimento automático e assinatura eletrônica para agilizar a formalização da contratação. | RF   | Não          | [AC Bamboohr](../concorrentes/bamboohr.md)   | Média |
| RE-056                     | O sistema deve incluir funcionalidades para a transição do processo seletivo para o onboarding digital, com pacotes de boas-vindas customizáveis. | RF   | Não          | [AC Bamboohr](../concorrentes/bamboohr.md)   | Baixa |
| RE-057                     | O sistema deve oferecer um aplicativo móvel para gerenciar vagas, candidatos e comunicações, com funcionalidades de visualização e ações rápidas. | RF   | Não          | [AC Bamboohr](../concorrentes/bamboohr.md)   | Baixa |
| RE-058                     | O sistema deve permitir a sincronização com calendários para agendamento e gerenciamento de entrevistas e eventos relacionados ao recrutamento. | RF   | Não          | [AC Bamboohr](../concorrentes/bamboohr.md)   | Média |
| RE-059                     | O sistema deve fornecer controle de saldo de licenças e exibição de informações sobre planos de benefícios para colaboradores. | RF   | Não          | [AC Bamboohr](../concorrentes/bamboohr.md)   | Baixa |
| RE-060                     | O sistema deve incluir lembretes automáticos sobre prazos, feedbacks pendentes e outras ações requeridas no processo seletivo. | RF   | Não          | [AC Bamboohr](../concorrentes/bamboohr.md)   | Média |
| RE-061                     | O sistema deve oferecer funcionalidades para solicitação, aprovação e acompanhamento de licenças diretamente pela plataforma. | RF   | Não          | [AC Bamboohr](../concorrentes/bamboohr.md)   | Baixa |
| RE-062                     | O sistema deve centralizar informações de disponibilidade, ausência e datas importantes da equipe, como aniversários. | RF   | Não          | [AC Bamboohr](../concorrentes/bamboohr.md)   | Baixa |
| RE-063                     | O sistema deve permitir o controle de treinamentos incompletos e o acompanhamento de programas de capacitação obrigatórios ou opcionais. | RF   | Não          | [AC Bamboohr](../concorrentes/bamboohr.md)   | Baixa |
| RE-064                     | O sistema deve exibir dados de desempenho, como colaboradores sem aumento salarial há mais de 12 meses, em um painel de insights. | RF   | Não          | [AC Bamboohr](../concorrentes/bamboohr.md)   | Baixa |
| RE-065                     | O sistema deve permitir a disponibilização de links úteis para a equipe, como acesso a documentos, políticas e recursos da empresa. | RF   | Não          | [AC Bamboohr](../concorrentes/bamboohr.md)   |  Média |
| RE-066                     | O sistema deve centralizar dados pessoais e profissionais dos colaboradores, como cargo, status de emprego, informações de contato e departamento. | RF   | Não          | [AC Bamboohr](../concorrentes/bamboohr.md)   | Baixa |
| RE-067                     | O sistema deve registrar informações sobre data de contratação, status de emprego (full-time/part-time) e detalhes sobre benefícios associados. | RF   | Não          | [AC Bamboohr](../concorrentes/bamboohr.md)   | Baixa |
| RE-068                     | O sistema deve permitir o armazenamento e acesso a documentos importantes dos colaboradores, como contratos e políticas assinadas. | RF   | Não          | [AC Bamboohr](../concorrentes/bamboohr.md)   | Baixa |
| RE-069                     | O sistema deve oferecer a personalização de campos de dados para atender necessidades específicas da empresa. | RF   | Não          | [AC Bamboohr](../concorrentes/bamboohr.md)   | Baixa |
| RE-070                     | O sistema deve monitorar e registrar equipamentos alocados aos colaboradores, como laptops e celulares. | RF   | Não          | [AC Bamboohr](../concorrentes/bamboohr.md)   | Baixa |
| RE-071                     | O sistema deve permitir a adição de notas internas sobre colaboradores, garantindo confidencialidade e organização de informações específicas. | RF   | Não          | [AC Bamboohr](../concorrentes/bamboohr.md)   | Baixa |
| RE-072                     | O sistema deve oferecer funcionalidades para controle de treinamentos individuais, incluindo status e progresso. | RF   | Não          | [AC Bamboohr](../concorrentes/bamboohr.md)   | Baixa |
| RE-073                     | O sistema deve permitir que colaboradores solicitem alterações em seus registros, como atualização de dados pessoais ou profissionais. | RF   | Não          | [AC Bamboohr](../concorrentes/bamboohr.md)   | Baixa |
| RE-074                     | O sistema deve registrar contatos de emergência de colaboradores para uso em situações críticas. | RF   | Não          | [AC Bamboohr](../concorrentes/bamboohr.md)   | Baixa |
| RE-075                     | O sistema deve permitir o rastreamento de horas trabalhadas diretamente associadas aos colaboradores, vinculando a relatórios de pagamento e produtividade. | RF   | Não          | [AC Bamboohr](../concorrentes/bamboohr.md)   | Baixa |
| RE-076                     | O sistema deve incluir um assistente de inteligência artificial para suporte em tempo real, respondendo a perguntas sobre políticas da empresa, benefícios e procedimentos de RH. | RF   | Não          | [AC Bamboohr](../concorrentes/bamboohr.md)   | Média |
| RE-077                     | O sistema deve exibir um organograma para visualização da estrutura hierárquica da empresa, com navegação para explorar equipes e supervisores. | RF   | Não          | [AC Bamboohr](../concorrentes/bamboohr.md)   | Baixa |
| RE-078                     | O sistema deve oferecer uma lista completa de colaboradores ativos e inativos com filtros por localização, status de emprego e outros critérios. | RF   | Não          | [AC Bamboohr](../concorrentes/bamboohr.md)   | Baixa |
| RE-079                     | O sistema deve permitir o registro de novos colaboradores, incluindo informações completas de contato, cargo e departamento. | RF   | Não          | [AC Bamboohr](../concorrentes/bamboohr.md)   | Baixa |
| RE-080                     | O sistema deve disponibilizar ferramentas para criação de relatórios personalizados com base em métricas específicas, como adições e desligamentos. | RF   | Não          | [AC Bamboohr](../concorrentes/bamboohr.md)   | Baixa |
| RE-081                     | O sistema deve disponibilizar relatórios padrão como headcount, turnover e uso de benefícios, acessíveis de forma rápida. | RF   | Não          | [AC Bamboohr](../concorrentes/bamboohr.md)   | Baixa |
| RE-082                     | O sistema deve oferecer a opção de salvar relatórios frequentemente acessados como favoritos para facilitar análises recorrentes. | RF   | Não          | [AC Bamboohr](../concorrentes/bamboohr.md)   |  Média |
| RE-083                     | O sistema deve exibir relatórios recentes acessados, organizados por período, como últimos 7 dias, com opções para abrir e editar. | RF   | Não          | [AC Bamboohr](../concorrentes/bamboohr.md)   | Média |
| RE-084                     | O sistema deve apresentar uma tela de boas-vindas interativa para novos usuários, com vídeos explicativos e passos guiados. | RF   | Não          | [AC Bamboohr](../concorrentes/bamboohr.md)   | Média |
| RE-085                     | O sistema deve oferecer uma biblioteca para armazenamento e gerenciamento de documentos corporativos, categorizados por tipo e com funcionalidade de busca. | RF   | Não          | [AC Bamboohr](../concorrentes/bamboohr.md)   | Baixa |
| RE-086                     | O sistema deve permitir o upload de documentos diretamente na plataforma para compartilhamento ou arquivamento centralizado. | RF   | Não          | [AC Bamboohr](../concorrentes/bamboohr.md)   |  Baixa |
| RE-087                     | O sistema deve gerenciar modelos de assinatura para contratos e outros documentos legais. | RF   | Não          | [AC Bamboohr](../concorrentes/bamboohr.md)   | Média |
| RE-088                     | O sistema deve centralizar documentos importantes como manuais da empresa, políticas de reembolso e resumos de benefícios. | RF   | Não          | [AC Bamboohr](../concorrentes/bamboohr.md)   |  Média |

<font size="3"><p><b>Autor:</b> Vitor Feijó, 2024.</p></font>

</center>

## Bibliografia

></a> 1. Software Requirements Third Edition. In: WIEGERS, Karl E.; BEATTY, Joy. Software Requirements. 3. ed. [S. l.]: Microsoft Press, 2013. cap. 16, p. 313-329. ISBN 0735679665. Disponível em: [https://www.booksfree.org/wp-content/uploads/2022/03/Software_Requirements_3rd_Edition_compressed.pdf](https://www.booksfree.org/wp-content/uploads/2022/03/Software_Requirements_3rd_Edition_compressed.pdf)

## Histórico de versão
| Versão | Data | Descrição | Autor(es) |
| :-: | :-: | :-: | :-: |
| `1.0` | 10/11/2024 | Criação do artefato de three-level scale | Vitor Feijó |
| `1.1` | 18/11/2024 | Preenchimento do artefato | Vitor Feijó |