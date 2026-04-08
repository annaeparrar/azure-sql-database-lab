# ☁️ Desafio DIO - Configuração de Banco de Dados no Microsoft Azure

## 📌 Descrição do Projeto

Este repositório foi desenvolvido como parte do desafio da DIO, com o objetivo de praticar a criação e configuração de uma instância de banco de dados na plataforma Microsoft Azure.

O projeto documenta todo o processo, incluindo conceitos aprendidos, etapas realizadas e dicas práticas para futuras implementações.

---

## 🎯 Objetivos de Aprendizagem

* Aplicar conceitos de computação em nuvem na prática
* Criar e configurar uma instância de banco de dados no Azure
* Documentar processos técnicos de forma clara
* Utilizar o GitHub como ferramenta de compartilhamento

---

## ☁️ O que é o Microsoft Azure?

O Microsoft Azure é uma plataforma de computação em nuvem que oferece serviços como:

* Armazenamento
* Redes
* Máquinas Virtuais
* Bancos de Dados Gerenciados

---

## 🗄️ Banco de Dados no Azure

Neste laboratório, foi utilizada uma instância de:

**Azure SQL Database**

Principais características:

* Banco de dados como serviço (PaaS)
* Alta disponibilidade
* Escalabilidade automática
* Backup automático

---

## ⚙️ Passo a Passo da Configuração

### 1. Acesso ao Portal Azure

* Acessar: https://portal.azure.com
* Fazer login com conta Microsoft


---

### 2. Criar um Recurso

* Selecionar **SQL Database**
* Clicar em **Create**


---

### 3. Configuração do Banco

* Resource Group: criar novo ou usar existente
* Database Name: `dio-db-lab`
* Server: criar novo servidor
* Região: selecionar a mais próxima
* Autenticação: SQL Authentication


---

### 4. Configuração de Rede

* Permitir acesso ao IP local
* Habilitar acesso público (apenas para testes)

---

### 5. Revisão e Criação

* Validar configurações
* Clicar em **Create**

---

### 6. Conexão com o Banco

Ferramentas utilizadas:

* Azure Data Studio
* SQL Server Management Studio (SSMS)


---

## 🧪 Teste de Conexão


```sql
SELECT GETDATE();
```

---

## 📝 Aprendizados

Durante este desafio, aprendi:

* Como provisionar recursos no Azure
* Diferença entre IaaS, PaaS e SaaS
* Configuração de segurança básica (firewall)
* Conexão com banco de dados na nuvem

---

## 💡 Dicas Importantes

* Sempre configure regras de firewall corretamente
* Evite deixar acesso público aberto em produção
* Utilize nomes padronizados para recursos
* Monitore custos no Azure

---

## 📚 Referências

* Microsoft Learn
* Documentação oficial do Azure
* Conteúdo da DIO

---

## 🔗 Conclusão

Este laboratório foi essencial para consolidar conhecimentos em cloud computing e banco de dados, proporcionando uma experiência prática com o Microsoft Azure.

---

## 👩‍💻 Autor

Desenvolvido por Anna Rausseo

