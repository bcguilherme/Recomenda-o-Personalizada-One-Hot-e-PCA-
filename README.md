# Recomenda-o-Personalizada-One-Hot-e-PCA-

# Sistema de Recomendação Baseado em Conteúdo

Este notebook implementa um sistema de recomendação baseado em similaridade de conteúdo, explorando duas abordagens:
1. Representação vetorial com one-hot encoding.
2. Representação vetorial com PCA para redução de dimensionalidade.

O conjunto de dados contém metadados de 32 mil jogos da Steam. O pré-processamento inclui extração de características e one-hot encoding para tags e especificações.

## Parte 1: Representação Vetorial Simples
- Normaliza os dados para cálculo de similaridade.
- Calcula a matriz de similaridade item-item usando similaridade cosseno.
- Gera recomendações com base nos escores de similaridade.

## Parte 2: Representação Vetorial com PCA
- Reduz a dimensionalidade dos vetores usando PCA.
- Analisa a variância explicada para determinar o número ideal de componentes.
- Calcula a matriz de similaridade item-item usando vetores transformados por PCA.
- Fornece recomendações com base nos embeddings PCA.

Explore recomendações personalizadas de jogos com facilidade!
