# 🛒 **Projeto de E-commerce – SENAI Suíço Santo Amaro**  

## 🔥 **Visão Geral**  
Este projeto é a **implementação do backend** de um **e-commerce completo**, desenvolvido ao longo do semestre de **backend** no **SENAI Suíço Santo Amaro**. Utilizando **Java com Spring Boot** para a lógica de negócio e **MySQL** para o banco de dados, o sistema visa oferecer uma plataforma segura, eficiente e escalável para compras online.  

O projeto conta com um **frontend separado**, que será desenvolvido em paralelo. O prazo final para a entrega completa do sistema é **agosto**.  

## 🚀 **Objetivo do Projeto**  
Criar um **backend robusto** para um e-commerce funcional, permitindo que os usuários possam:  
✅ **Criar conta** e gerenciar seus perfis.  
✅ **Navegar** por produtos organizados em categorias.  
✅ **Adicionar itens ao carrinho** e finalizar compras.  
✅ **Realizar pagamentos** com integração de gateway.  
✅ **Acompanhar pedidos** e receber notificações.  
✅ **Administradores** gerenciarem estoque, produtos e usuários.  

## 🏗️ **Tecnologias Utilizadas**  
### 🖥️ **Backend**  
- **Java 17+** → Linguagem principal do projeto.  
- **Spring Boot** → Framework para criar a API de forma eficiente.  
- **Spring Security** → Autenticação e autorização dos usuários.  
- **Spring Data JPA** → Gerenciamento da persistência dos dados.  

### 🗄️ **Banco de Dados**  
- **MySQL** → Banco relacional para armazenar os dados.  
- **Flyway** → Versionamento e migração do banco de dados.  

### 📡 **APIs e Integrações**  
- **Stripe/PagSeguro** → Processamento de pagamentos.  
- **Twilio ou Firebase** → Notificações via e-mail/SMS.  
- **OpenAI API** → Implementação futura de recomendações inteligentes.  

## 🛠️ **Principais Funcionalidades do Backend**  
### 👤 **Usuário**  
✅ Cadastro/Login com autenticação JWT  
✅ Recuperação de senha via e-mail  
✅ Gestão de perfil e histórico de compras  

### 🛍️ **Catálogo de Produtos**  
✅ Listagem de produtos por categorias  
✅ Filtros avançados (preço, popularidade, avaliações)  
✅ Exibição detalhada do produto com imagens e descrições  

### 🛒 **Carrinho e Checkout**  
✅ Adicionar/remover produtos  
✅ Cálculo de frete e impostos  
✅ Finalização de compra com múltiplas formas de pagamento  

### 📦 **Gestão de Pedidos**  
✅ Acompanhamento do status do pedido (Processando → Enviado → Entregue)  
✅ Sistema de notificações (e-mail, SMS)  
✅ Suporte a devoluções e trocas  

### 📊 **Painel para Administradores**  
✅ Gestão de produtos e categorias  
✅ Controle de estoque e relatórios de vendas  
✅ Gestão de usuários e permissões  

## 🔥 **Diferenciais do Backend**  
- **🔐 Segurança** → Uso de **JWT** para autenticação, criptografia de senhas e proteção contra ataques como SQL Injection e CSRF.  
- **⚡ Performance** → Implementação de **cache** com Redis para reduzir carga no banco de dados.  
- **📈 Escalabilidade** → Arquitetura baseada em **microservices** para futuras expansões.  
- **🤖 Inteligência Artificial** (futuro) → Recomendações personalizadas para clientes com base no histórico de compras.  

## 📅 **Cronograma de Desenvolvimento**  
✅ **Sprint 1** → Configuração do ambiente e banco de dados.  
✅ **Sprint 2** → Implementação do sistema de usuários e autenticação.  
🛠️ **Sprint 3** → Desenvolvimento do catálogo de produtos e carrinho.  
🚀 **Sprint 4** → Checkout, pagamentos e sistema de pedidos.  
🔍 **Sprint 5** → Testes, otimizações e deploy final.  

## 🌐 **Deploy e Infraestrutura**  
- **Backend**: **Hospedado na Azure/Vercel**  
- **Banco de Dados**: **MySQL gerenciado na nuvem**  
- **CI/CD**: **GitHub Actions para automação de builds e testes**  

## 📌 **Prazos e Entrega Final**  
📅 **Prazo final para conclusão do projeto: Agosto de 2025**  
O backend será totalmente desenvolvido e integrado ao frontend dentro desse período, garantindo que a plataforma esteja funcional e otimizada até a data de entrega.  

## 💡 **Conclusão**  
Este projeto não é apenas um trabalho acadêmico, mas uma experiência **realista** de desenvolvimento de um **e-commerce do zero**, seguindo boas práticas e padrões modernos de desenvolvimento. Com uma arquitetura sólida e tecnologias de ponta, este sistema poderá ser expandido e utilizado como um modelo para futuros projetos profissionais.  
