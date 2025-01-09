# Pesquisa Cognitiva com IA do Azure

Este projeto demonstra como configurar e usar **Pesquisa Cognitiva** com a IA do **Azure** para analisar e extrair informações de documentos.

## Passo a Passo de Configuração

1. **Criar um recurso de Pesquisa Cognitiva no Azure**:
    - Acesse o portal do Azure e crie um novo recurso de Pesquisa Cognitiva.
    - Escolha uma região e um nome para o serviço.
    - Anote a chave de API e o nome do serviço para uso posterior.

2. **Configurar a pesquisa cognitiva**:
    - No portal do Azure, configure uma **indexação de documentos**. Isso pode incluir documentos em texto simples, PDFs e outros formatos.
    - Configure a **pipeline cognitiva** para realizar processamento de linguagem natural, extração de entidades e outras análises.

3. **Usar a API para enviar documentos**:
    - Utilize a chave de API gerada no passo 1 para configurar a autenticação em seu aplicativo.
    - Envie seus documentos para a pesquisa cognitiva utilizando a API REST do Azure.

4. **Analisar os resultados**:
    - A partir do retorno da API, você poderá analisar as informações extraídas, como palavras-chave, entidades e conceitos relevantes.

## Insights

- **Aplicações da Pesquisa Cognitiva**:
    - A pesquisa cognitiva pode ser usada em várias indústrias, como saúde, jurídico e financeiro, para automatizar a extração de informações relevantes de grandes volumes de documentos não estruturados.
    - Ferramentas como o **Microsoft Power BI** e o **Azure AI** podem ser integradas para fornecer uma análise ainda mais poderosa dos dados extraídos.

- **Possíveis Ferramentas que se Beneficiam da Pesquisa Cognitiva**:
    - **Sistemas de gerenciamento de conteúdo (CMS)** para categorizar e indexar automaticamente documentos.
    - **Ferramentas de automação de processos** para extrair dados de documentos e automatizar fluxos de trabalho.
    - **Plataformas de BI (Business Intelligence)** para analisar dados extraídos e gerar relatórios dinâmicos.

## Aprendizados

- A pesquisa cognitiva vai além das simples buscas por palavras-chave. Ela usa **inteligência artificial**, como o **Processamento de Linguagem Natural (NLP)**, para entender o **contexto** e a **intenção** por trás dos documentos.
- A configuração de pipelines no Azure permite uma análise inteligente de documentos, considerando diversos fatores como semântica, relações entre entidades e até mesmo sentimentos.
  
## Como rodar o código

1. Clone este repositório para sua máquina local.
2. Certifique-se de ter uma chave de API válida para o Azure e configure-a no arquivo `config/configuracoes_azure.txt`.
3. Execute o código para enviar seus documentos para o serviço de Pesquisa Cognitiva do Azure.

## Exemplo de Documento

O documento de exemplo (`inputs/exemplo_documento.txt`) contém um conjunto de frases que você pode utilizar para testar a pesquisa cognitiva.

---

Espero que este projeto ajude a entender melhor como funciona a **pesquisa cognitiva** e suas aplicações em ambientes de produção.
