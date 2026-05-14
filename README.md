# MCA - Perfil de Consumo em Streaming

Este repositório apresenta um exemplo didático de **Análise de Correspondência Múltipla (MCA)** usando um dataset fictício sobre comportamento de clientes em plataformas de streaming.

## Arquivos

- `clientes_streaming_mca.csv`: dataset fictício com variáveis categóricas.
- `MCA_streaming_clientes.ipynb`: notebook com a análise completa em Python.

## Variáveis do dataset

- `cliente_id`: identificador do cliente.
- `faixa_etaria`: faixa etária do cliente.
- `dispositivo_principal`: dispositivo mais utilizado para assistir streaming.
- `conteudo_preferido`: tipo de conteúdo mais consumido.
- `tipo_plano`: tipo de assinatura.
- `periodo_uso`: período mais comum de uso.

## Objetivo

Aplicar MCA para investigar associações entre categorias, transformando variáveis categóricas em coordenadas numéricas e representando essas associações em um mapa perceptual.

## Diferença prática entre ANACOR e MCA

Na ANACOR, o input geralmente é uma matriz de contingência entre duas variáveis categóricas. Na MCA, o input é o banco de dados original com múltiplas variáveis categóricas.
