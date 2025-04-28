# ☁️ Configuração de Instância de Banco de Dados no Azure

## 📘 Sobre o Desafio

Este repositório faz parte do laboratório prático da DIO com foco na **criação e configuração de uma instância de Banco de Dados** utilizando a plataforma **Microsoft Azure**. O objetivo é documentar os principais aprendizados, conceitos, dicas e boas práticas para utilizar bancos de dados na nuvem em projetos reais.

Este conteúdo também serve como material de apoio para estudos e futuras implementações.

---

## 🚀 Benefícios de Utilizar Banco de Dados no Azure

A Microsoft Azure oferece diversas vantagens para hospedar e gerenciar bancos de dados:

- 🔒 Alta segurança e proteção de dados.
- 🌍 Alta disponibilidade e recuperação de desastres.
- ⚡ Performance escalável conforme a necessidade do projeto.
- 🔄 Backups automáticos e gerenciamento simplificado.
- 🔧 Suporte para diversos motores de banco de dados (SQL Server, PostgreSQL, MySQL, Cosmos DB, entre outros).

---

## 🛠️ Etapas para Criação de uma Instância de Banco de Dados no Azure

1. **Acessar o Portal Azure**  
   - Link: [Portal Azure](https://portal.azure.com/)

2. **Criar um recurso de Banco de Dados**  
   - Ir em **"Criar um recurso" > "Bancos de dados"**.
   - Escolher o tipo de banco de dados desejado (ex: Azure SQL Database).

3. **Configurar os detalhes da instância**  
   - Informar:
     - Nome do banco de dados.
     - Nome do servidor ou criar um novo servidor.
     - Região (data center).
     - Tipo de preço (DTU-based ou vCore-based).
     - Configurar autenticação (usuário e senha).

4. **Configurar opções adicionais**  
   - Backup automático.
   - Redundância geográfica.
   - Monitoramento e alertas.

5. **Revisar e Criar**  
   - Validar todas as configurações.
   - Clicar em **"Criar"** e aguardar o provisionamento.

---

## 📈 Boas Práticas e Dicas

- 🔑 **Utilizar autenticação segura**: sempre usar senhas fortes e habilitar firewalls e autenticação multifator quando possível.
- 🧩 **Separar ambientes**: crie instâncias separadas para desenvolvimento, testes e produção.
- 💸 **Controlar custos**: monitore o uso de recursos e ajuste o plano de serviço conforme a demanda.
- 🛡️ **Backup e Recuperação**: verifique a política de backup configurada e entenda o processo de recuperação de dados.
- 📊 **Monitoramento**: utilize o Azure Monitor e configure alertas para quedas de performance ou indisponibilidades.
- 🌐 **Configurar o Firewall do Servidor**: permita apenas os IPs necessários para acessar o banco de dados.

---

## 🔐 Segurança em Bancos de Dados no Azure

- **TDE (Transparent Data Encryption):** Criptografa automaticamente os dados armazenados.
- **Auditoria de Banco de Dados:** Monitora e registra eventos no banco de dados.
- **Advanced Threat Protection:** Detecta atividades suspeitas e anomalias.

---

## ⏱️ SLA - Acordo de Nível de Serviço

- A Microsoft garante **SLA de até 99,99% de disponibilidade** para bancos de dados SQL na nuvem.
- O tempo de indisponibilidade esperado é **menor que 5 minutos por mês**.

---

## 📌 Conclusão

Com este laboratório, pratiquei a criação e configuração de uma instância de banco de dados no Azure, além de consolidar conhecimentos sobre **segurança, backup, escalabilidade e boas práticas na nuvem**. Este material servirá como guia para futuras implementações e para projetos profissionais em ambientes de produção.

---


## 🔗 Links Úteis

- [Portal Azure](https://portal.azure.com/)
- [Documentação oficial do Azure SQL Database](https://learn.microsoft.com/pt-br/azure/azure-sql/)
- [Calculadora de Preços do Azure](https://azure.microsoft.com/pt-br/pricing/calculator/)
- [Formação GitHub Certification na DIO](https://github.com/digitalinnovationone/formacao-github-certification)
- [Guia de Markdown no GitHub](https://docs.github.com/pt/get-started/writing-on-github)


