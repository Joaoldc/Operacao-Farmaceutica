# Operacão Farmaceutica
Projeto para implementação de serviços AWS

# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 01/10/2025
Empresa: Natura Farmaco 
Responsável: João Luiz

## Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa Natura Farmaco, realizado por João Luiz. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos. 
A Análise dos serviços disponíveis e a aplicação será feita com supervisão técnica prévia para e escolha do melhor recurso aplicado e acompanhamento durante o processo de implementação, processo de possíveis melhorias, correções e alterações e finalização.

## Descrição do Projeto

O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- Amazon S3 (Simple Storage Service)
- Armazenamento de objetos escaláveis na nuvem.
- Suporta arquivos grandes, logs, imagens, vídeos e dados estruturados ou não estruturados.
- Armazenar dados clínicos de pesquisas, resultados laboratoriais e documentação regulatória.

# Casos de Uso

- Substituir servidores físicos de armazenamento, evitando custos com manutenção, energia e espaço físico.
- Benefício de custo: Pagamento apenas pelo armazenamento utilizado. Classes de armazenamento como Intelligent-Tiering podem otimizar o custo automaticamente, movendo dados menos acessados para camadas mais baratas.

Etapa 2: 
- Amazon RDS (Relational Database Service)
- Banco de dados relacional gerenciado (MySQL, PostgreSQL, SQL Server, etc.) Cuida de backups, patching e escalabilidade
  automaticamente.

# Casos de Uso

- Centralizar informações de estoque, fornecedores e vendas de medicamentos. Permitir integração com sistemas de pesquisa e produção, mantendo dados consistentes. Escalabilidade elástica evita superdimensionamento de servidores.
- Reduz o gasto com administração de banco de dados local, hardware e licenças de software.


Etapa 3: 
- Combinação de AWS Lambda + Amazon EventBridge
- Lambda: serviço de computação sem servidor que executa código sob demanda.
- EventBridge: serviço de eventos que permite reagir a mudanças nos dados ou eventos do sistema.

# Casos de Uso

- Automatizar processos de monitoramento de estoque de insumos, alertas de validade ou atualização de relatórios.
- Executar cálculos ou análises de dados de produção sem manter servidores ligados 24h.
-Paga apenas pelo que usa, sem necessidade de manter servidores ativos o tempo todo.
-Reduz custo operacional e melhora a eficiência dos processos repetitivos.


## Conclusão
A implementação de ferramentas na empresa Natura Farmaco tem como esperado a diminuição de servidores locais e suas manutenções, controle automático de armazenamento de dados, disponibilização constante dos mesmos, o que aumentaria a eficiência e a produtividade da empresa comparando a momentos de inoperabilidade por falhas se servidor etc. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

https://aws.amazon.com/pt/

Assinatura do Responsável pelo Projeto:

João Luiz
