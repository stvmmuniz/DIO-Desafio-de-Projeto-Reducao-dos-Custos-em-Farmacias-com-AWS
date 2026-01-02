# Anexo 1 – Arquitetura Proposta
## Visão Geral da Arquitetura

A arquitetura proposta utiliza serviços gerenciados da AWS para garantir alta disponibilidade, elasticidade, segurança e otimização de custos, atendendo às necessidades de uma empresa farmacêutica que atua como hub de distribuição.

### Componentes Principais:

* **Amazon EC2 com Auto Scaling** <br>
Responsável por hospedar sistemas operacionais críticos, como:

    * Sistema de Gestão de Pedidos

    * Sistema de Controle de Estoque

    * APIs de integração com redes de farmácias

* **Amazon S3**<br>
Repositório central de dados para:

    * Arquivos fiscais e logísticos

    * Histórico de pedidos e movimentações

    * Dados de integração com parceiros

* **AWS Glue** <br>
Camada de integração e processamento:

    * Consolidação de dados de múltiplas fontes

    * Padronização de informações

    * Preparação de dados para análises futuras

* **AWS IAM e AWS KMS**<br>
Camada transversal de segurança:

    * Controle de acessos por perfil e função

    * Criptografia de dados sensíveis

    * Auditoria e rastreabilidade de acessos

* **Benefícios da Arquitetura**

    * Escala automática conforme a demanda

    * Redução de infraestrutura ociosa

    * Segurança alinhada às exigências do setor farmacêutico

    * Base preparada para futuras iniciativas analíticas e automação