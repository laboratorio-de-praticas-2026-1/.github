## Portal de Despachante

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
- **26/03** - Front + Vitrine, CMS Blog + Busca Simples e Avançada + CMS (Header e Carrossel)
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
| **23/04** | Dados | **Squad Engenharia de Dados e Dashboard** | Painel de controle gerencial com métricas de processos e faturamento. |
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

#### 2.2 Squad Engenharia de Dados e Dashboard
- **Como um desenvolvedor**, eu quero que o servidor seja feito no mesmo projeto e que o banco de dados usado seja um local por enquanto, para que a configuração inicial seja ágil e estruturada.
- **Como um analista**, eu quero ter acesso fácil e seguro aos dados, para que eu possa gerar relatórios e insights de serviços realizados.
- **Como um gestor**, eu quero ter um painel de controle (dashboard) com métricas importantes (processos em andamento, concluídos, faturamento), para que eu possa monitorar a operação do despachante e tomar decisões estratégicas.

#### 2.3 Squad Reports em PDF
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
![ER_BANCO_DE_DADOS](https://github.com/user-attachments/assets/9307ba44-e57e-48d5-958d-a05af060601f)


### Script SQL
<details>

<summary>lp_despachante_dump_empty</summary>

```sql
   -- --------------------------------------------------------
-- Servidor:                     127.0.0.1
-- Versão do servidor:           10.4.32-MariaDB - mariadb.org binary distribution
-- OS do Servidor:               Win64
-- HeidiSQL Versão:              12.3.0.6589
-- --------------------------------------------------------

/*!40101 SET @OLD_CHARACTER_SET_CLIENT=@@CHARACTER_SET_CLIENT */;
/*!40101 SET NAMES utf8 */;
/*!50503 SET NAMES utf8mb4 */;
/*!40103 SET @OLD_TIME_ZONE=@@TIME_ZONE */;
/*!40103 SET TIME_ZONE='+00:00' */;
/*!40014 SET @OLD_FOREIGN_KEY_CHECKS=@@FOREIGN_KEY_CHECKS, FOREIGN_KEY_CHECKS=0 */;
/*!40101 SET @OLD_SQL_MODE=@@SQL_MODE, SQL_MODE='NO_AUTO_VALUE_ON_ZERO' */;
/*!40111 SET @OLD_SQL_NOTES=@@SQL_NOTES, SQL_NOTES=0 */;


-- Copiando estrutura do banco de dados para lp_despachante_portal
CREATE DATABASE IF NOT EXISTS `lp_despachante_portal` /*!40100 DEFAULT CHARACTER SET utf8mb4 COLLATE utf8mb4_general_ci */;
USE `lp_despachante_portal`;

-- Copiando estrutura para tabela lp_despachante_portal.banner
CREATE TABLE IF NOT EXISTS `banner` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `url_imagem` varchar(255) DEFAULT NULL,
  `descricao` varchar(255) DEFAULT NULL,
  `ativo` tinyint(1) DEFAULT 1,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=11 DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

-- Exportação de dados foi desmarcado.

-- Copiando estrutura para tabela lp_despachante_portal.blog
CREATE TABLE IF NOT EXISTS `blog` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `titulo` varchar(150) DEFAULT NULL,
  `conteudo` text DEFAULT NULL,
  `data_publicacao` date DEFAULT NULL,
  `url_imagem` varchar(255) DEFAULT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=11 DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

-- Exportação de dados foi desmarcado.

-- Copiando estrutura para tabela lp_despachante_portal.documento_solicitacao
CREATE TABLE IF NOT EXISTS `documento_solicitacao` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `solicitacao_id` int(11) NOT NULL,
  `nome_hash` varchar(255) DEFAULT NULL,
  `tipo_documento` varchar(100) DEFAULT NULL,
  `status_validacao` enum('pendente','aprovado','rejeitado') DEFAULT 'pendente',
  `data_upload` timestamp NULL DEFAULT NULL,
  PRIMARY KEY (`id`),
  KEY `fk_documento_solicitacao` (`solicitacao_id`),
  CONSTRAINT `fk_documento_solicitacao` FOREIGN KEY (`solicitacao_id`) REFERENCES `solicitacao` (`id`) ON DELETE CASCADE
) ENGINE=InnoDB AUTO_INCREMENT=11 DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

-- Exportação de dados foi desmarcado.

-- Copiando estrutura para tabela lp_despachante_portal.empresa
CREATE TABLE IF NOT EXISTS `empresa` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `nome_fantasia` varchar(100) DEFAULT NULL,
  `cnpj` varchar(20) DEFAULT NULL,
  `telefone` varchar(20) DEFAULT NULL,
  `email` varchar(100) DEFAULT NULL,
  `endereco` varchar(255) DEFAULT NULL,
  `cidade` varchar(100) DEFAULT NULL,
  `estado` varchar(2) DEFAULT NULL,
  `site` varchar(100) DEFAULT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=2 DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

-- Exportação de dados foi desmarcado.

-- Copiando estrutura para tabela lp_despachante_portal.faq
CREATE TABLE IF NOT EXISTS `faq` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `pergunta` text DEFAULT NULL,
  `resposta` text DEFAULT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=11 DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

-- Exportação de dados foi desmarcado.

-- Copiando estrutura para tabela lp_despachante_portal.publicidade
CREATE TABLE IF NOT EXISTS `publicidade` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `titulo` varchar(150) DEFAULT NULL,
  `conteudo` text DEFAULT NULL,
  `url_imagem` varchar(255) DEFAULT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=11 DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

-- Exportação de dados foi desmarcado.

-- Copiando estrutura para tabela lp_despachante_portal.servico
CREATE TABLE IF NOT EXISTS `servico` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `nome` varchar(100) NOT NULL,
  `descricao` text DEFAULT NULL,
  `valor_base` decimal(10,2) DEFAULT NULL,
  `prazo_estimado_dias` int(11) DEFAULT NULL,
  `ativo` tinyint(1) DEFAULT 1,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=11 DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

-- Exportação de dados foi desmarcado.

-- Copiando estrutura para tabela lp_despachante_portal.solicitacao
CREATE TABLE IF NOT EXISTS `solicitacao` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `usuario_id` int(11) NOT NULL,
  `veiculo_id` int(11) NOT NULL,
  `servico_id` int(11) NOT NULL,
  `status` enum('recebido','aguardando_pagamento','aguardando_documento','em_andamento','concluido','cancelado') DEFAULT 'recebido',
  `observacao_cliente` text DEFAULT NULL,
  `observacao_admin` text DEFAULT NULL,
  `data_solicitacao` datetime DEFAULT current_timestamp(),
  `data_conclusao` datetime DEFAULT NULL,
  PRIMARY KEY (`id`),
  KEY `fk_solicitacao_usuario` (`usuario_id`),
  KEY `fk_solicitacao_veiculo` (`veiculo_id`),
  KEY `fk_solicitacao_servico` (`servico_id`),
  CONSTRAINT `fk_solicitacao_servico` FOREIGN KEY (`servico_id`) REFERENCES `servico` (`id`),
  CONSTRAINT `fk_solicitacao_usuario` FOREIGN KEY (`usuario_id`) REFERENCES `usuario` (`id`) ON DELETE CASCADE,
  CONSTRAINT `fk_solicitacao_veiculo` FOREIGN KEY (`veiculo_id`) REFERENCES `veiculo` (`id`) ON DELETE CASCADE
) ENGINE=InnoDB AUTO_INCREMENT=11 DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

-- Exportação de dados foi desmarcado.

-- Copiando estrutura para tabela lp_despachante_portal.usuario
CREATE TABLE IF NOT EXISTS `usuario` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `nome` varchar(100) NOT NULL,
  `email` varchar(100) NOT NULL,
  `senha` varchar(255) NOT NULL,
  `nivel` enum('cliente','administrador') DEFAULT 'cliente',
  `cpf_cnpj` varchar(20) DEFAULT NULL,
  `celular` varchar(20) DEFAULT NULL,
  `data_cadastro` datetime DEFAULT current_timestamp(),
  PRIMARY KEY (`id`),
  UNIQUE KEY `email` (`email`)
) ENGINE=InnoDB AUTO_INCREMENT=11 DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

-- Exportação de dados foi desmarcado.

-- Copiando estrutura para tabela lp_despachante_portal.veiculo
CREATE TABLE IF NOT EXISTS `veiculo` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `usuario_id` int(11) NOT NULL,
  `placa` varchar(10) NOT NULL,
  `renavam` varchar(20) DEFAULT NULL,
  `marca` varchar(50) DEFAULT NULL,
  `modelo` varchar(50) DEFAULT NULL,
  `ano_fabricacao` int(11) DEFAULT NULL,
  `ano_modelo` int(11) DEFAULT NULL,
  PRIMARY KEY (`id`),
  KEY `fk_veiculo_usuario` (`usuario_id`),
  CONSTRAINT `fk_veiculo_usuario` FOREIGN KEY (`usuario_id`) REFERENCES `usuario` (`id`) ON DELETE CASCADE
) ENGINE=InnoDB AUTO_INCREMENT=11 DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

-- Exportação de dados foi desmarcado.

/*!40103 SET TIME_ZONE=IFNULL(@OLD_TIME_ZONE, 'system') */;
/*!40101 SET SQL_MODE=IFNULL(@OLD_SQL_MODE, '') */;
/*!40014 SET FOREIGN_KEY_CHECKS=IFNULL(@OLD_FOREIGN_KEY_CHECKS, 1) */;
/*!40101 SET CHARACTER_SET_CLIENT=@OLD_CHARACTER_SET_CLIENT */;
/*!40111 SET SQL_NOTES=IFNULL(@OLD_SQL_NOTES, 1) */;

```

</details>

<details>

<summary>lp_despachante_dump</summary>

```sql
   -- --------------------------------------------------------
-- Servidor:                     127.0.0.1
-- Versão do servidor:           10.4.32-MariaDB - mariadb.org binary distribution
-- OS do Servidor:               Win64
-- HeidiSQL Versão:              12.3.0.6589
-- --------------------------------------------------------

/*!40101 SET @OLD_CHARACTER_SET_CLIENT=@@CHARACTER_SET_CLIENT */;
/*!40101 SET NAMES utf8 */;
/*!50503 SET NAMES utf8mb4 */;
/*!40103 SET @OLD_TIME_ZONE=@@TIME_ZONE */;
/*!40103 SET TIME_ZONE='+00:00' */;
/*!40014 SET @OLD_FOREIGN_KEY_CHECKS=@@FOREIGN_KEY_CHECKS, FOREIGN_KEY_CHECKS=0 */;
/*!40101 SET @OLD_SQL_MODE=@@SQL_MODE, SQL_MODE='NO_AUTO_VALUE_ON_ZERO' */;
/*!40111 SET @OLD_SQL_NOTES=@@SQL_NOTES, SQL_NOTES=0 */;


-- Copiando estrutura do banco de dados para lp_despachante_portal
DROP DATABASE IF EXISTS `lp_despachante_portal`;
CREATE DATABASE IF NOT EXISTS `lp_despachante_portal` /*!40100 DEFAULT CHARACTER SET utf8mb4 COLLATE utf8mb4_general_ci */;
USE `lp_despachante_portal`;

-- Copiando estrutura para tabela lp_despachante_portal.banner
CREATE TABLE IF NOT EXISTS `banner` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `url_imagem` varchar(255) DEFAULT NULL,
  `descricao` varchar(255) DEFAULT NULL,
  `ativo` tinyint(1) DEFAULT 1,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=11 DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

-- Copiando dados para a tabela lp_despachante_portal.banner: ~10 rows (aproximadamente)
INSERT INTO `banner` (`id`, `url_imagem`, `descricao`, `ativo`) VALUES
	(1, 'https://img.com/banner1.jpg', 'Renove sua CNH sem sair de casa', 1),
	(2, 'https://img.com/banner2.jpg', 'Licenciamento 2026 já disponível', 1),
	(3, 'https://img.com/banner3.jpg', 'Transferência rápida e segura', 1),
	(4, 'https://img.com/banner4.jpg', 'Parcelamento de débitos em até 12x', 1),
	(5, 'https://img.com/banner5.jpg', 'Primeiro emplacamento facilitado', 1),
	(6, 'https://img.com/banner6.jpg', 'Recurso de multa especializado', 1),
	(7, 'https://img.com/banner7.jpg', 'Baixa de gravame simplificada', 1),
	(8, 'https://img.com/banner8.jpg', 'Mudança de categoria CNH', 1),
	(9, 'https://img.com/banner9.jpg', 'Comunicação de venda online', 1),
	(10, 'https://img.com/banner10.jpg', 'Atendimento ágil e digital', 1);

-- Copiando estrutura para tabela lp_despachante_portal.blog
CREATE TABLE IF NOT EXISTS `blog` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `titulo` varchar(150) DEFAULT NULL,
  `conteudo` text DEFAULT NULL,
  `data_publicacao` date DEFAULT NULL,
  `url_imagem` varchar(255) DEFAULT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=11 DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

-- Copiando dados para a tabela lp_despachante_portal.blog: ~10 rows (aproximadamente)
INSERT INTO `blog` (`id`, `titulo`, `conteudo`, `data_publicacao`, `url_imagem`) VALUES
	(1, 'Calendário IPVA 2026', 'Confira as datas de vencimento do IPVA por final de placa.', '2026-01-10', 'https://img.com/blog1.jpg'),
	(2, 'Como recorrer de multa', 'Entenda o passo a passo para apresentar recurso.', '2026-01-15', 'https://img.com/blog2.jpg'),
	(3, 'Transferência de veículo: documentos necessários', 'Veja quais documentos são exigidos.', '2026-01-20', 'https://img.com/blog3.jpg'),
	(4, 'Mudanças na legislação de trânsito', 'Principais alterações no CTB.', '2026-01-25', 'https://img.com/blog4.jpg'),
	(5, 'Licenciamento atrasado: o que fazer?', 'Saiba como regularizar seu veículo.', '2026-02-01', 'https://img.com/blog5.jpg'),
	(6, 'CNH vencida: prazo e penalidades', 'Evite multas e pontos na carteira.', '2026-02-05', 'https://img.com/blog6.jpg'),
	(7, 'Como funciona o parcelamento de débitos', 'Entenda as opções disponíveis.', '2026-02-10', 'https://img.com/blog7.jpg'),
	(8, 'Primeiro emplacamento passo a passo', 'Guia completo para veículos zero km.', '2026-02-15', 'https://img.com/blog8.jpg'),
	(9, 'Baixa de gravame: quando solicitar?', 'Retire restrições financeiras do veículo.', '2026-02-20', 'https://img.com/blog9.jpg'),
	(10, 'Dicas para evitar multas', 'Boas práticas para dirigir com segurança.', '2026-02-25', 'https://img.com/blog10.jpg');

-- Copiando estrutura para tabela lp_despachante_portal.documento_solicitacao
CREATE TABLE IF NOT EXISTS `documento_solicitacao` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `solicitacao_id` int(11) NOT NULL,
  `nome_hash` varchar(255) DEFAULT NULL,
  `tipo_documento` varchar(100) DEFAULT NULL,
  `status_validacao` enum('pendente','aprovado','rejeitado') DEFAULT 'pendente',
  `data_upload` timestamp NULL DEFAULT NULL,
  PRIMARY KEY (`id`),
  KEY `fk_documento_solicitacao` (`solicitacao_id`),
  CONSTRAINT `fk_documento_solicitacao` FOREIGN KEY (`solicitacao_id`) REFERENCES `solicitacao` (`id`) ON DELETE CASCADE
) ENGINE=InnoDB AUTO_INCREMENT=11 DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

-- Copiando dados para a tabela lp_despachante_portal.documento_solicitacao: ~10 rows (aproximadamente)
INSERT INTO `documento_solicitacao` (`id`, `solicitacao_id`, `nome_hash`, `tipo_documento`, `status_validacao`, `data_upload`) VALUES
	(1, 1, 'doc_001.pdf', 'RG', 'aprovado', '2026-03-03 18:19:00'),
	(2, 1, 'doc_002.pdf', 'CRLV', 'aprovado', '2026-03-03 18:19:00'),
	(3, 2, 'doc_003.pdf', 'CPF', 'pendente', '2026-03-03 18:19:00'),
	(4, 3, 'doc_004.pdf', 'Comprovante Residência', 'pendente', '2026-03-03 18:19:00'),
	(5, 4, 'doc_005.pdf', 'CNH', 'aprovado', '2026-03-03 18:19:00'),
	(6, 5, 'doc_006.pdf', 'Contrato Banco', 'pendente', '2026-03-03 18:19:00'),
	(7, 6, 'doc_007.pdf', 'Multa', 'pendente', '2026-03-03 18:19:00'),
	(8, 7, 'doc_008.pdf', 'Comprovante Pagamento', 'aprovado', '2026-03-03 18:19:00'),
	(9, 8, 'doc_009.pdf', 'Laudo Médico', 'pendente', '2026-03-03 18:19:00'),
	(10, 9, 'doc_010.pdf', 'CRV Assinado', 'aprovado', '2026-03-03 18:19:00');

-- Copiando estrutura para tabela lp_despachante_portal.empresa
CREATE TABLE IF NOT EXISTS `empresa` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `nome_fantasia` varchar(100) DEFAULT NULL,
  `cnpj` varchar(20) DEFAULT NULL,
  `telefone` varchar(20) DEFAULT NULL,
  `email` varchar(100) DEFAULT NULL,
  `endereco` varchar(255) DEFAULT NULL,
  `cidade` varchar(100) DEFAULT NULL,
  `estado` varchar(2) DEFAULT NULL,
  `site` varchar(100) DEFAULT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=2 DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

-- Copiando dados para a tabela lp_despachante_portal.empresa: ~1 rows (aproximadamente)
INSERT INTO `empresa` (`id`, `nome_fantasia`, `cnpj`, `telefone`, `email`, `endereco`, `cidade`, `estado`, `site`) VALUES
	(1, 'Despachante Bortone', '12.345.678/0001-99', '1133334444', 'contato@bortone.com', 'Av. Paulista, 1000', 'São Paulo', 'SP', 'www.bortone.com');

-- Copiando estrutura para tabela lp_despachante_portal.faq
CREATE TABLE IF NOT EXISTS `faq` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `pergunta` text DEFAULT NULL,
  `resposta` text DEFAULT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=11 DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

-- Copiando dados para a tabela lp_despachante_portal.faq: ~10 rows (aproximadamente)
INSERT INTO `faq` (`id`, `pergunta`, `resposta`) VALUES
	(1, 'Quais documentos para transferência?', 'CRV assinado, RG, CPF e comprovante de residência.'),
	(2, 'Posso parcelar IPVA?', 'Sim, parcelamos no cartão em até 12x.'),
	(3, 'Quanto tempo demora o licenciamento?', 'Em média 2 dias úteis após pagamento.'),
	(4, 'É possível recorrer de multa online?', 'Sim, mediante envio da documentação necessária.'),
	(5, 'Preciso agendar para atendimento?', 'Não, mas recomendamos agendamento prévio.'),
	(6, 'Posso enviar documentos pelo site?', 'Sim, pela área do cliente.'),
	(7, 'A empresa atende pessoas jurídicas?', 'Sim, atendemos CNPJ também.'),
	(8, 'Qual o prazo para renovação da CNH?', 'Depende da categoria e idade do condutor.'),
	(9, 'Como consultar débitos do veículo?', 'Basta informar placa e RENAVAM na área do cliente.'),
	(10, 'Vocês fazem vistoria?', 'Temos parceria com clínicas credenciadas.');

-- Copiando estrutura para tabela lp_despachante_portal.publicidade
CREATE TABLE IF NOT EXISTS `publicidade` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `titulo` varchar(150) DEFAULT NULL,
  `conteudo` text DEFAULT NULL,
  `url_imagem` varchar(255) DEFAULT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=11 DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

-- Copiando dados para a tabela lp_despachante_portal.publicidade: ~10 rows (aproximadamente)
INSERT INTO `publicidade` (`id`, `titulo`, `conteudo`, `url_imagem`) VALUES
	(1, 'Seguro Auto Completo', 'Proteja seu veículo com nosso parceiro.', 'https://img.com/pub1.jpg'),
	(2, 'Vistoria Cautelar Premium', 'Agende vistoria com desconto exclusivo.', 'https://img.com/pub2.jpg'),
	(3, 'Clínica Médica Credenciada', 'Renove sua CNH com rapidez.', 'https://img.com/pub3.jpg'),
	(4, 'Despachante para Frotas', 'Soluções empresariais completas.', 'https://img.com/pub4.jpg'),
	(5, 'Financiamento Facilitado', 'Parcelamento em até 18x.', 'https://img.com/pub5.jpg'),
	(6, 'Assessoria para Leilão', 'Regularize veículos de leilão.', 'https://img.com/pub6.jpg'),
	(7, 'Consultoria para Empresas', 'Gestão de documentação de frota.', 'https://img.com/pub7.jpg'),
	(8, 'Serviço Express 24h', 'Alguns serviços com prioridade.', 'https://img.com/pub8.jpg'),
	(9, 'App do Cliente', 'Acompanhe tudo pelo celular.', 'https://img.com/pub9.jpg'),
	(10, 'Atendimento Personalizado', 'Suporte especializado para cada caso.', 'https://img.com/pub10.jpg');

-- Copiando estrutura para tabela lp_despachante_portal.servico
CREATE TABLE IF NOT EXISTS `servico` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `nome` varchar(100) NOT NULL,
  `descricao` text DEFAULT NULL,
  `valor_base` decimal(10,2) DEFAULT NULL,
  `prazo_estimado_dias` int(11) DEFAULT NULL,
  `ativo` tinyint(1) DEFAULT 1,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=11 DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

-- Copiando dados para a tabela lp_despachante_portal.servico: ~10 rows (aproximadamente)
INSERT INTO `servico` (`id`, `nome`, `descricao`, `valor_base`, `prazo_estimado_dias`, `ativo`) VALUES
	(1, 'Licenciamento Anual', 'Renovação do CRLV', 180.00, 2, 1),
	(2, 'Transferência de Propriedade', 'Transferência de titularidade', 350.00, 5, 1),
	(3, 'Primeiro Emplacamento', 'Registro veículo zero km', 420.00, 7, 1),
	(4, 'Renovação CNH', 'Renovação carteira de habilitação', 200.00, 10, 1),
	(5, 'Baixa de Gravame', 'Retirada restrição financeira', 190.00, 3, 1),
	(6, 'Recurso de Multa', 'Defesa administrativa', 250.00, 15, 1),
	(7, '2ª Via CRLV', 'Emissão segunda via documento', 120.00, 2, 1),
	(8, 'Mudança de Categoria CNH', 'Alteração categoria habilitação', 600.00, 30, 1),
	(9, 'Comunicação de Venda', 'Registro de venda no Detran', 150.00, 1, 1),
	(10, 'Parcelamento de Débitos', 'Parcelamento IPVA e multas', 90.00, 1, 1);

-- Copiando estrutura para tabela lp_despachante_portal.solicitacao
CREATE TABLE IF NOT EXISTS `solicitacao` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `usuario_id` int(11) NOT NULL,
  `veiculo_id` int(11) NOT NULL,
  `servico_id` int(11) NOT NULL,
  `status` enum('recebido','aguardando_pagamento','aguardando_documento','em_andamento','concluido','cancelado') DEFAULT 'recebido',
  `observacao_cliente` text DEFAULT NULL,
  `observacao_admin` text DEFAULT NULL,
  `data_solicitacao` datetime DEFAULT current_timestamp(),
  `data_conclusao` datetime DEFAULT NULL,
  PRIMARY KEY (`id`),
  KEY `fk_solicitacao_usuario` (`usuario_id`),
  KEY `fk_solicitacao_veiculo` (`veiculo_id`),
  KEY `fk_solicitacao_servico` (`servico_id`),
  CONSTRAINT `fk_solicitacao_servico` FOREIGN KEY (`servico_id`) REFERENCES `servico` (`id`),
  CONSTRAINT `fk_solicitacao_usuario` FOREIGN KEY (`usuario_id`) REFERENCES `usuario` (`id`) ON DELETE CASCADE,
  CONSTRAINT `fk_solicitacao_veiculo` FOREIGN KEY (`veiculo_id`) REFERENCES `veiculo` (`id`) ON DELETE CASCADE
) ENGINE=InnoDB AUTO_INCREMENT=11 DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

-- Copiando dados para a tabela lp_despachante_portal.solicitacao: ~10 rows (aproximadamente)
INSERT INTO `solicitacao` (`id`, `usuario_id`, `veiculo_id`, `servico_id`, `status`, `observacao_cliente`, `observacao_admin`, `data_solicitacao`, `data_conclusao`) VALUES
	(1, 2, 1, 1, 'em_andamento', 'Preciso com urgência.', NULL, '2026-03-03 15:18:52', NULL),
	(2, 3, 2, 2, 'recebido', 'Documentos enviados.', NULL, '2026-03-03 15:18:52', NULL),
	(3, 4, 3, 3, 'aguardando_documento', 'Falta comprovante.', NULL, '2026-03-03 15:18:52', NULL),
	(4, 5, 4, 4, 'concluido', 'Tudo certo.', NULL, '2026-03-03 15:18:52', NULL),
	(5, 6, 5, 5, 'em_andamento', 'Aguardando banco.', NULL, '2026-03-03 15:18:52', NULL),
	(6, 7, 6, 6, 'recebido', 'Multa indevida.', NULL, '2026-03-03 15:18:52', NULL),
	(7, 8, 7, 7, 'aguardando_pagamento', 'Enviarei PIX.', NULL, '2026-03-03 15:18:52', NULL),
	(8, 9, 8, 8, 'recebido', 'Categoria D.', NULL, '2026-03-03 15:18:52', NULL),
	(9, 2, 9, 9, 'concluido', 'Já vendido.', NULL, '2026-03-03 15:18:52', NULL),
	(10, 3, 10, 10, 'em_andamento', 'Parcelamento em 12x.', NULL, '2026-03-03 15:18:52', NULL);

-- Copiando estrutura para tabela lp_despachante_portal.usuario
CREATE TABLE IF NOT EXISTS `usuario` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `nome` varchar(100) NOT NULL,
  `email` varchar(100) NOT NULL,
  `senha` varchar(255) NOT NULL,
  `nivel` enum('cliente','administrador') DEFAULT 'cliente',
  `cpf_cnpj` varchar(20) DEFAULT NULL,
  `celular` varchar(20) DEFAULT NULL,
  `data_cadastro` datetime DEFAULT current_timestamp(),
  PRIMARY KEY (`id`),
  UNIQUE KEY `email` (`email`)
) ENGINE=InnoDB AUTO_INCREMENT=11 DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

-- Copiando dados para a tabela lp_despachante_portal.usuario: ~10 rows (aproximadamente)
INSERT INTO `usuario` (`id`, `nome`, `email`, `senha`, `nivel`, `cpf_cnpj`, `celular`, `data_cadastro`) VALUES
	(1, 'Ana Martins', 'ana@portal.com', '123', 'administrador', '111.111.111-11', '11999990001', '2026-03-03 15:18:13'),
	(2, 'Bruno Costa', 'bruno@portal.com', '123', 'cliente', '222.222.222-22', '11999990002', '2026-03-03 15:18:13'),
	(3, 'Carla Souza', 'carla@portal.com', '123', 'cliente', '333.333.333-33', '11999990003', '2026-03-03 15:18:13'),
	(4, 'Daniel Lima', 'daniel@portal.com', '123', 'cliente', '444.444.444-44', '11999990004', '2026-03-03 15:18:13'),
	(5, 'Eduardo Rocha', 'eduardo@portal.com', '123', 'cliente', '555.555.555-55', '11999990005', '2026-03-03 15:18:13'),
	(6, 'Fernanda Alves', 'fernanda@portal.com', '123', 'cliente', '666.666.666-66', '11999990006', '2026-03-03 15:18:13'),
	(7, 'Gabriel Pinto', 'gabriel@portal.com', '123', 'cliente', '777.777.777-77', '11999990007', '2026-03-03 15:18:13'),
	(8, 'Helena Dias', 'helena@portal.com', '123', 'cliente', '888.888.888-88', '11999990008', '2026-03-03 15:18:13'),
	(9, 'Igor Mendes', 'igor@portal.com', '123', 'cliente', '999.999.999-99', '11999990009', '2026-03-03 15:18:13'),
	(10, 'Juliana Melo', 'juliana@portal.com', '123', 'administrador', '000.000.000-00', '11999990010', '2026-03-03 15:18:13');

-- Copiando estrutura para tabela lp_despachante_portal.veiculo
CREATE TABLE IF NOT EXISTS `veiculo` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `usuario_id` int(11) NOT NULL,
  `placa` varchar(10) NOT NULL,
  `renavam` varchar(20) DEFAULT NULL,
  `marca` varchar(50) DEFAULT NULL,
  `modelo` varchar(50) DEFAULT NULL,
  `ano_fabricacao` int(11) DEFAULT NULL,
  `ano_modelo` int(11) DEFAULT NULL,
  PRIMARY KEY (`id`),
  KEY `fk_veiculo_usuario` (`usuario_id`),
  CONSTRAINT `fk_veiculo_usuario` FOREIGN KEY (`usuario_id`) REFERENCES `usuario` (`id`) ON DELETE CASCADE
) ENGINE=InnoDB AUTO_INCREMENT=11 DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

-- Copiando dados para a tabela lp_despachante_portal.veiculo: ~10 rows (aproximadamente)
INSERT INTO `veiculo` (`id`, `usuario_id`, `placa`, `renavam`, `marca`, `modelo`, `ano_fabricacao`, `ano_modelo`) VALUES
	(1, 2, 'ABC1A23', '12345678901', 'Honda', 'Civic', 2020, 2020),
	(2, 3, 'DEF2B34', '23456789012', 'Toyota', 'Corolla', 2019, 2020),
	(3, 4, 'GHI3C45', '34567890123', 'Chevrolet', 'Onix', 2022, 2023),
	(4, 5, 'JKL4D56', '45678901234', 'Hyundai', 'HB20', 2021, 2022),
	(5, 6, 'MNO5E67', '56789012345', 'Ford', 'Ka', 2018, 2019),
	(6, 7, 'PQR6F78', '67890123456', 'Volkswagen', 'Gol', 2017, 2018),
	(7, 8, 'STU7G89', '78901234567', 'Fiat', 'Argo', 2023, 2023),
	(8, 9, 'VWX8H90', '89012345678', 'Nissan', 'Kicks', 2020, 2021),
	(9, 2, 'YZA9I12', '90123456789', 'Jeep', 'Renegade', 2021, 2022),
	(10, 3, 'BCD0J34', '01234567890', 'Renault', 'Sandero', 2016, 2017);

/*!40103 SET TIME_ZONE=IFNULL(@OLD_TIME_ZONE, 'system') */;
/*!40101 SET SQL_MODE=IFNULL(@OLD_SQL_MODE, '') */;
/*!40014 SET FOREIGN_KEY_CHECKS=IFNULL(@OLD_FOREIGN_KEY_CHECKS, 1) */;
/*!40101 SET CHARACTER_SET_CLIENT=@OLD_CHARACTER_SET_CLIENT */;
/*!40111 SET SQL_NOTES=IFNULL(@OLD_SQL_NOTES, 1) */;

```

</details>

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
