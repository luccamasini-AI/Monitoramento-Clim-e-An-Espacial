# Contexto - Front End & Mobile Development (Disciplina 04)

## Objetivo
Projetar um dashboard frontend utilizando **Streamlit** ou **Gradio** que consuma dados satelitais, climáticos ou de geolocalização para visualização em tempo real.

## Requisitos Iniciais
- O dashboard deve ser responsivo e apresentar componentes dinâmicos.
- Inclusão de gráficos interativos e filtros.
- Deve facilitar a tomada de decisão em problemas como agricultura ou desastres ambientais.

## Estratégia de Desenvolvimento
- **Independência**: Como a integração total do projeto do grupo é incerta, o Front End será desenvolvido para operar de forma totalmente independente.
- **Mocks**: Utilizaremos dados fictícios (mocks) de satélite inicialmente para simular as respostas da API e garantir que a interface gráfica e seus gráficos estejam 100% funcionais.
- **Preparação para Integração**: Os dados consumidos seguirão um formato pré-estabelecido (ex: JSON), de forma que bastará apontar o endpoint para a API de Visão Computacional dos colegas posteriormente para realizar a integração.

## Status Atual
- **V1.1 Concluída (UI Refinada)**: Toda a arquitetura do Streamlit foi implementada e o design da interface polido.
- Foi aplicado um tema escuro e efeitos de *Glassmorphism* usando injeção de CSS para um visual premium (sem botões ou barras de menu nativas expostas).
- O layout foi migrado para um fluxo de **Data Storytelling vertical** (scroll), permitindo que os gráficos do Plotly ganhassem respiro e alturas fixas maiores, evitando poluição visual.
- Aguardando o dataset real (prometido para o próximo passo) para substituir a função geradora em `data/mock_generator.py`.
