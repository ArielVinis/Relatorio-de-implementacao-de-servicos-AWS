# Relatorio de implementacao de servicos AWS

```
Data: 27/08/2025
Empresa: Drogaria e Farmácia Savaris
Responsável: Ariel França
```

## Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa Drogaria e Farmácia Savaris, realizado por Ariel França. O objetivo do projeto foi elencar 3 serviços AWS que possibilitem a redução imediata de custos, além de preparar a empresa para um crescimento sustentável e seguro no ambiente de nuvem.

## Descrição do Projeto

O projeto de implementação foi dividido em 3 etapas, cada uma com seus objetivos específicos:

### Etapa 1:
```
- Nome da ferramenta: Amazon S3 (Simple Storage Service)

- Foco da ferramenta: Armazenamento de dados com alta durabilidade e baixo custo.

- Descrição de caso de uso:
Atualmente, a empresa armazena dados em servidores locais, com alto custo de manutenção e risco de perda. Com o Amazon S3, todos os documentos administrativos, resultados laboratoriais e arquivos de pesquisa poderão ser migrados para a nuvem, garantindo durabilidade de 99,99%, escalabilidade automática e custo proporcional ao uso. Além disso, será possível utilizar políticas de arquivamento no S3 Glacier para reduzir ainda mais os custos com dados pouco acessados.
```

### Etapa 2:
```
Nome da ferramenta: Amazon RDS (Relational Database Service)

Foco da ferramenta: Banco de dados gerenciado e otimizado.

Descrição de caso de uso:
A empresa utiliza servidores próprios para gerenciar bancos de dados internos, o que gera custos elevados com licenciamento, energia e administração. Com o Amazon RDS, a PharmaVida poderá migrar seus bancos de dados (como estoque, vendas e cadastros de clientes) para um ambiente totalmente gerenciado, sem necessidade de manutenção de hardware ou backup manual. O serviço traz alta disponibilidade, segurança e escalabilidade automática, permitindo pagar apenas pelo que é consumido.
```

### Etapa 3:
```
Nome da ferramenta: Amazon EC2 (Elastic Compute Cloud) com Auto Scaling

Foco da ferramenta: Hospedagem de sistemas corporativos com escalabilidade elástica.

Descrição de caso de uso:
A empresa possui aplicações internas, como ERP e sistemas de controle de produção, que hoje funcionam em servidores físicos. Com o Amazon EC2, esses sistemas poderão ser migrados para máquinas virtuais na nuvem, com capacidade de ajuste automático de recursos através do Auto Scaling. Assim, nos horários de pico, a infraestrutura será expandida automaticamente, e em horários de baixa demanda, será reduzida — diminuindo os custos operacionais e garantindo desempenho ideal.
```

## Conclusão

### A implementação das ferramentas na empresa Drogaria e Farmácia Savaris permitirá:

- Redução imediata de custos com infraestrutura física.

- Maior segurança no armazenamento e backup de dados.

- Escalabilidade e alta disponibilidade nos serviços críticos da empresa.

- Eliminação de manutenções complexas em servidores locais.

> Recomenda-se a continuidade da utilização das ferramentas implementadas e a análise de novos serviços AWS, como AWS Lambda (serverless) e Amazon CloudFront (otimização de distribuição de conteúdo), que podem trazer ganhos ainda maiores no futuro.

## Anexos

### 1. Guia de Boas Práticas de Migração para AWS

- Avaliação detalhada do ambiente atual antes da migração.
- Planejamento de etapas e cronograma para minimizar impactos.
- Utilização de ferramentas nativas da AWS para migração segura (AWS Migration Hub, AWS Database Migration Service).
- Testes de integridade e performance após a migração.
- Implementação de políticas de segurança e backup automatizado.

### 2. Comparativo de Custos: Servidores Locais vs AWS

A tabela abaixo apresenta uma análise comparativa dos custos anuais entre a infraestrutura tradicional (on-premise) e a AWS, evidenciando a economia potencial:

| Categoria                  | On-Premise (R$) | AWS (R$) | Economia (R$) |
|----------------------------|-----------------|----------|---------------|
| Armazenamento de Dados     | 12.000          | 4.000    | 8.000         |
| Banco de Dados             | 8.000           | 3.000    | 5.000         |
| Servidores de Aplicação    | 15.000          | 6.000    | 9.000         |
| Energia/Manutenção         | 5.000           | 1.000    | 4.000         |
| Licenciamento de Software  | 4.000           | 1.000    | 3.000         |
| **Total**                  | **44.000**      | **15.000** | **29.000**   |

> **Observação:** Os valores são estimativas anuais e podem variar conforme o uso e a demanda dos serviços.

### 3. Documentação Oficial dos Serviços Utilizados

- [Amazon S3](https://docs.aws.amazon.com/pt_br/s3/index.html)
- [Amazon RDS](https://docs.aws.amazon.com/pt_br/rds/index.html)
- [Amazon EC2](https://docs.aws.amazon.com/pt_br/ec2/index.html)

---

## 👤 Autor

Desenvolvido por **Ariel França**.
