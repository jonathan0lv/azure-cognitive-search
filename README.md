# Azure Cognitive Search - LAB Prático 🚀

Este repositório contém um projeto prático de **Azure Cognitive Search**, abordando técnicas de organização de documentos, criação de índices e exploração de funcionalidades.

---

## 📊 Conteúdos Aprendidos

### ✨ Mineração de Conhecimento
- Compreensão sobre como extrair informações valiosas de grandes volumes de dados.
- Aplicabilidade da mineração para otimizar pesquisas e classificação de documentos.

### ✨ Solução de Pesquisa Cognitiva do Azure
- Exploração dos recursos do **Azure Cognitive Search**.
- Criação de serviços de busca otimizados para diferentes tipos de documentos.

### ✨ Enriquecimento de IA
- Uso de **IA** para melhorar a pesquisa e análise dos dados indexados.
- Implementação de habilidades cognitivas como **extração de texto, reconhecimento de entidade e tradutor**.

### ✨ Conhecendo o Desafio do Laboratório
- Introdução ao desafio prático e aos objetivos do projeto.
- Definição dos principais componentes necessários para a solução.

### ✨ Buscas Cognitivas
- Aprendizado sobre como melhorar os resultados de pesquisa através de busca cognitiva.
- Implementação de **filtros e relevância** para otimizar resultados.

---

## 📌 Passo a Passo para Configuração

### 1️⃣ **Criação do Serviço no Azure**
- Acesse o [Portal do Azure](https://portal.azure.com/).
- Procure por **Azure Cognitive Search**.
- Clique em **Criar um Serviço de Pesquisa**.
- Configure os detalhes do serviço (Nome, Região, Camada de Preço).
- Aguarde a implantação do serviço.

### 2️⃣ **Ingestão de Dados**
- Utilize um dataset de exemplo (JSON, CSV, ou banco de dados).
- Configure a **origem de dados** no portal do Azure.
- Crie um **indexador** para processar e estruturar os dados.

### 3️⃣ **Criação e Exploração do Índice**
- Acesse a seção **Índices** e visualize os campos criados.
- Utilize o **Search Explorer** para testar consultas.
- Experimente filtros, facetas e ordenação.

### 4️⃣ **Integração com Aplicações**
- Conecte a API de Pesquisa do Azure a um projeto Python ou .NET.
- Execute consultas usando `requests` no Python:
  ```python
  import requests

  url = "https://<seu-servico>.search.windows.net/indexes/<seu-indice>/docs?api-version=2021-04-30&search=*"
  headers = {"api-key": "<sua-chave>", "Content-Type": "application/json"}

  response = requests.get(url, headers=headers)
  print(response.json())
  ```

---

## 📊 **Insights e Aprendizados**
- **Facilidade na indexação**: O Azure Cognitive Search simplifica a organização e recuperação de informações.
- **Flexibilidade na busca**: Suporte a filtros avançados, pesquisa textual e facetas.
- **Escalabilidade**: Suporta grandes volumes de dados com alto desempenho.

---

## 📚 **Referências**
- [Documentação Oficial do Azure Cognitive Search](https://learn.microsoft.com/pt-br/azure/search/)
- [Guia Mineração de Conhecimento no Azure](https://www.dio.me/articles/a-inteligencia-artificial-e-a-mineracao-de-conhecimento-no-azure)

