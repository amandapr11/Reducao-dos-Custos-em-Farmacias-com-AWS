# Reducao dos Custos em Farmacias com AWS


# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 26 de março de 2026  
**Empresa:** Abstergo Industries  
**Responsável:** Amanda Perin  

## Introdução
Este relatório apresenta o processo de implementação de serviços AWS na empresa **Abstergo Industries**, com o objetivo de reduzir custos operacionais imediatos, aumentar a escalabilidade do ambiente tecnológico e melhorar a eficiência dos processos internos.

A proposta do projeto consistiu em selecionar **3 serviços da AWS** capazes de otimizar a infraestrutura da empresa, substituindo ou reduzindo gastos com recursos locais, manutenção manual e desperdício de capacidade computacional.

## Descrição do Projeto
O projeto de implementação foi dividido em 3 etapas, cada uma com objetivos específicos voltados à redução de custos e modernização da infraestrutura.

### Etapa 1: Amazon EC2 Auto Scaling
- **Nome da ferramenta:** Amazon EC2 Auto Scaling  
- **Foco da ferramenta:** Escalabilidade automática de instâncias computacionais  
- **Descrição de caso de uso:**  
A empresa possuía servidores provisionados de forma fixa para suportar picos de acesso ao sistema. Esse modelo gerava desperdício de recursos em horários de baixa demanda, elevando os custos de infraestrutura.

Com a implementação do **Amazon EC2 Auto Scaling**, passou a ser possível ajustar automaticamente a quantidade de instâncias EC2 conforme a demanda real da aplicação. Dessa forma, a empresa mantém desempenho adequado nos horários de pico e reduz custos em períodos de menor utilização, pagando apenas pelos recursos efetivamente necessários.

### Etapa 2: Amazon S3
- **Nome da ferramenta:** Amazon S3  
- **Foco da ferramenta:** Armazenamento escalável e de baixo custo  
- **Descrição de caso de uso:**  
A empresa armazenava documentos, arquivos de backup e relatórios em servidores locais ou volumes com custo mais elevado, o que exigia manutenção e limitava a escalabilidade.

Com a adoção do **Amazon S3**, os arquivos passaram a ser armazenados em uma solução segura, altamente durável e com melhor custo-benefício. Além disso, a empresa pode utilizar classes de armazenamento apropriadas para diferentes perfis de acesso, reduzindo ainda mais os gastos com dados pouco acessados, como backups e arquivos históricos.

### Etapa 3: Amazon RDS
- **Nome da ferramenta:** Amazon RDS  
- **Foco da ferramenta:** Gerenciamento simplificado de banco de dados  
- **Descrição de caso de uso:**  
A manutenção de bancos de dados em servidores próprios demandava esforço da equipe com instalação, atualizações, backups, monitoramento e recuperação em caso de falhas.

Com a implementação do **Amazon RDS**, a empresa passou a contar com um banco de dados gerenciado, com recursos de backup automatizado, aplicação de patches, monitoramento e alta disponibilidade. Isso reduziu o custo operacional associado à administração manual da infraestrutura de banco de dados e permitiu que a equipe técnica focasse em atividades mais estratégicas.

## Conclusão
A implementação dos serviços **Amazon EC2 Auto Scaling**, **Amazon S3** e **Amazon RDS** na **Abstergo Industries** trouxe benefícios imediatos relacionados à redução de custos, melhoria de desempenho operacional e aumento da eficiência da infraestrutura.

Entre os principais ganhos observados, destacam-se:
- redução do desperdício de recursos computacionais;
- diminuição de custos com armazenamento;
- menor esforço de administração de banco de dados;
- maior escalabilidade e confiabilidade dos serviços;
- melhor aproveitamento da equipe técnica.

Dessa forma, conclui-se que a adoção dessas ferramentas representa um passo importante para a modernização tecnológica da empresa. Recomenda-se a continuidade da utilização dos serviços implementados, bem como a avaliação de novas soluções em nuvem que possam ampliar ainda mais os ganhos operacionais e financeiros.

## Anexos
- Planilha de estimativa de custos antes e depois da migração
- Documento de arquitetura da solução
- Registro das configurações dos serviços AWS
- Relatório de testes de desempenho
- Manual básico de operação do ambiente

**Assinatura do Responsável pelo Projeto:**  

Amanda Perin
