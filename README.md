# MVP - Pipeline de Dados para Análise Fundamentalista no Setor de Geração de Energia Elétrica

## Introdução

Este projeto é um MVP (Minimum Viable Product) desenvolvido como parte do trabalho da disciplina de Engenharia de Dados da PUC-RIO. O objetivo principal é construir um pipeline de dados que auxilie analistas de investimentos, especialmente aqueles que realizam análises fundamentalistas (equity research), a obter e analisar informações financeiras de empresas do segmento de geração de energia elétrica.

### Sobre o PGERA (Power Generation Equity Research Assistant)

O PGERA (Power Generation Equity Research Assistant) foi concebido como uma ferramenta especializada para apoiar analistas de investimentos que se concentram especificamente no setor de geração de energia elétrica. Este assistente visa atender às necessidades dos analistas especialistas neste segmento, que precisam de acesso rápido e estruturado a dados financeiros e operacionais para realizar avaliações precisas.

É importante ressaltar que muitas empresas do setor elétrico atuam em múltiplos segmentos da cadeia energética (geração, transmissão e distribuição). Nestes casos, o PGERA fornece suporte ao analista especializado em geração, que deverá trabalhar em colaboração com analistas especializados nas áreas de transmissão e distribuição para realizar uma avaliação completa e integrada da empresa. 

## Contexto do Trabalho

Este trabalho integra o desenvolvimento prático das competências adquiridas na disciplina de Engenharia de Dados. Com o crescimento da complexidade dos mercados e a necessidade de análises cada vez mais precisas, o foco deste projeto é facilitar a obtenção e padronização dos dados extraídos das demonstrações financeiras das empresas do setor elétrico.

A análise fundamentalista é essencial para o processo de valuation (avaliação) das empresas, permitindo aos analistas determinar o valor justo das ações com base em dados financeiros concretos, comparando-os com o preço atual de mercado para identificar oportunidades de investimento. Este pipeline visa fornecer dados estruturados que possam alimentar modelos de valuation, facilitando decisões estratégicas de investimento baseadas em evidências.

## Objetivos do Projeto

O principal objetivo deste MVP é desenvolver um pipeline de dados inicial que permita:

- **Coleta Automatizada:** Obtenção de dados padronizados das demonstrações financeiras periódicas (DFPs) das empresas.
- **Integração e Padronização:** Consolidação e tratamento básico dos dados financeiros, garantindo consistência para análises preliminares.
- **Suporte à Análise Fundamentalista:** Preparação dos dados financeiros essenciais para que analistas possam extrair insights sobre o desempenho das empresas do setor elétrico.

Embora a visão de longo prazo inclua a integração de dados de notícias, informações de agências reguladoras (como dados sobre usinas e consumo de energia) e análises de outros especialistas, o foco inicial deste MVP está na estruturação dos dados financeiros fundamentais.

Em fases futuras, o PGERA também poderá incorporar modelos de linguagem (LLMs) para potencializar as análises fundamentalistas, estabelecendo correlações entre os dados estruturados das DFPs e informações textuais disponíveis em fontes diversas, como notícias públicas, press releases e notas explicativas. Esta abordagem permitirá contextualizar variações significativas nos dados financeiros. Por exemplo, um aumento expressivo nos ativos de uma empresa de um ano para outro poderia ser automaticamente correlacionado com anúncios de aquisições divulgados em press releases ou detalhados nas notas explicativas das DFPs, proporcionando aos analistas insights contextualizados que explicam as mudanças nos indicadores financeiros. Além disso, os LLMs poderão auxiliar na geração interativa de relatórios, onde o analista mantém o controle editorial enquanto o sistema sugere estruturas, formula análises preliminares com base nos dados processados e ajuda a redigir seções específicas do documento, acelerando significativamente o processo de elaboração de relatórios sem comprometer a qualidade e o julgamento profissional do especialista.

## Perguntas a Responder

As seguintes perguntas foram definidas para orientar o desenvolvimento do projeto:

- **Quais indicadores financeiros são mais relevantes para análise de empresas específicas do setor de geração de energia elétrica?**
- **Como identificar padrões e tendências nos dados financeiros que sejam específicos das empresas de geração de energia?**
- **De que forma a estruturação e padronização das DFPs pode facilitar comparações entre empresas do setor elétrico?**
- **Como integrar dados financeiros estruturados com informações contextuais das notas explicativas para enriquecer a análise?**
- **Quais métricas operacionais específicas do setor de geração (como capacidade instalada, fator de capacidade, etc.) podem complementar a análise financeira?**
- **Como um sistema de pipeline de dados pode acelerar a produção de relatórios de análise sem comprometer a qualidade do trabalho do analista?**
- **De que maneira os LLMs podem apoiar a interpretação das variações significativas nos indicadores financeiros entre períodos?**

> **Observação:** Nesta fase inicial do MVP, o foco estará principalmente no tratamento das demonstrações financeiras padronizadas (DFPs). As demais questões representam direções para expansão futura do projeto.