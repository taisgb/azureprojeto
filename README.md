# 📂 Criando Processos de Redundância de Arquivos na Azure

## 📌 Descrição do Projeto
Este projeto demonstra a criação de **processos de redundância e integração de arquivos** na plataforma **Azure**, utilizando recursos como **Azure Data Factory** e **Azure Data Lake Storage Gen2**.

Através da configuração de **runtimes de integração** e **serviços vinculados**, foi possível construir um ambiente seguro para armazenamento de dados com opções de redundância e alta disponibilidade.

---

## 🚀 Tecnologias e Serviços Utilizados
- Microsoft Azure
- Azure Data Factory
- Azure Data Lake Storage Gen2
- Azure Integration Runtime
- Git e GitHub para versionamento
- Azure Storage Explorer (opcional para testes locais)

---

## 🛠️ Etapas de Implementação

### 1. Configuração do Data Factory
Criação e configuração das **runtimes de integração** (AutoResolveIntegrationRuntime e IntegrationRuntime1).

![Configuração das Runtimes](![runtimes-integracao (1)](https://github.com/user-attachments/assets/6a96d051-38b4-424b-97b7-91239ef317b9)
)

---

### 2. Criação de Serviços Vinculados
Conexão de serviços como Azure Data Lake Storage, Azure SQL Database e GitHub.

![Serviços Vinculados](![servicos-vinculados](https://github.com/user-attachments/assets/f0a77726-386c-4c9c-bc7d-3ef59259c02e)
)

---

### 3. Configuração de Conexão Segura
Utilização de **Chave de Conta** para autenticação no Azure Data Lake Storage.  
Definição manual da URL de acesso e configuração da chave para segurança.

![Configuração do Azure Data Lake Storage](![configuracao-datalake](https://github.com/user-attachments/assets/036ca0e5-8267-4a8d-a7a0-87cce8938191)
)

---

### 4. Edição e Testes
Teste de conectividade para garantir que o serviço foi corretamente vinculado.

![Teste de Conexão](![teste-conexao](https://github.com/user-attachments/assets/903bced0-1561-4e10-95ef-84999568df47)
)

---

## 📈 Insights e Aprendizados

- O **Integration Runtime** é essencial para permitir a movimentação e transformação de dados entre diferentes ambientes de rede no Azure.
- A escolha entre diferentes tipos de **autenticação** impacta diretamente na segurança e agilidade do processo de integração.
- **Azure Data Lake Storage** é ideal para armazenar grandes volumes de dados de forma escalável e segura.
- Sempre testar as conexões antes de ativar pipelines para evitar erros de execução em ambientes produtivos.

---

## 🔮 Possibilidades Futuras

- Configurar **pipelines de movimentação de dados automáticos** entre diferentes storages.
- Implementar **redundância geográfica** para maior segurança contra falhas regionais.
- Automatizar integrações usando **Azure Data Factory Triggers**.

---

## 📎 Como acessar o projeto
```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
