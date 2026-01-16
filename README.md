# Redução dos Custos em Farmácias com AWS
# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 15/01/2026

Empresa: Abstergo Industries

Responsável: Thiago Santos Pires

## Introdução
Este relatório apresenta o processo de implementação de serviços em nuvem na empresa Abstergo Industries, realizado por Thiago Santos Pires. A empresa atua como um hub de distribuição farmacêutica, realizando a revenda e distribuição de produtos de diferentes fabricantes e farmácias parceiras.

O objetivo do projeto é propor a adoção de três serviços da Amazon Web Services (AWS) com foco na redução imediata de custos operacionais, aumento de eficiência, escalabilidade e confiabilidade da infraestrutura de TI, considerando que a empresa não possuía nenhuma solução em nuvem previamente implementada.

## Descrição do Projeto
O projeto de implementação foi dividido em três etapas, cada uma contemplando um serviço AWS essencial para suportar as operações da empresa. A seguir, serão descritas as etapas do projeto:

**Etapa 1: Amazon EC2 (Elastic Compute Cloud)**
**Foco da ferramenta:** Hospedagem e processamento de aplicações

**Descrição do caso de uso:**
O Amazon EC2 foi escolhido para hospedar o sistema principal da farmácia, incluindo aplicações de gestão de estoque, pedidos, fornecedores e distribuição. Com o EC2, a empresa elimina a necessidade de investir em servidores físicos, reduzindo custos com aquisição, manutenção e energia elétrica.

Além disso, o EC2 permite escalabilidade sob demanda, possibilitando aumentar ou reduzir recursos computacionais conforme o volume de pedidos, especialmente em períodos de alta demanda, como campanhas promocionais ou sazonalidades do setor farmacêutico.

**Etapa 2: Amazon Aurora (RDS)**
**Foco da ferramenta:** Banco de dados relacional gerenciado

**Descrição do caso de uso:**
O Amazon Aurora, serviço de banco de dados relacional compatível com MySQL e PostgreSQL, foi selecionado para armazenar dados críticos da operação, como produtos, lotes, clientes, fornecedores, pedidos e histórico de movimentações.

Por ser um serviço gerenciado, o Aurora reduz significativamente os custos e esforços com administração de banco de dados, como backups, atualizações e alta disponibilidade. Sua arquitetura distribuída oferece alta performance, resiliência e segurança, características essenciais para um ambiente farmacêutico que exige confiabilidade e integridade dos dados.

**Etapa 3: AWS Lambda**
**Foco da ferramenta:** Processamento serverless e automação

**Descrição do caso de uso:**
O AWS Lambda foi proposto para realizar processamentos automáticos e tarefas assíncronas, como:
- Atualização automática de preços e estoques de fornecedores parceiros;
- Processamento de eventos de entrada e saída de produtos;
- Integração com sistemas externos (APIs de fabricantes e farmácias);
- Geração de notificações e relatórios operacionais.
- Por adotar o modelo serverless, o Lambda elimina custos com servidores ociosos, cobrando apenas pelo tempo de execução das funções. Isso resulta em uma redução imediata de custos e maior agilidade na implementação de novas rotinas de negócio.

## Conclusão
A implementação dos serviços Amazon EC2, Amazon Aurora e AWS Lambda na empresa Abstergo Industries tem como resultado esperado a redução de custos operacionais, maior eficiência dos processos, escalabilidade automática e aumento da confiabilidade da infraestrutura de TI.

Essas soluções permitem que a empresa concentre seus esforços no negócio principal — a distribuição farmacêutica — sem a complexidade da gestão de infraestrutura física. Recomenda-se a continuidade da utilização das ferramentas implementadas e a avaliação futura de novos serviços AWS, como monitoramento, segurança e análise de dados, para evolução contínua da arquitetura.

Assinatura do Responsável pelo Projeto:

Thiago Santos Pires
