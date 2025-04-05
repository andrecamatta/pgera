# MVP - Pipeline de dados para análise fundamentalista no setor de geração de energia elétrica

![PGERA Logo](pgera_logo.png)

## Introdução

Este projeto é um MVP (Minimum Viable Product) desenvolvido como parte do trabalho da disciplina de Engenharia de Dados da PUC-RIO. O objetivo principal é construir um pipeline de dados que auxilie analistas de investimentos, especialmente aqueles que realizam análises fundamentalistas (equity research), a obter e analisar informações financeiras de empresas do segmento de geração de energia elétrica.

### Sobre o PGERA (Power Generation Equity Research Assistant)

A ideia do PGERA (Power Generation Equity Research Assistant) foi concebida dada a necessidade de uma ferramenta especializada para apoiar analistas de investimentos que se concentram especificamente no setor de geração de energia elétrica. Este assistente visa atender às necessidades dos analistas especialistas neste segmento, que precisam de acesso rápido e estruturado a dados financeiros e operacionais para realizar avaliações.

É importante ressaltar que muitas empresas do setor elétrico atuam em múltiplos segmentos da cadeia energética (geração, transmissão e distribuição). Nestes casos, o PGERA poderá fornecer suporte ao analista especializado em geração, que deverá trabalhar em colaboração com analistas especializados nas áreas de transmissão e distribuição para realizar uma avaliação completa e integrada da empresa. 

## Contexto do trabalho

Este trabalho integra o desenvolvimento prático das competências adquiridas na disciplina de Engenharia de Dados. Com o crescimento da complexidade dos mercados e a necessidade de análises cada vez mais precisas, o foco deste projeto é facilitar a obtenção e padronização dos dados extraídos das demonstrações financeiras das empresas do setor elétrico.

A análise fundamentalista é essencial para o processo de valuation (avaliação) das empresas, permitindo aos analistas determinar o valor justo das ações com base em dados financeiros concretos, comparando-os com o preço atual de mercado para identificar oportunidades de investimento. Este pipeline visa fornecer dados estruturados que possam alimentar modelos de valuation, facilitando decisões estratégicas de investimento.

## Objetivos do projeto

O principal objetivo deste MVP é desenvolver um pipeline de dados inicial que permita:

- **Coleta automatizada:** Obtenção de dados padronizados das demonstrações financeiras periódicas (DFPs) das empresas, no site da CVM.
- **Integração e padronização:** Consolidação e tratamento básico dos dados financeiros, garantindo consistência para análises preliminares.
- **Instrumental intermediário de análise:** Preparação dos dados financeiros para fazer análises de balanço tais como análise horizontal e vertical, alavancagem operacional e financeira, estudo do fluxo de fundos no ativo circulante, acompanhamento de indicadores de liquidez e de ciclo operacional, entre muitos outros. 

Embora a visão de longo prazo inclua a integração de dados de notícias, informações de agências reguladoras (como dados sobre usinas e consumo de energia) e análises de outros especialistas, o foco inicial deste MVP está na estruturação dos dados financeiros fundamentais.

O instrumental intermediário de análise de balanços por si só não é suficiente para uma análise econômica financeira mais conclusiva. Dessa forma, em fases futuras, o PGERA também poderá incorporar modelos de linguagem (LLMs) para potencializar as análises fundamentalistas, estabelecendo correlações entre os dados estruturados das DFPs e informações textuais disponíveis em fontes diversas, como notícias públicas, press releases e notas explicativas. 

Essa abordagem permitirá contextualizar variações significativas nos dados financeiros. Por exemplo, um aumento expressivo nos ativos de uma empresa de um ano para outro poderia ser correlacionado, de forma automática, com anúncios de aquisições divulgados em press releases ou detalhados nas notas explicativas das DFPs, proporcionando aos analistas insights contextualizados que explicam as mudanças nos indicadores financeiros. 

Além disso, as LLMs poderão auxiliar na geração interativa de relatórios, onde o analista mantém o controle editorial enquanto o sistema sugere estruturas, formula análises preliminares com base nos dados processados e ajuda a redigir seções específicas do documento, acelerando significativamente o processo de elaboração de relatórios sem comprometer a qualidade e o julgamento profissional do especialista.