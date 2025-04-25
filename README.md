# DIO-DESAFIO-AZURE-DATABRICKS-01
Desafio é "Criando um Monitoramento de Custos no Data Factory"

## Criando uma Instância do Data Fabric no Azure
 
 Este guia mostra como criar uma instância do Microsoft Fabric e criar um monitoramento de custos da instância.
 
 ---
 
 ## Limitações
 
 - Não foi aberto a conta na Microsoft Azure gratuita porque o usuário usou em datas anteriores para a obtenção da certificação AI-900.Criar um Workspace no Microsoft Fabric
Acesse o portal do Azure.
---
 
 ## Criar um Workspace no Microsoft Fabric
 
 1. Acesse o [portal do Azure](https://portal.azure.com).
 2. No menu lateral, clique em Criar um recurso.
 3. Pesquise por Microsoft Fabric e selecione a opção correta.
 4. Clique em Criar e preencha os detalhes necessários:

  - Nome do workspace.
  - Assinatura e grupo de recursos.
  - Região.
 5. Clique em Revisar + Criar, depois em Criar.

![Criar recurso no Azure](https://learn.microsoft.com/en-us/azure/includes/media/cloud-shell-try-it/create-a-resource.png)
## Criar Monitoramento de Custos no Azure Data Factory

## Acessar o Cost Management

 1. Vá até o Azure Portal
 2. No menu esquerdo, clique em "Gerenciamento de custos + cobrança"
 3. Selecione a assinatura que contém sua Data Factory
## Criar Gráfico de Custos por Recurso

 1. Dentro de Gerenciamento de custos, clique em Análise de custo
 2. Filtros importantes:
- **Escopo:** Selecione a assinatura ou grupo de recursos que contém sua Data Factory
- **Agrupar por:** Recurso ou Nome do recurso
- **Período:** Últimos 7 dias, mês atual, ou personalizado
 3. Localize seu recurso de Data Factory na lista

## Criar um Dashboard de Custos
 1. No topo do portal, clique em Dashboard
 2. Clique em + Novo dashboard
 3. Adicione um tile do tipo Gráfico de custos
 4. Configure:
 - Escopo: Data Factory ou grupo de recursos
 - Agrupamento: Por recurso ou tag
 - Período: Mês atual ou personalizado
 5. Clique em Fixar no dashboard
