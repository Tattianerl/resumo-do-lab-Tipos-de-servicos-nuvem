# resumo-do-lab-Tipos-de-servicos-nuvem.

# Tipos de Serviços na Nuvem

Neste laboratório, exploramos os principais tipos de serviços oferecidos na computação em nuvem, com foco nos modelos de serviço IaaS, PaaS e SaaS.

- IaaS (Infraestrutura como Serviço):   
é o modelo em que a infraestrutura virtual é fornecida, permitindo o provisionamento de recursos de computação como armazenamento, redes e máquinas virtuais. Usuários têm controle sobre o sistema operacional e aplicações, tornando-o ideal para ambientes que precisam de flexibilidade e controle avançado.

- PaaS (Plataforma como Serviço): 
oferece uma plataforma para desenvolvimento e implementação de aplicações sem a necessidade de gerenciar a infraestrutura subjacente. PaaS facilita a criação de aplicativos de forma mais rápida, permitindo que desenvolvedores se concentrem apenas no código e na funcionalidade.

- SaaS (Software como Serviço): 
fornece software pronto para uso, acessível pela internet. O modelo SaaS é amplamente utilizado por organizações para aplicativos comuns, como e-mails e CRM, dispensando a necessidade de instalação local ou gerenciamento direto de servidores.

Com esses modelos, é possível escolher a abordagem que melhor se adapta às necessidades específicas, seja no controle da infraestrutura, na velocidade de desenvolvimento ou na praticidade de uso de softwares prontos.

# Introdução para a criação de instâcia de banco de dados.
## Passos Para configurar uma instância de banco de dados no Azure:
### 1. **Acesse o Portal Azure**
- Entre no Portal do Azure usando sua conta.
- No menu de navegação, escolha Criar um recurso.
  
### 2. **Selecione o Tipo de Banco de Dados**
- Pesquise por "Banco de Dados" e escolha o tipo desejado, como:
- Azure SQL Database para SQL Server.
- Azure Database for MySQL para MySQL.
- Azure Database for PostgreSQL para PostgreSQL.
  
### 3. **Configure as Opções de Banco de Dados**
- Clique em Criar para iniciar a configuração da instância.
- Selecione as seguintes opções principais:
- Nome do Banco de Dados: Nome de identificação da sua instância.
 - Assinatura: Escolha a assinatura correta (se você tiver várias).
 - Grupo de Recursos: Escolha um existente ou crie um novo para organizar seu banco.
 - Localização: Selecione a região que melhor atende ao seu caso de uso e latência.
   
### 4. **Configurar a Performance e o Tipo de Preço**
- Defina o plano de serviço conforme sua necessidade:
- Computação Serveless ou Dedicada para SQL Server.
- Camada de Preço: Dependendo do volume esperado, como Básico, Geral ou Otimizado para Memória.
- Escolha o número de vCores e quantidade de armazenamento conforme o desempenho desejado.
  
### 5. **Configurar as Definições de Segurança**
- Autenticação: Configure o tipo de autenticação (SQL, Azure AD, ou ambas).
- Firewall e Redes Virtuais:
- Defina as regras de firewall para permitir acesso ao seu IP ou a redes específicas.
- Opcionalmente, ative Private Link para acesso privado.

### 6. **Revise e Crie a Instância**
- Clique em Revisar + Criar para verificar todas as configurações.
- Após a verificação, clique em Criar para iniciar a implantação da instância.
