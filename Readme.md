# API-Data-Insights

Projeto para integração com API e visualização de insights no Microsoft Fabric.

## Objetivo

Este projeto consome dados de uma API de Inteligência Artificial, processa-os no Microsoft Fabric e apresenta insights no Power BI. O objetivo é explorar como IA pode auxiliar em análises de dados e visualizações, além de documentar e utilizar as respostas para análises futuras.

## Funcionalidades

- Integração com a OpenAI API para análises avançadas.
- Armazenamento das respostas da IA no OneLake em formato CSV, permitindo análises posteriores.
- Processamento e análise de dados utilizando scripts Python e Spark.
- Visualização de insights no Power BI, incluindo prompts enviados e respostas geradas pela IA.

## Extensões Futuras

- Envio de datasets para análise da IA e geração de insights automatizados.
- Criação de pipelines que coletam perguntas de usuários e enviam para a IA.
- Dashboards detalhados que mostram como a IA foi utilizada, incluindo frequência de temas e categorias detectadas.

## Estrutura do Repositório

- `src/`: Scripts para consumo, processamento e análise de dados.
- `data/`: Exemplos de dados coletados ou processados.
- `docs/`: Documentação adicional e imagens.

## Como Usar

1. Configure sua conta no Microsoft Fabric e habilite um cluster para processamento.
2. Conecte-se à API da IA escolhida (ex.: OpenAI) e configure a chave de API.
3. Execute o pipeline no Fabric para consumir e armazenar os dados no OneLake.
4. Use o Power BI para conectar-se ao Lakehouse e criar visualizações dos insights gerados.

## Contribuição

Sugestões e melhorias são bem-vindas! Abra uma issue ou envie um pull request.

---

Desenvolvido por Alessandra Cruz como parte de um desafio pessoal para aplicar habilidades recém-aprendidas em Engenharia de Dados. 🚀
