# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 15/01/2026<br>
**Empresa:** Abstergo Industries<br>
**Responsável:** Estevam Muniz<br>

## Introdução

Este relatório apresenta a proposta de implementação de serviços em nuvem na empresa Abstergo Industries, atuante como hub de distribuição para múltiplas redes de farmácias, responsável por operações críticas de logística, armazenagem e integração com parceiros comerciais.

O objetivo do projeto é recomendar o uso estratégico de serviços da AWS visando redução imediata de custos operacionais, alta escalabilidade, agilidade nos processos logísticos e analíticos e segurança da informação, atendendo às exigências regulatórias do setor farmacêutico.

## Descrição do Projeto

O projeto de implementação foi dividido em 3 etapas, cada uma focada em um pilar estratégico do negócio: infraestrutura, processamento de dados e segurança e governança.

## Etapa 1:

### Serviço: Amazon EC2 com Auto Scaling

**Foco da ferramenta:** Infraestrutura escalável e otimização de custos

**Descrição de caso de uso:**
O Amazon EC2, em conjunto com o Auto Scaling, permite ajustar automaticamente a capacidade computacional de acordo com a demanda operacional, como picos de pedidos, campanhas promocionais ou sazonalidades do setor farmacêutico.
Essa abordagem elimina a necessidade de superdimensionamento da infraestrutura, reduzindo custos com servidores ociosos e garantindo alta disponibilidade para sistemas de gestão de pedidos, estoque e integração com redes de farmácias.

## Etapa 2:

### Serviço: Amazon S3 + AWS Glue

**Foco da ferramenta:** Armazenamento de dados e integração de informações

**Descrição de caso de uso:**
O Amazon S3 será utilizado como repositório central de dados operacionais e históricos, incluindo movimentação de estoque, notas fiscais, pedidos e dados logísticos.
O AWS Glue permitirá a automação dos processos de extração, transformação e carga (ETL), integrando dados provenientes de ERPs, sistemas legados e parceiros externos.
Essa arquitetura reduz custos com armazenamento tradicional, melhora a rastreabilidade de informações e viabiliza análises futuras com rapidez e baixo custo.

## Etapa 3:

### Serviço: AWS IAM + AWS KMS

**Foco da ferramenta:** Segurança da informação e conformidade regulatória

**Descrição de caso de uso:**
O AWS Identity and Access Management (IAM) garante controle rigoroso de acesso aos sistemas e dados, aplicando o princípio do menor privilégio para colaboradores, parceiros e sistemas automatizados.
O AWS Key Management Service (KMS) assegura a criptografia dos dados sensíveis, tanto em repouso quanto em trânsito, atendendo a requisitos de compliance e boas práticas de segurança exigidas no setor farmacêutico.
Essa combinação reduz riscos de vazamento de dados, acessos indevidos e incidentes de segurança.

## Conclusão

A implementação dos serviços AWS na empresa XYZ Pharma Distribution tem como expectativa a redução significativa de custos operacionais, maior flexibilidade para crescimento, agilidade nos processos de integração e análise de dados e elevação do nível de segurança da informação.

A adoção dessa arquitetura em nuvem cria uma base tecnológica sólida para suportar a expansão do negócio, novos parceiros comerciais e futuras iniciativas de análise avançada e automação logística. Recomenda-se a continuidade da evolução da arquitetura AWS e a avaliação periódica de novos serviços que possam ampliar ainda mais a eficiência operacional da empresa.

## Anexos

1- [Arquitetura Proposta](stvmmuniz_Anexo1_Arquitetura_Proposta.md)

2- [Estimativa de custos comparativa (on-premises x AWS)](stvmmuniz_Anexo2_Comparativo_Custos.md)

3- [Plano inicial de migração e cronograma](stvmmuniz_Anexo3_Cronograma.md)

Assinatura do Responsável pelo Projeto:

Moacir Muniz


