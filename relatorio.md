# RELATORIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 27/08/2025
Empresa: Abstergo Industries
Responsável: Julia Felizardo Bittencurt

## INTRODUÇÃO
ESte relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Julia Felizardo Bittencourt. O objetivo do projeto foi elencar 3 serviços AWS, com finalidade de realizar diminuição de custos imediatos.

## DESCRIÇÃO DO PROJETO
O projeto de implementação de ferramentas foi dividido em 3 etapas cada uma com seus objetivos específicos. A seguir, serão descritas as etapas dos projeto:

Etapa 1:
- AWS Cost Explorer
- Analisa detalhadamente os gastos e padrões de uso dos serviços AWS.
- A distribuidora farmacêutica utilizará o Cost Explorer via painel de monitoramento na AWS para gerar relatórios de custos por serviço. Isso permitirá identificar instâncias EC2 ociosas ou serviços S3 com alto custo, possibilitando desligamento ou redimensionamento de recursos.

Etapa 2:
- AWS Trusted Advisor
- Fornecer recomendações automáticas para otimização de custos, desempenho, segurança e confiabilidade dos recursos AWS.  
- A empresa acessará o Trusted Advisor pelo console da AWS para receber recomendações sobre instâncias ociosas, volumes de armazenamento não utilizados e recursos superdimensionados. As ações recomendadas serão aplicadas diretamente nas máquinas virtuais (EC2), volumes de armazenamento (EBS) e outros recursos em uso.

Etapa 3:
- Etapa 2:
- Definir limites de gastos e receber alertas quando os custos se aproximam do orçamento
- A distribuidora farmacêutica criará um orçamento mensal via AWS Budgets. Alertas serão configurados por e-mail ou SMS quando os gastos atingirem 80% e 100% do limite, permitindo que ajustes sejam feitos em tempo real nos recursos utilizados, como reduzir instâncias EC2 ou ajustar planos de armazenamento S3.

## Conclusão
A implementação de ferramentas na sempresa Abstergo Industries tem como esperado a utilização de AWS de forma eficiente e econômica, evitando desperdícios e aumentando o retorno sobre o investimento.

## Anexos
- https://docs.aws.amazon.com/cost-explorer/latest/userguide/what-is-cost-explorer.html 
- https://docs.aws.amazon.com/awssupport/latest/user/trusted-advisor.html
- https://docs.aws.amazon.com/cost-management/latest/userguide/budgets-managing-costs.html

Assinatura do Responsável pelo Projeto:
Julia Felizardo Bittencourt

