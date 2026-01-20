# Dashboard de Gestão de Assinaturas (Xbox & Season Passes)

Este projeto consiste em um dashboard interativo desenvolvido em **Microsoft Excel** para análise de métricas de faturamento e comportamento de assinantes de serviços de jogos. O foco principal é monitorar o desempenho de planos base e a venda de produtos adicionais (*upsell*).

## Estrutura do Arquivo
O arquivo está organizado em quatro abas principais para garantir a integridade dos dados e facilitar a manutenção:

* **`Assets`**: Centraliza a identidade visual do projeto, contendo a paleta de cores e imagens utilizadas na interface.
* **`Bases`**: Contém a tabela com a base de dados "crua" (dados brutos de assinantes).
* **`Cálculos`**: Área técnica onde residem as **Tabelas Dinâmicas** criadas para extrair os valores dos cards e dos gráficos.
* **`Dashboard`**: Interface final interativa contendo os cards de indicadores e as visualizações gráficas.

## O Dashboard
A interface foi projetada para uma leitura rápida e eficiente, contendo os seguintes elementos:

* **Cards Superiores**: Exibem o faturamento total das assinaturas de *EA Play Season Pass* e *Minecraft Season Pass*.
* **Gráficos**: Visualizações que detalham o faturamento do *Xbox Game Pass* e a distribuição por renovação automática.
* **Filtros Interativos**: Um segmentador lateral (Slicer) para filtrar os dados por **Subscription Type** (Anual, Mensal, Trimestral).

## Perguntas de Negócio Respondidas
O projeto utiliza análises específicas para responder questões estratégicas:
1. Qual o faturamento total de vendas de planos anuais (com assinaturas agregadas)?
2. Qual o faturamento total de planos anuais, separado por renovação automática (Sim/Não)?
3. Qual o total de vendas de assinaturas do *EA Play*?
4. Qual o total de vendas de assinaturas do *Minecraft Season Pass*?

## Instruções para Reprodução

1. **Dados Brutos**: Insira ou atualize as informações na aba `Bases`.
2. **Processamento**: Vá até a aba `Cálculos` e atualize as Tabelas Dinâmicas para garantir que os novos dados sejam processados.
3. **Visualização**: Os resultados serão refletidos automaticamente nos gráficos e cards da aba `Dashboard`.
4. **Interação**: Utilize o segmentador de dados à esquerda para realizar filtros dinâmicos na visão geral.

---

### Tecnologias Utilizadas
* **Microsoft Excel**: Tabelas Dinâmicas, Segmentadores de Dados e Gráficos de Barras.
* **Design**: Interface limpa com foco em UX para análise de dados.

    Microsoft Excel: Tabelas Dinâmicas, Segmentadores de Dados e Gráficos.

    Design: Flat UI (Inspirado em dashboards modernos de análise de dados).
