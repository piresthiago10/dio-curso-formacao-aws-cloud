# RELATÓRIO DE IMPLEMENTAÇÃO DE MEDIDAS DE SEGURANÇA AWS

**Data:** 15/01/2026\
**Empresa:** Abstergo Industries\
**Responsável:** Thiago Santos Pires

## Introdução

Este relatório apresenta a proposta de implementação de **medidas de
segurança em nuvem** na empresa **Abstergo Industries**, que atua como
um hub de distribuição farmacêutica. Considerando que a empresa não
possuía nenhuma estratégia de segurança em cloud previamente definida,
este documento tem como objetivo elencar **três serviços de segurança da
Amazon Web Services (AWS)** visando **redução de riscos**, **proteção de
dados sensíveis** e **adequação às boas práticas de segurança da
informação**, sem impactar negativamente os custos operacionais.

## Descrição do Projeto

O projeto foi dividido em **três etapas**, cada uma abordando uma medida
de segurança essencial para a proteção dos sistemas, dados e aplicações
da empresa em ambiente AWS.

### Etapa 1: AWS Identity and Access Management (IAM)

**Foco da ferramenta:** Controle de acesso e gerenciamento de
identidades

O AWS IAM foi proposto como a principal ferramenta para **gerenciamento
de usuários, permissões e acessos** aos recursos da AWS. Através do IAM,
a empresa pode aplicar o **princípio do menor privilégio**, garantindo
que cada usuário, sistema ou serviço tenha acesso apenas aos recursos
estritamente necessários para sua função.

Principais benefícios: - Controle granular de permissões\
- Uso de roles para serviços e aplicações\
- Implementação de autenticação multifator (MFA)\
- Redução de acessos não autorizados

### Etapa 2: AWS Key Management Service (KMS)

**Foco da ferramenta:** Criptografia e proteção de dados sensíveis

O AWS KMS foi selecionado para garantir a **criptografia de dados em
repouso e em trânsito**, protegendo informações como dados de clientes,
fornecedores e pedidos.

Principais benefícios: - Gerenciamento centralizado de chaves\
- Integração nativa com serviços AWS\
- Controle de acesso às chaves via IAM\
- Rotação automática de chaves

### Etapa 3: AWS Web Application Firewall (WAF)

**Foco da ferramenta:** Proteção de aplicações web

O AWS WAF foi proposto para proteger aplicações web e APIs expostas à
internet contra ataques comuns.

Principais benefícios: - Bloqueio de ataques como SQL Injection e XSS\
- Criação de regras personalizadas\
- Monitoramento de tráfego malicioso\
- Integração com ALB e CloudFront

## Conclusão

A adoção dos serviços **AWS IAM, AWS KMS e AWS WAF** fornece uma base
sólida de segurança em nuvem para a *Abstergo Industries*, reduzindo
riscos, protegendo dados sensíveis e aumentando a confiabilidade das
aplicações.

Recomenda-se a evolução contínua da estratégia de segurança,
incorporando novos serviços e práticas conforme a maturidade da operação
em cloud.

## Assinatura

**Thiago Santos Pires**
