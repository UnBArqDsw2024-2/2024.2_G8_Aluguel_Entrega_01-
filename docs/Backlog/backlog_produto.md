# Backlog do Produto

## Introdução

O backlog do produto é uma ferramenta da gestão de projetos ágeis, servindo como um repositório dinâmico de requisitos e funcionalidades que devem ser desenvolvidas.
Este documento apresenta o backlog para HostHub, que abrange diversas funcionalidades organizadas em épicos, features,histórias de usuários e as tarefas do primeiro épico. Através deste backlog, a equipe de desenvolvimento poderá priorizar e gerenciar as tarefas necessárias para entregar um produto que atenda às necessidades dos usuários.

## Objetivo

O objetivo deste artefato é proporcionar uma visão clara e estruturada das funcionalidades planejadas para a plataforma HostHub. Isso facilitará a comunicação entre os membros da equipe e permitirá um planejamento eficaz das iterações.

## Metodologia

A metodologia utilizada para a elaboração deste backlog segue os princípios do Scrum, uma abordagem ágil que enfatiza a colaboração e a entrega incremental de valor.
A equipe elaborou o backlog durante uma reunião no Discord, onde discutiu e coletou as histórias de usuários. Para facilitar a colaboração e deixar a reunião interativa, foi usada a ferramenta Miro. Porém, optamos por organizar o backlog em formato de tabela no documento final, para facilitar a visualização rápida e o acompanhamento das tarefas planejadas.

## Backlog

<table>
    <thead>
        <tr>
            <th>ÉPICO</th>
            <th>FEATURE</th>
            <th>HISTÓRIA DE USUÁRIO (US)</th>
            <th>TAREFAS</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan="5">Gestão de Usuários</td>
            <td rowspan="2">Cadastro e Login de Usuários</td>
            <td>US1: Como usuário, quero me cadastrar para acessar as funcionalidades da plataforma.</td>
            <td>
                - Desenvolver tela de cadastro com campos necessários (nome, data de nascimento, CPF/CNPJ, email, senha, confirmar senha e foto).<br>
                - Validar entrada dos dados no cadastro.<br>
                - Implementar mensagens de erro em caso de falha no cadastro.<br>
                - Desenvolver back-end para receber e processar dados, salvando no banco de dados.<br>
                - Criar tabela "Usuários" no banco de dados com os campos necessários.
            </td>
        </tr>
        <tr>
            <td>US2: Como usuário, quero realizar meu login para acessar as funcionalidades da plataforma.</td>
            <td>
                - Desenvolver tela de login.<br>
                - Implementar funcionalidade de login.<br>
                - Exibir mensagens de erro em caso de falha.
            </td>
        </tr>
        <tr>
            <td rowspan="3">Edição do Perfil de Usuário</td>
            <td>US3: Como usuário, quero recuperar minha senha para poder recuperar a minha conta caso necessário.</td>
            <td>
                - Desenvolver tela para recuperação de senha.<br>
                - Implementar funcionalidade para recuperação de senha.
            </td>
        </tr>
        <tr>
            <td>US4: Como usuário, quero atualizar minhas informações cadastradas para manter meu perfil atualizado.</td>
            <td>
                - Desenvolver tela de edição de perfil (dados e foto).<br>
                - Validar entrada dos dados na edição.
            </td>
        </tr>
        <tr>
            <td>US5: Como usuário, quero poder excluir minha conta para não ser incomodado.</td>
            <td>
                - Implementar botão para exclusão de conta na tela de edição de usuário.
            </td>
        </tr>
        <tr>
            <td rowspan="2">Gestão de Anúncios</td>
            <td>Publicação</td>
            <td>US6: Como usuário, quero criar e publicar anúncios de imóveis, incluindo fotos, vídeos e descrições, para disponibilizá-los para os interessados.</td>
            <td>
            </td>
        </tr>
        <tr>
            <td>Gerenciamento de Anúncios</td>
            <td>US7: Como usuário, quero gerenciar meus anúncios, ver estatísticas de visualização e responder mensagens dos interessados.</td>
            <td>
            </td>
        </tr>
        <tr>
            <td rowspan="3">Busca e Visualização de Imóveis</td>
            <td rowspan="2">Busca e Filtro</td>
            <td>US8: Como usuário, quero realizar filtros por preço, categoria, quantidade de quartos e localidade durante minha pesquisa por imóveis.</td>
            <td>
            </td>
        </tr>
        <tr>
            <td>US9: Como usuário, quero realizar buscas por imóveis para verificar as opções disponíveis.</td>
            <td>
            </td>
        </tr>
        <tr>
            <td>Visualização</td>
            <td>US10: Como usuário, quero visualizar informações detalhadas dos imóveis para saber mais sobre as opções apresentadas.</td>
            <td>
            </td>
        </tr>
        <tr>
            <td rowspan="6">Avaliação e Feedbacks</td>
            <td rowspan="4">Avaliação de Anúncios</td>
            <td>US11: Como usuário, quero deixar feedbacks sobre os imóveis para ajudar outros usuários.</td>
            <td>
            </td>
        </tr>
        <tr>
            <td>US12: Como usuário, quero avaliar imóveis para expressar minha satisfação.</td>
            <td>
            </td>
        </tr>
        <tr>
            <td>US13: Como usuário, quero visualizar avaliações feitas por outros usuários sobre os imóveis.</td>
            <td>
            </td>
        </tr>
        <tr>
            <td>US14: Como usuário, quero responder avaliações ou feedbacks para esclarecer dúvidas ou agradecer.</td>
            <td>
            </td>
        </tr>
        <tr>
            <td rowspan="2">Favoritar Anúncios</td>
            <td>US15: Como usuário, quero favoritar anúncios para acessá-los rapidamente depois.</td>
            <td>
            </td>
        </tr>
        <tr>
            <td>US16: Como usuário, quero desfavoritar anúncios que não sejam mais de interesse.</td>
            <td>
            </td>
        </tr>
        <tr>
            <td rowspan="2">Comunicação entre Usuários</td>
            <td>Notificar Usuário</td>
            <td>US17: Como usuário, quero receber notificações de novas mensagens para saber quando alguém entra em contato comigo.</td>
            <td>
            </td>
        </tr>
        <tr>
            <td>Chat de Mensagens</td>
            <td>US18: Como usuário, quero enviar mensagens para outros usuários para discutir detalhes dos imóveis.</td>
            <td>
            </td>
        </tr>
    </tbody>
</table>


## Conclusão

O backlog do produto apresentado neste documento é uma ferramenta que orientará o desenvolvimento da plataforma HostHub. Ao organizar as funcionalidades em épicos, features e histórias de usuários, a equipe pode priorizar as tarefas com base nas necessidades dos usuários e garantir uma entrega contínua e incrementada.

## Referências Bibliográficas

- SCRUM Alliance. Scrum Guide. Disponível em: https://www.scrumguides.org/scrum-guide.html. Acesso em: 28 nov. 2024.

## Histórico de Versão

| Versão |    Data    |         Descrição          |  Autor(es)  |
| :----: | :--------: | :------------------------: | :---------: |
| `1.0`  | 27/11/2024 | Elaboração do Backlog do Produto | [Caio Berg](https://github.com/Caio-bergbjj), [Ester Lino](https://github.com/esteerlino), [Gabriel Marcolino](https://github.com/GabrielMR360), [Gabriela Tiago](https://github.com/GabrielaTiago), [Lucas Macedo](https://github.com/Luckx98), [Miguel Moreira](https://github.com/EhOMiguel), [Pedro Sena](https://github.com/pedroyen21), [Shaíne Oliveira](https://github.com/ShaineOliveira) |
| `1.1`  | 28/11/2024 | Criação do documento | [Ester Lino](https://github.com/esteerlino) |
