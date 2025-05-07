# Tutorial: Instalação e Configuração da Estrutura para Agente de IA Local

## Introdução

Este tutorial vai guiar você através do processo de instalação e configuração da nossa estrutura para criação de um Agente de IA Local, incliuindo os componentes:

- **WAHA**: API de Whatsapp gratuita
- **n8n**: Plataforma de automação
- **Redis**: Banco de dados em memória para registro de chats
- **PostgreSQL** (Opcional): Banco de dados relacional para uso geral

## Pré-requisitos

- Ter o Docker Desktop instalado [Baixe aqui](https://www.docker.com/get-started/)
- Windows 10, 11 ou MacOs.

## Passo a Passo

### 1. Faça download deste repositório

![Preparação do Ambiente](./imagens/passo1.png)

*Descrição: Nesta etapa, você vai preparar seu ambiente para a instalação.*

### 2. Clone do Repositório

![Clone do Repositório](./imagens/passo2.png)

*Descrição: Como obter os arquivos necessários para a instalação.*

### 3. Configuração do Docker Compose

![Configuração do Docker Compose](./imagens/passo3.png)

*Descrição: Ajustes necessários no arquivo docker-compose.yml.*

### 4. Resolução de Problemas de Compatibilidade

![Resolução de Problemas](./imagens/passo4.png)

*Descrição: Como resolver o erro "no matching manifest for linux/arm64/v8" e outros problemas de compatibilidade de plataforma.*

### 5. Inicialização dos Serviços

![Inicialização dos Serviços](./imagens/passo5.png)

*Descrição: Como iniciar todos os serviços com Docker Compose.*

### 6. Configuração do WAHA

![Configuração do WAHA](./imagens/passo6.png)

*Descrição: Como configurar o WAHA para conectar ao WhatsApp.*

### 7. Configuração do n8n

![Configuração do n8n](./imagens/passo7.png)

*Descrição: Como acessar e configurar o n8n para criar seus fluxos de trabalho.*

### 8. Integração com o Banco de Dados

![Integração com o Banco de Dados](./imagens/passo8.png)

*Descrição: Como configurar a conexão com o PostgreSQL.*

### 9. Criação do Seu Primeiro Fluxo de Trabalho

![Primeiro Fluxo de Trabalho](./imagens/passo9.png)

*Descrição: Como criar um fluxo de trabalho básico no n8n que integra com o WhatsApp.*

### 10. Teste e Validação

![Teste e Validação](./imagens/passo10.png)

*Descrição: Como testar se tudo está funcionando corretamente.*

## Solução de Problemas Comuns

### Problema: Incompatibilidade de Plataforma

```
matching manifest for linux/arm64/v8 in the manifest list entries: no match for platform in manifest: not found
```

**Solução:**

*Descreva aqui a solução para o problema de compatibilidade de plataforma.*

### Problema: Falha na Conexão com o WhatsApp

**Solução:**

*Descreva aqui a solução para problemas de conexão com o WhatsApp.*

### Problema: Erros no n8n

**Solução:**

*Descreva aqui a solução para problemas comuns no n8n.*

## Conclusão

Parabéns! Você agora tem uma estrutura completa de Agente de IA Local funcionando. Esta configuração permite que você crie automações poderosas que podem interagir com usuários através do WhatsApp.

## Recursos Adicionais

- [Documentação do WAHA](https://github.com/waha-project/waha)
- [Documentação do n8n](https://docs.n8n.io/)
- [Documentação do PostgreSQL](https://www.postgresql.org/docs/)

---

*Última atualização: Maio 2025*
