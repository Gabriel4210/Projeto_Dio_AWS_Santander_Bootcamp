# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 07/01/2026 
Empresa: Abstergo Industries 
Responsável: Gabriel Penha

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Gabriel. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1:

- **Nome da ferramenta**: Amazon S3 Intelligent-Tiering
- **Foco da ferramenta**: Otimização automática de custos de armazenamento.
- **Descrição de caso de uso**: A farmácia armazena milhares de imagens de produtos e documentos fiscais antigos. Com o S3 Intelligent-Tiering, esses arquivos são movidos automaticamente para camadas de armazenamento mais baratas quando não são acessados por 30 dias ou mais, sem que a equipe de TI precise fazer isso manualmente. Isso reduz drasticamente a fatura de storage sem risco de perda de dados.

Etapa 2:

- **Nome da ferramenta**: AWS Lambda
- **Foco da ferramenta**: Computação Serverless.
- **Descrição de caso de uso**: Atualmente, a farmácia mantém um servidor ligado 24h apenas para enviar e-mails de confirmação de compra. Substituiremos isso pelo AWS Lambda. Assim, a empresa não pagará por um servidor ligado o tempo todo, mas pagará apenas pelos milissegundos que o código levar para enviar o e-mail quando uma venda ocorrer. Se não houver vendas de madrugada, o custo é zero.

Etapa 3:

- **Nome da ferramenta**: AWS Cost Explorer
- **Foco da ferramenta**: Visibilidade e análise de custos.
- **Descrição de caso de uso**: Implementação de painéis para visualizar exatamente quais setores da farmácia estão gastando mais na nuvem. A ferramenta permitirá identificar recursos ociosos (como discos rígidos virtuais esquecidos ou IPs não utilizados) e recomendará onde cortar gastos, permitindo uma gestão proativa do orçamento mensal.

## Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado a redução dos custos operacionais através da automação de storage, a eliminação de servidores ociosos e a visibilidade total dos gastos, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos
 - Documentação oficial do Amazon S3 Intelligent-Tiering. [https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/using-intelligent-tiering.html]
 - Planilha custos: EC2 (Servidor Tradicional) vs. Lambda (Serverless). [https://aws.amazon.com/pt/lambda/pricing/]

Assinatura do Responsável pelo Projeto:
Gabriel F. R. Penha
