# Projeto_NeoDesk
![NeoDESK](icon/iconBack.png)


Repositório para documentação do projeto integrado multidisciplinar, sistema orientado objeto em desenvolvimento, e para hábito de boas práticas

## Backlog
Gerenciamento de Usuários
Como administrador, quero cadastrar usuários, para que possam acessar o sistema.
Como administrador, quero editar informações de usuários, para manter os dados atualizados.
Como administrador, quero remover usuários, para controlar quem tem acesso.
Como usuário, quero alterar minha própria senha, para manter minha conta segura.

Critérios de Aceitação: Todas as operações devem ser feitas via API e refletidas no banco MySQL.

Gestão de Chamados
Como usuário, quero abrir um chamado, para solicitar suporte.
Como técnico, quero atualizar o status do chamado (Aberto, Em Andamento, Fechado), para acompanhar o progresso.
Como administrador, quero visualizar todos os chamados, para controlar o fluxo de suporte.
Como usuário, quero anexar informações adicionais ao chamado, para detalhar o problema.

Critérios de Aceitação: Chamados vinculados a usuários, departamentos e categorias; atualização refletida em tempo real na API.

Departamentos e Categorias
Como administrador, quero cadastrar departamentos, para organizar chamados.
Como administrador, quero criar categorias de chamados, para classificar os problemas.
Como administrador, quero editar e remover departamentos/categorias, para manter a organização atualizada.

API e Banco de Dados
Como desenvolvedor, quero uma API REST em Node.js, para disponibilizar os dados para o front-end.
Como desenvolvedor, quero conectar a API ao MySQL, para persistir dados de forma segura.
Como desenvolvedor, quero implementar rotas CRUD para todas as entidades (Usuários, Chamados, Departamentos, Categorias), para permitir todas as operações do sistema.
Como desenvolvedor, quero testar a API com dados de exemplo, para garantir que todas as operações funcionem.


## Diagramas
Os diagramas foram criados no **Astah** e podem ser acessados pelos links abaixo:

- [Diagrama de Casos de Uso](https://1drv.ms/u/c/654cf350b11023d3/EdZe9LOuJtVAv6EZlYtWScEB0ktooReMP8pZ5GvsHBILuw?e=cVUog2)

## Protótipo de tela
O protótipo de tela do software que será desenvolvido foi feito utilizando o figma, para praticidade na modelagem e testes de usabilidade
    
- [Modelo Desktop/Web](https://www.figma.com/proto/PNPPrRL9X2HOf28W2uVfBA/NeoDesk?node-id=317-414&starting-point-node-id=317%3A414&scaling=scale-down&content-scaling=fixed&t=I6LKXuKYxbPHIr7W-1)

## Sistema Mobile
O sistema está sendo programado utilizando React Native(EXPO) como ferramenta de desenvolvimento e javascript/typescript como linguagem de programação

- [Repositório](https://github.com/manopassaro/NeoDeskApp)

## 📅 Planejamento das Sprints

| Sprint  | Período        | Entregas / Atividades                                                                 |
|---------|----------------|----------------------------------------------------------------------------------------|
| Sprint 1 | 12/08 - 26/08 | ✅ Criar repositório com boas práticas <br> ✅ Apresentar diagramas de caso de uso (Diagrama de Casos de Uso) |
| Sprint 2 | 27/08 - 10/09 | ✅ Aplicação de boas práticas ao README <br> ✅ Estudo e desenvolvimento da API <br> ✅ Protótipo de tela (modelo Desktop/Web) |
| Sprint 3 | 11/09 - 23/09 | ✅ Criação do frontend versão mobile do sistema <br> ✅ Integração com API              |
| Sprint 4 | 24/09 - 07/10 | ✅ Desenvolvimento do front versão Mobile <br> ✅ Implementação do banco de dados a API                                                                                  |
| Sprint 5 | dd/mm - dd/mm | ⬜ ...                                                                                  |

---

> Desenvolvido por: Luiz Miguel Lemes da Silva, Renan Nogueira Ribeiro, Lucas Antônio Goulart Souto, Pedro Henrique Rodrigues de Souza, Lívia Vieira Jacó
