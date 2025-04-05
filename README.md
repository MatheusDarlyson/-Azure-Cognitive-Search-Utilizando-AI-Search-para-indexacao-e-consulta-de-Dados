# -Azure-Cognitive-Search-Utilizando-AI-Search-para-indexacao-e-consulta-de-Dados
Desafio para o Bootcamp Dio/Avanade

# Configurando uma Solução de Pesquisa com Azure AI Search

## 🧠 Objetivo

Este projeto tem como objetivo demonstrar a configuração de uma solução de pesquisa inteligente utilizando o Azure AI Search. A solução permitirá indexar e consultar dados de forma eficiente, enriquecendo-os com habilidades de IA para extrair insights valiosos.

---

## ⚙️ Passo a Passo de Configuração

1. **Criação dos Recursos no Azure**:

   - **Azure AI Search**:Serviço que gerencia a indexação e consulta de dados
   - **Azure AI Services**:Fornece habilidades de IA para enriquecer os dados durante o processo de indexação
   - **Conta de Armazenamento (Storage Account)**:Utilizada para armazenar os documentos que serão indexados

   *Observação*:Todos os recursos devem ser criados na mesma região para garantir compatibilidade

2. **Upload de Documentos no Azure Storage**:

   -Criar um container chamado `coffee-reviews` na conta de armazenamento
   -Fazer o upload dos arquivos de revisão de clientes para este container

3. **Criação e Configuração do Índice no Azure AI Search**:

   -Definir um índice chamado `coffee-index` com os campos apropriados para armazenar os dados das revisões
   -Configurar um indexador que conecte o container `coffee-reviews` ao `coffee-index`, utilizando habilidades de IA para enriquecer os dados durante a indexação

4. **Consulta ao Índice**:

   -Utilizar o portal do Azure para realizar consultas ao `coffee-index` e validar os dados indexados

---

## 💡 Insights Obtidos

- **Integração de Serviços** A combinação do Azure AI Search com o Azure AI Services permite a criação de soluções de pesquisa robustas e inteligente.
- **Enriquecimento de Dados** O uso de habilidades de IA durante a indexação adiciona valor aos dados, extraindo informações que não seriam facilmente acessíveis de outra form.

---

## 🛠️ Ferramentas e Tecnologias Utilizadas

- **Azure AI Search**
- **Azure AI Services**
- **Azure Storage Account**
- **Portal do Azure**

---

## 📚 Aprendizados
- Configuração e integração de múltiplos serviços do Azure para construir uma solução de pesqusa.
- Importância do enriquecimento de dados para melhorar a relevância e precisão dos resultados de pesqusa.

---

> Projeto baseado na documentação: [Explore an Azure AI Search index (UI)](http://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html)

