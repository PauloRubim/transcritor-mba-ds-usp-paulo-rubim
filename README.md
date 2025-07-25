# 📚 Sistema de Transcrição Fonética Adaptada para Falantes de Português Brasileiro

Este projeto propõe o desenvolvimento de um sistema de transcrição fonética automatizada do inglês, utilizando uma representação simbólica adaptada à fonologia do português brasileiro. O objetivo é auxiliar falantes nativos de português na compreensão da pronúncia da língua inglesa, tornando a aprendizagem mais intuitiva e acessível.

## ✨ Destaques

- Representação fonética adaptada com **grafia simplificada e recursos visuais** (como cores e acentos).
- Modelo treinado em **redes neurais Sequence-to-Sequence** com mecanismo de **atenção**.
- Sistema projetado para ser didático e amigável para **aprendizes iniciantes de inglês**.
- Processamento robusto de base de dados via **web scraping** e **ampliação de frases**.
- Resultados com **alta precisão**: ROUGE-L > 0,97, Acurácia de 91% e Taxa de Erro por Caractere (CER) de apenas 1,1%.

## 📦 Principais Tecnologias Utilizadas

- **Python**
- **TensorFlow/Keras** (Seq2Seq + Atenção)
- **BeautifulSoup4** (Web Scraping)
- **Pandas** e **NumPy** (Manipulação de dados)

## 📊 Avaliação de Desempenho

- **ROUGE-1 F1:** 0.9852
- **ROUGE-2 F1:** 0.9466
- **ROUGE-L F1:** 0.9852
- **CER:** 0.011
- **Acurácia de Transcrições Completas:** 91%

## 📋 Limitações Conhecidas

- Sensibilidade limitada a **pontuações** (vírgulas, pontos) e **diferenças entre maiúsculas e minúsculas**.
- Latência maior durante a inferência, típica de modelos baseados em **LSTM com atenção**.
- Base de dados proveniente majoritariamente de uma única fonte.
- Tem dificuldades com textos grandes (mais de 15 palavras). 

## 🚀 Trabalhos Futuros

- Expansão da base de dados com múltiplas fontes fonéticas.
- Otimização do tempo de inferência com arquiteturas mais leves (Transformers quantizados).
- Avaliação prática com usuários reais em ambientes educacionais.

