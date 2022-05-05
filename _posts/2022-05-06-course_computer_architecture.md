---
title: Curso de Arquitetura de Computadores
author: Leandro Santiago
date: 2022-05-05 15:00:00
categories: [Courses, Arquitetura de Computadores]
tags: [cursos, arquitetura de computadores, organização de computadores]
---

## Objetivo

Apresentar técnicas e conceitos usados no desenvolvimento de processadores modernos:

- **Paralelismo em nível de instrução (ILP)**
   - Pipelining
   - Branch prediction
   - Execução de instrução fora-de-ordem
   - Superescalares
- **Paralelismo em nível de threads (TLP)**
   - Multiprocessadores
   - Protocolos de coerência de cache
   - APIs de programação paralela
- Entre outros ...



 [Playlist no YouTube](https://youtube.com/playlist?list=PLBw9d_OueVJQV_O4qEvC2e5TQ5RZeL9BD)


## Ementa 

ARQUITETURA DE CONJUNTO DE INSTRUÇÕES, ANÁLISE DE CUSTO,  DESEMPENHO E GASTO DE ENERGIA. CONCEITO DE CACHE, OTIMIZAÇÕES DE DESEMPENHO DE CACHE. MEMÓRIA VIRTUAL. MÁQUINAS VIRTUAIS. CONCEITO DE PIPELINE. PREDIÇÃO DE DESVIOS. ESCALONAMENTO DINÂMICO. ESPECULAÇÃO POR HARDWARE. ARQUITETURA VETORIAL. INSTRUÇÕES SIMD PARA MULTIMÍDIA. GPUS. DETECÇÃO DE PARALELISMO NO NÍVEL DE LAÇO. ARQUITETURAS DE MULTIPROCESSADORES COM MEMÓRIA COMPARTILHADA COM ACESSO UNIFORME E NÃO UNIFORME À MEMÓRIA. CONCEITOS BÁSICOS DE SINCRONIZAÇÃO. CONCEITOS BÁSICOS DE CONSISTÊNCIA DE MEMÓRIA.



## Conteúdo Programático

1. **`Introdução ao Projeto de Sistemas Computacionais`**
   1. Contextualização e Breve Revisão da Arquitetura Multicamada, Multi-Linguagem
   2. Métricas de Avaliação: Desempenho, Custos
2. **`Arquiteturas de Conjunto de Instruções`**
   1. Projeto de Construção de um Conjunto de Instruções
   2. Implementação MIPS: Monociclo e Multiciclo
3. **`Projeto de Hierarquia de Memória`**
   1. Revisão dos Conceitos e Funcionamento de Caches
   2. Otimização de Desempenho de Cache
   3. Coerência de Caches
4. **`Conceito de Pipelining`**
   1. Funcionalidade e Limitação (Dependências/Hazards)
   2. Técnicas de Otimização Estática e Dinâmica
   3. Predição de Desvios e Execução Especulativa
5. **`Arquiteturas Paralelas`**
   1. Taxonomia de Flynn
   2. Máquinas Superescalares e VLIW
   3. Paralelismo em Arquiteturas SIMD
      1. Processadores Vetoriais
      2. Visão de Arquiteturas de GPGPUS
      3. Extensões SIMD em Conjuntos de Instruções (ISAS) modernos
   4. Arquiteturas MIMD
      1. Multiprocessadores com Memória Compartilhada
      2. Multiprocessadores com Memória Distribuída
 
## Aulas

{% include class-videos.html course=site.data.courses.computer_architecture %}


## Bibliografia

- Organização e Projeto de Computadores – A Interface Hardware/Software. David A. Patterson e John L. Hennessy, Edição 5, 2017

- Arquitetura de Computadores – Uma Abordagem Quantitativa. David A. Patterson e John L. Hennessy, Edição 6, 2017

- Arquitetura e Organização de Computadores. William Stalling, Edição 10, 2015



