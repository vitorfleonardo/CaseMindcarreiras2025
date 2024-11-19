# Roadmap

## Intrdoução

Este artefato apresenta o Roadmap de Releases, que organiza os requisitos priorizados em três releases distintas para orientar o desenvolvimento e a entrega do sistema. O objetivo do roadmap é planejar e comunicar de forma clara o cronograma de implementação dos requisitos, garantindo alinhamento entre as equipes envolvidas e o cumprimento de metas estratégicas. Cada release é composta por requisitos técnicos priorizados, ações necessárias para sua implementação e datas de início, finalização e lançamento. Essa abordagem permite uma visão estruturada do progresso do projeto, facilitando o planejamento, a execução e a adaptação às necessidades dos stakeholders.

## Resultados

| Identificador do requisito | Requisito                                                                                                     | Release|
|:-:|:-:|:-:|
| RE-027                     | O sistema deve disponibilizar uma biblioteca de vídeos tutoriais para configuração e otimização das funcionalidades, como agendamento de entrevistas e integração com portais. | 01 |
| RE-028                     | O sistema deve oferecer suporte via chat, e-mail, webinars, central de ajuda, guia de API para desenvolvedores, perguntas frequentes e blog. |  01 |
| RE-037                     | O sistema deve alertar sobre candidatos duplicados e realizar o rastreamento de suas aplicações para evitar redundâncias no pipeline. | 01 |
| RE-022                     | O sistema deve oferecer uma visão em pipeline do processo de contratação, mostrando o estágio de cada candidato (triagem, entrevista, revisão, oferta, contratação). |  01 |
| RE-023                     | O sistema deve permitir a automação de fluxos de trabalho com regras automáticas para tarefas como notificações de entrevistas e rejeições de candidatos com base em critérios. | 02 |
| RE-030                     | O sistema deve fornecer uma página inicial (dashboard) com visão geral e métricas sobre o processo de recrutamento. | 01 |
| RE-031                     | O sistema deve incluir uma área para agendamento e gerenciamento de entrevistas, com funcionalidades de calendário e sincronização com outras ferramentas. | 02 |
| RE-043                     | O sistema deve disponibilizar ferramentas para organização de entrevistas, incluindo preparação de perguntas e scorecards. | 02 |
| RE-054                     | O sistema deve exibir métricas gerais do processo seletivo em um dashboard centralizado, incluindo status de candidatos e insights sobre o funil de recrutamento. | 02 |
| RE-058                     | O sistema deve permitir a sincronização com calendários para agendamento e gerenciamento de entrevistas e eventos relacionados ao recrutamento. | 03 |
| RE-060                     | O sistema deve incluir lembretes automáticos sobre prazos, feedbacks pendentes e outras ações requeridas no processo seletivo. | 02 |
| RE-024                     | O sistema deve gerar relatórios sobre a origem dos candidatos e o status de cada um no recrutamento, incluindo gráficos para análise de desempenho. | 01 |
| RE-032                     | O sistema deve permitir a configuração de regras que automatizem ações, como cancelamento de entrevistas e mudança de status, adaptáveis a diferentes módulos. | 02 |
| RE-039                     | O sistema deve incluir um painel consolidado para análise de qualidade por canal de recrutamento.             | - |
| RE-042                     | O sistema deve oferecer fluxos de trabalho escaláveis com etapas personalizáveis por cargo ou departamento.   | - |
| RE-045                     | O sistema deve fornecer formulários de kickoff para capturar objetivos do negócio, habilidades e times de contratação. | - |
| RE-047                     | O sistema deve possibilitar a exportação e customização de relatórios, permitindo a criação de relatórios personalizados e integração com ferramentas de BI como Tableau. | - |
| RE-051                     | O sistema deve incluir ferramentas para incentivar práticas inclusivas, como testes anônimos e seleção de pronomes preferidos. | - |
| RE-055                     | O sistema deve permitir o envio de cartas de oferta com preenchimento automático e assinatura eletrônica para agilizar a formalização da contratação. | - |
| RE-033                     | O sistema deve oferecer funcionalidades de importação e exportação de dados, backup, armazenamento, lixeira, registro de auditoria e log de atividade. | - |
| RE-046                     | O sistema deve incluir um painel de análise demográfica do pipeline, incluindo gênero, para medir diversidade no processo seletivo. | - |
| RE-049                     | O sistema deve permitir atualizações importantes no processo de contratação, como aprovações e lembretes, diretamente no Slack. | - |
| RE-065                     | O sistema deve permitir a disponibilização de links úteis para a equipe, como acesso a documentos, políticas e recursos da empresa. | - |
| RE-082                     | O sistema deve oferecer a opção de salvar relatórios frequentemente acessados como favoritos para facilitar análises recorrentes. | - |
| RE-083                     | O sistema deve exibir relatórios recentes acessados, organizados por período, como últimos 7 dias, com opções para abrir e editar. | - |
| RE-087                     | O sistema deve gerenciar modelos de assinatura para contratos e outros documentos legais.                   | - |
| RE-088                     | O sistema deve centralizar documentos importantes como manuais da empresa, políticas de reembolso e resumos de benefícios. | - |
| RE-026                     | O sistema deve oferecer uma comunidade para interação, discussão de dúvidas e compartilhamento de soluções para o uso do ATS. | - |
| RE-044                     | O sistema deve prever datas de aceitação de ofertas e início de trabalho usando aprendizado de máquina baseado em dados históricos. | 03 |
| RE-048                     | O sistema deve possibilitar a integração com mais de 529 ferramentas de terceiros, organizadas por categorias como HRIS & onboarding, Job distribution, Sourcing, entre outras. | 03 |
| RE-076                     | O sistema deve incluir um assistente de inteligência artificial para suporte em tempo real, respondendo a perguntas sobre políticas da empresa, benefícios e procedimentos de RH. | 03 |
| RE-084                     | O sistema deve apresentar uma tela de boas-vindas interativa para novos usuários, com vídeos explicativos e passos guiados. | - |


<table>
    <tr>
        <th colspan="2">Release 01: Foco em experiência do usuário</th>
    </tr>
    <tr>
        <th>Objetivo</th>
        <td>Criar uma base funcional robusta, melhorando a experiência do usuário e fornecendo ferramentas fundamentais de recrutamento e seleção de talentos</td>
    </tr>
    <tr>
        <th>Requisitos técnicos</th>
        <td> 
            <ul>
                <li> <b> RE-027: </b> O sistema deve disponibilizar uma biblioteca de vídeos tutoriais para configuração e otimização das funcionalidades, como agendamento de entrevistas e integração com portais.</li>
                <li><b> RE-028: </b> O sistema deve oferecer suporte via chat, e-mail, webinars, central de ajuda, guia de API para desenvolvedores, perguntas frequentes e blog.</b></li>
               <li><b> RE-022: </b> O sistema deve oferecer uma visão em pipeline do processo de contratação, mostrando o estágio de cada candidato (triagem, entrevista, revisão, oferta, contratação).</b></li>
               <li><b> RE-030: </b> O sistema deve fornecer uma página inicial (dashboard) com visão geral e métricas sobre o processo de recrutamento.</b></li>
               <li><b> RE-037: </b> O sistema deve alertar sobre candidatos duplicados e realizar o rastreamento de suas aplicações para evitar redundâncias no pipeline.</b></li>
               <li><b> RE-024: </b> Gerar relatórios sobre origem de candidatos e status no recrutamento com gráficos básicos.</b></li>
            </ul> 
        </td>
    </tr>
    <tr>
        <th>Ações</th>
        <td> 
            <ul>
                <li> <b> Desenvolvimento: </b> Os requisitos téncicos devem ser desenvolvidos e estar em versão estável para testes até 20/02/2025.</li>
                <li> <b> Custumer Success: </b> Realizar teste de usabilidade das funcionalidades desenvolvidas de 20/02/2025 até 20/03/2025.</li>
                <li> <b> Desenvolvimento e teste: </b> Corrigir bugs, criar scripts de teste de 20/02/2025 até 20/03/2025.</li>
                <li> <b> Infraestrutura e Segurança: </b> Analisar e colocar em conformidade com LGPD, adicionando as funcionalidades desenvolvidas para produção até 03/04/2025.</li>
                <li> <b> Marketing: </b> Preparar evento de lançamento online para o dia 15/04/2025.</li>
            </ul> 
        </td>
    </tr>
    <tr>
        <th>Datas</th>
        <td> 
            <ul>
                <li> <b> Início: </b> 19/11/2024.</li>
                <li> <b> Fim: </b> 03/04/2025.</li>
                <li> <b> Lançamento: </b> 15/04/2025.</li>
            </ul> 
        </td>
    </tr>
<table>

<table>
    <tr>
        <th colspan="2">Release 02: Automação e Eficiência Operacional</th>
    </tr>
    <tr>
        <th>Objetivo</th>
        <td>Aumentar a eficiência do processo de recrutamento por meio de automação e integração.</td>
    </tr>
    <tr>
        <th>Requisitos técnicos</th>
        <td> 
            <ul>
                <li> <b> RE-023: </b> Permitir automação de fluxos de trabalho para notificações e rejeições.</li>
                <li><b> RE-031: </b> Incluir área para agendamento e gerenciamento de entrevistas, com integração de calendários.</b></li>
               <li><b> RE-060: </b>  Incluir lembretes automáticos sobre prazos e feedbacks pendentes.</b></li>
               <li><b> RE-032: </b> Configurar regras para ações automáticas, como cancelamento de entrevistas e mudanças de status.</b></li>
               <li><b> RE-043: </b> Fornecer ferramentas para organizar entrevistas, incluindo preparação de perguntas e scorecards.</b></li>
               <li><b> RE-054: </b> O sistema deve exibir métricas gerais do processo seletivo em um dashboard centralizado, incluindo status de candidatos e insights sobre o funil de recrutamento.</b></li>
            </ul> 
        </td>
    </tr>
    <tr>
        <th>Ações</th>
        <td> 
            <ul>
                <li> <b> Desenvolvimento: </b> Os requisitos téncicos devem ser desenvolvidos e estar em versão estável para testes até 21/05/2025.</li>
                <li> <b> Custumer Success: </b> Realizar teste de usabilidade das funcionalidades desenvolvidas de 21/05/2025 até 21/06/2025.</li>
                <li> <b> Desenvolvimento e teste: </b> Corrigir bugs, criar scripts de teste de 21/05/2025 até 21/06/2025.</li>
                <li> <b> Infraestrutura e Segurança: </b> Analisar e colocar em conformidade com LGPD, adicionando as funcionalidades desenvolvidas para produção até 15/07/2025.</li>
                <li> <b> Marketing: </b> Preparar evento de lançamento online para o dia 25/07/2025.</li>
            </ul> 
        </td>
    </tr>
    <tr>
        <th>Datas</th>
        <td> 
            <ul>
                <li> <b> Início: </b> 15/04/2025.</li>
                <li> <b> Fim: </b> 15/07/2025.</li>
                <li> <b> Lançamento: </b> 25/07/2025.</li>
            </ul> 
        </td>
    </tr>
<table>


<table>
    <tr>
        <th colspan="2">Release 03: Integrações e Inteligência artificial</th>
    </tr>
    <tr>
        <th>Objetivo</th>
        <td>Expandir o ecossistema do produto por meio de integrações robustas e inovação com inteligência artificial.</td>
    </tr>
    <tr>
        <th>Requisitos técnicos</th>
        <td> 
            <ul>
                <li> <b> RE-048: </b> Possibilitar a integração com mais ferramentas de terceiros.</li>
                <li><b> RE-044:  </b> Implementar previsões de aceitação de ofertas com aprendizado de máquina.</b></li>
               <li><b> RE-076:  </b>  Adicionar assistente de inteligência artificial para suporte em tempo real.</b></li>
               <li><b> RE-058:  </b>  O sistema deve permitir a sincronização com calendários para agendamento e gerenciamento de entrevistas e eventos relacionados ao recrutamento.</b></li>
            </ul> 
        </td>
    </tr>
    <tr>
        <th>Ações</th>
        <td> 
            <ul>
                <li> <b> Desenvolvimento: </b> Os requisitos téncicos devem ser desenvolvidos e estar em versão estável para testes até 03/11/2025.</li>
                <li> <b> Custumer Success: </b> Realizar teste de usabilidade das funcionalidades desenvolvidas de 03/11/2025 até 24/11/2025.</li>
                <li> <b> Desenvolvimento e teste: </b> Corrigir bugs, criar scripts de teste de 03/11/2025 até 24/11/2025.</li>
                <li> <b> Infraestrutura e Segurança: </b> Analisar e colocar em conformidade com LGPD, adicionando as funcionalidades desenvolvidas para produção até 12/01/2026.</li>
                <li> <b> Marketing: </b> Preparar evento de lançamento online para o dia 25/01/2026.</li>
            </ul> 
        </td>
    </tr>
    <tr>
        <th>Datas</th>
        <td> 
            <ul>
                <li> <b> Início: </b> 25/07/2025.</li>
                <li> <b> Fim: </b> 12/01/2026.</li>
                <li> <b> Lançamento: </b> 25/01/2026.</li>
            </ul> 
        </td>
    </tr>
<table>

## Histórico de versão

| Versão | Data | Descrição | Autor(es) |
| :-: | :-: | :-: | :-: |
| `1.0` | 10/11/2024 | Criação do artefato de three-level scale | Vitor Feijó |
| `1.1` | 17/11/2024 | Preenchimento do artefato | Vitor Feijó |