# Azure Cognitive Search: Utilizando AI Search para Indexação e Consulta de Dados

Este repositório documenta a implementação prática do serviço **Azure Cognitive Search**, utilizando os recursos de **AI Search** para realizar indexação, enriquecimento e consulta inteligente de dados.

---

## 🎯 Descrição do Projeto

O projeto foi desenvolvido com o objetivo de explorar como o **Azure Cognitive Search** permite criar mecanismos de busca inteligentes, capazes de indexar grandes volumes de dados estruturados ou não estruturados, além de aplicar recursos de IA para extração de informações relevantes durante o processo de indexação.

---

## 🛠️ Tecnologias e Ferramentas Utilizadas

- ☁️ **Azure Cognitive Search**
- 🔍 **AI Enrichment (Cognitive Skills)**
- 🐍 **Python + SDK do Azure Search** (para automação)
- 📄 Dados em formatos JSON, CSV e PDF
- 🌐 Portal do Azure
- 📸 Capturas de tela do processo

---

## 🚀 Processo Realizado

1. Foi criado um recurso de **Azure Cognitive Search** no portal do Azure, configurando endpoint, API Key e um serviço de preço básico.

2. Um **índice de busca** foi projetado com campos personalizados, como:
   - `id` (chave primária)
   - `titulo`
   - `conteudo`
   - `categoria`
   - `data_criacao`

3. Utilizando o recurso de **Indexador**, foram conectadas fontes de dados, incluindo:
   - Arquivos JSON armazenados no **Azure Blob Storage**.
   - Documentos PDF e CSV para testes de enriquecimento.

4. Foi aplicado o pipeline de **AI Enrichment**, utilizando **Cognitive Skills** como:
   - Detecção de linguagem.
   - Extração de entidades.
   - Análise de sentimentos.
   - OCR para reconhecimento de texto em PDFs.

5. Após a indexação, foram realizados testes de consultas, utilizando filtros, full-text search e ordenações, tanto pela interface do Azure quanto por meio de scripts em Python.

---
## 🧠 Resultados Obtidos

- O serviço foi capaz de indexar rapidamente documentos **estruturados e não estruturados**.
- As **Cognitive Skills** adicionaram enriquecimento aos dados, como:
  - Detecção de entidades.
  - Análise de sentimentos.
  - Extração de texto em PDFs via OCR.
- As consultas realizadas retornaram **resultados altamente relevantes**, utilizando:
  - Filtros por categorias.
  - Full-text search.
  - Recursos de **pesquisa semântica**.

---

## 💡 Aprendizados

- Configuração de **índices** no Azure Cognitive Search.
- Implementação de **pipelines de AI Enrichment** para enriquecimento de dados.
- Utilização das linguagens de consulta no Azure Search:
  - **OData**
  - **Lucene**
- Integração programática com o Azure Search utilizando **Python** e **API REST**.
- Interpretação dos resultados e **otimização de buscas inteligentes**.

---
