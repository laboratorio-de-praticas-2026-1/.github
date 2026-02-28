Portal de Despachante

### Descrição do Projeto

O **Portal de Despachante** é uma plataforma digital que tem como principal objetivo facilitar a regularização de documentos de veículos e condutores. Nosso foco é oferecer uma experiência de usuário intuitiva e completa, desde a consulta de débitos (IPVA, licenciamento, multas) até a solicitação de serviços e agendamento de retiradas.

## Cronograma

<details>
<summary><strong>Kick-off e Planejamento Inicial</strong></summary>

- **Data:** 28 de fevereiro.
</details>

<details>
<summary><strong>Entregas obrigatórias</strong></summary>

Semanalmente, deverá ser entregue o vídeo das dailies entre os PMs, apresentando os resultados da semana. O vídeo deverá ter de 2 a 5 minutos no máximo. Precisará ser claro e objetivo nos resultados. A nota final será composta com base nas entregas apresentadas nessas gravações. A ausência do vídeo semanal resultará em nota zero para todas as squads do projeto naquela semana. Além disso, a não participação do PM (ou de um PO que o represente em caso de ausência) também acarretará nota zero na atividade para todos os integrantes do time do PM.

Cronograma:
- **12/03** - Apresentação do Design System + Front (Header e Carrossel)
- **26/03** - Front + Vitrine, CMS Blog + Busca Simples e Avançada
- **09/04** - Agendamento de Serviço/Retirada + Chat + Contato + Vitrine e CMS Publicidade
- **23/04** - Dashboard + Reports em PDF + Vitrine e CMS Serviços + Login e Cadastro + CMS Usuários
- **04/05** - FAQ + Simulador de Débitos e Parcelamento + Mapa de Parceiros e Clínicas + Notificação de Prazos + Data Science (Recomendação)

> Local para depósito dos vídeos:
link [aqui](https://drive.google.com/drive/folders/12wETeClzz4f98CGMoNyPgRRAXvlRLicb?usp=sharing)

> Sintaxe para nome do arquivo (exemplo):
2026-03-16-daily-01-apresentacao_ux
</details>

<details>
<summary><strong>Atualizações de Andamento</strong></summary>

As atualizações ocorrerão nas seguintes datas:

| Data Limite | Produto | Squad | O que deve ser entregue |
| :--- | :--- | :--- | :--- |
| **12/03** | Matricial | **Squad UX** | Apresentação dos protótipos de alta fidelidade e fluxos de navegação. |
| **12/03** | Matricial / Core | **Squad Front** & **Squad Header e Carrossel** | Implementação inicial do front-end com foco no cabeçalho e carrossel de serviços. |
| **26/03** | Matricial | **Squad Front** | Continuação e refinamento das interfaces de usuário principais. |
| **26/03** | Conteúdo e Mkt | **Squad Vitrine e CMS Blog** | Telas de exibição do blog e painel administrativo para publicações. |
| **26/03** | Core | **Squad Busca Simples e Avançada** | Funcionalidade de busca por placa/Renavam e filtros avançados. |
| **09/04** | CX | **Squad Agendamento de Serviço/Retirada** | Sistema para marcação de horários de retirada de documentos ou serviços. |
| **09/04** | CX | **Squad Chat** | Implementação da ferramenta de comunicação em tempo real. |
| **09/04** | CX | **Squad Contato** | Formulários e informações de atendimento ao cliente. |
| **09/04** | Conteúdo e Mkt | **Squad Vitrine e CMS Publicidade** | Espaços para anúncios de parceiros e painel de gestão das campanhas. |
| **23/04** | Dados | **Squad Dashboard** | Painel de controle gerencial com métricas de processos e faturamento. |
| **23/04** | Dados | **Squad Reports em PDF** | Geração e download de recibos e relatórios de andamento de débitos. |
| **23/04** | Core | **Squad Vitrine e CMS Serviços** | Catálogo de serviços do despachante e painel de edição de taxas. |
| **23/04** | Core | **Squad Login e Cadastro de Usuários** | Fluxo completo de autenticação e registro de clientes. |
| **23/04** | Core | **Squad Squad Login e Cadastro de Usuários** | Painel administrativo para gestão dos perfis de clientes da plataforma. |
| **04/05** | CX | **Squad FAQ** | Página com respostas às dúvidas frequentes e documentação necessária. |
| **04/05** | Engajamento | **Squad Simulador de Débitos** | Calculadora de IPVA, multas, taxas e simulação de parcelamentos. |
| **04/05** | Engajamento | **Squad Mapa de Parceiros e Clínicas** | Mapa interativo com clínicas do Detran e locais de vistoria credenciados. |
| **04/05** | Engajamento | **Squad Notificação de Prazos** | Alertas para vencimento de CNH, licenciamento e novos débitos. |
| **04/05** | Dados | **Squad Data Science (Recomendação)** | Algoritmo sugerindo serviços proativos baseados no perfil do condutor/veículo. |
</details>

<details>
<summary><strong>Entrega Final</strong></summary>

- **Data:** 04 de maio.
- **Objetivo:** Entregar o sistema completo, com todas as funcionalidades implementadas e testadas.
</details>

---

## Produtos e Funcionalidades

### 1. Produto Core

#### 1.1 Squad Header e Carrossel
- **Como um visitante do site**, eu quero ver um cabeçalho claro e um carrossel de imagens atraentes dos serviços oferecidos, para que eu possa ter uma boa primeira impressão e me orientar no site.

#### 1.2 Squad Busca Simples e Avançada
- **Como um proprietário de veículo ou condutor**, eu quero usar uma barra de busca simples (ex: por placa ou Renavam) e uma busca avançada com filtros, para que eu possa encontrar rapidamente meus débitos ou o serviço específico que necessito.

#### 1.3 Squad Login e Cadastro de Usuários
- **Como um novo cliente**, eu quero me cadastrar de forma fácil, para que eu possa acessar funcionalidades exclusivas, como acompanhamento de processos e pagamentos.
- **Como um cliente já cadastrado**, eu quero fazer login com segurança, para que eu possa gerenciar minhas solicitações e documentos.
- **Como um administrador**, eu quero gerenciar os perfis dos clientes, para que eu possa manter a plataforma segura e com dados corretos.

---

### 2. Produto Dados

#### 2.1 Squad Data Science - Recomendação
- **Como um usuário**, eu quero receber recomendações de serviços personalizadas com base no meu perfil (ex: aviso de renovação de CNH próxima ou seguro obrigatório), para que eu evite multas e mantenha tudo regularizado.

#### 2.2 Squad Engenharia de Dados / Backend
- **Como um desenvolvedor**, eu quero que o servidor seja feito no mesmo projeto e que o banco de dados usado seja um local por enquanto, para que a configuração inicial seja ágil e estruturada.
- **Como um analista**, eu quero ter acesso fácil e seguro aos dados, para que eu possa gerar relatórios e insights de serviços realizados.

#### 2.3 Squad Dashboard
- **Como um gestor**, eu quero ter um painel de controle (dashboard) com métricas importantes (processos em andamento, concluídos, faturamento), para que eu possa monitorar a operação do despachante e tomar decisões estratégicas.

#### 2.4 Squad Reports em PDF
- **Como um cliente/gestor**, eu quero gerar relatórios e recibos em PDF sobre os débitos pagos ou andamento de processos, para que eu possa ter comprovantes documentados.

---

### 3. Produto Conteúdo e Marketing

#### 3.1 Squad Vitrine e CMS Blog
- **Como um visitante**, eu quero ler artigos no blog sobre novas leis de trânsito, dicas de manutenção preventiva e regras do IPVA, para que eu possa me manter informado.
- **Como um gestor de conteúdo**, eu quero usar um CMS para publicar e gerenciar posts do blog, para que o conteúdo seja sempre relevante e atualizado.

#### 3.2 Squad Vitrine e CMS Publicidade
- **Como um parceiro (ex: vistoria veicular, seguradora)**, eu quero ter espaços para publicidade no site, para que eu possa divulgar meus serviços.
- **Como um gestor de marketing**, eu quero usar um CMS para gerenciar os anúncios, para que eu possa otimizar as campanhas.

#### 3.3 Squad Vitrine e CMS Serviços
- **Como um visitante**, eu quero ver uma vitrine com a descrição dos serviços disponíveis (transferência, licenciamento, renovação de CNH), para que eu entenda o que o despachante oferece.
- **Como um administrador**, eu quero usar um CMS para cadastrar, editar, pausar e remover serviços e alterar taxas, para que o portfólio esteja sempre atualizado e preciso.

---

### 4. Produto Matricial

#### 4.1 Squad UX
- **Como um usuário**, eu quero que a navegação do site seja intuitiva e agradável, para que eu consiga solicitar serviços burocráticos sem frustração.

#### 4.2 Squad Front
- **Como um usuário**, eu quero que o site seja responsivo e funcione bem em qualquer dispositivo (computador, celular), para que eu possa acessá-lo de onde eu estiver.
- **Como um desenvolvedor**, eu quero poder utilizar qualquer tecnologia ministrada no curso para construir um código de front-end limpo e bem documentado, garantindo manutenção eficiente.

#### 4.3 Squad Devops
- **Como um desenvolvedor**, eu quero um ambiente de desenvolvimento e produção automatizado, tendo como requisito estar hospedado no GitHub Pages, Vercel ou outro site de hospedagem de escolha, para que a entrega seja rápida e acessível.
- **Como um gestor**, eu quero que o site tenha alta disponibilidade e escalabilidade, para que suporte acessos em épocas de vencimento de IPVA.

---

### 5. Produto Engajamento e Retenção

#### 5.1 Squad Simulador de Débitos e Parcelamento
- **Como um proprietário de veículo**, eu quero usar um simulador para calcular o custo total de regularização (IPVA + Multas + Taxas do Despachante) e simular parcelamentos, para que eu possa planejar minhas finanças.

#### 5.2 Squad Notificação de Prazos
- **Como um cliente cadastrado**, eu quero receber notificações sobre o vencimento da minha CNH, prazo final do licenciamento ou novos débitos atrelados à minha placa, para não perder prazos legais.

#### 5.3 Squad Mapa de Parceiros e Clínicas
- **Como um cliente**, eu quero visualizar em um mapa interativo as clínicas credenciadas (para exame médico/psicotécnico), empresas de vistoria parceiras e unidades do Detran, para facilitar meu deslocamento.

---

### 6. Produto Customer Experience (CX)

#### 6.1 Squad Contato
- **Como um visitante**, eu quero encontrar informações de contato claras, como WhatsApp, telefone e e-mail, para que eu possa tirar dúvidas com a equipe do despachante.

#### 6.2 Squad Agendamento de Serviço/Retirada
- **Como um cliente**, eu quero agendar um horário para entregar documentos físicos, realizar biometria (se aplicável) ou retirar meus documentos prontos diretamente pelo site, para evitar filas.

#### 6.3 Squad FAQ
- **Como um visitante**, eu quero ter acesso a uma seção de perguntas frequentes (FAQ), para que eu possa encontrar respostas rápidas sobre documentação necessária para cada processo.

#### 6.4 Squad Chat
- **Como um visitante ou cliente**, eu quero usar um chat para falar com um atendente em tempo real, para que eu possa resolver dúvidas sobre processos travados no Detran de forma ágil.

---

## Banco de dados

### Diagrama ER do Sistema
DOING

### Script SQL
DOING

## Avaliação

### Entrega dos Vídeos

Semanalmente, deverá ser entregue o vídeo das dailies entre os PMs, apresentando os resultados da semana. O vídeo deverá ter de 2 a 5 minutos no máximo. Precisará ser clara e objetivo nos resultados. A nota final será composta com base nas entregas apresentadas nessas gravações. A ausência do vídeo semanal resultará em nota zero para todas as squads do projeto naquela semana. Além disso, a não participação do PM (ou de um PO que o represente em caso de ausência) também acarretará nota zero na atividade para todos os integrantes do time do PM.

---

### Avaliação 360º

A **avaliação 360º** é um processo realizado entre todos os membros de cada **PRODUTO**. Nessa avaliação, existem perguntas baseadas em uma escala de desempenho:

* **Abaixo das expectativas**
* **Atendeu às expectativas**
* **Superou as expectativas**

Essa escala é utilizada para avaliar a participação individual, o cumprimento de prazos de entrega e o nível de comprometimento de cada membro com o projeto.

---

### Feedback do PM

O **PM (Product Manager)** fornecerá uma visão estratégica sobre a execução das demandas em cada produto. A partir dessa análise, o PM avaliará o produto de forma geral, considerando o desempenho de cada companheiro de equipe.

---

### Nota Distributiva

Com base na análise das avaliações anteriores (**entrega dos vídeos**, **avaliação 360º** e **feedback do PM**), o colegiado dos professores responsáveis pelas disciplinas-chave determinará uma **nota final** para o produto/squad. Essa nota deverá ser distribuída entre todos os membros do grupo por meio de um **comum acordo**, levando em consideração o desempenho individual de cada discente ao longo do projeto. A **Nota Final Professores** validada neste processo é a nota oficial que será inserida no sistema SIGA.

## Ferramentas Utilizadas

<details>
<summary><strong>Lista de Ferramentas</strong></summary>

- **Gestão de Projeto:** GitHub (Projects).  
- **Desenvolvimento:** GitHub (versionamento), Docker (conteinerização), Vercel, GitHub Pages ou outro site de hospedagem à escolha (Hospedagem obrigatória do Front).  
- **Testes:** Ferramentas de teste de usabilidade e segurança.  
</details>
