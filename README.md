# **Explorando dados espaciais: Geoprocessamento e Cartografia**  
Bem-vindo ao meu portfólio! Aqui você encontrará projetos que desenvolvi utilizando ferramentas como QGIS, SAGA GIS, Python e outras soluções voltadas para o geoprocessamento e a cartografia. Meu objetivo é apresentar análises espaciais, mapeamentos temáticos e técnicas avançadas de SIG aplicadas a diversos contextos.  

Sinta-se à vontade para explorar e me contatar caso queira discutir algum projeto ou colaboração.  

---  

# Projetos em destaque

## Projeto 1: Análise de Terreno e Cartografia Temática de Bragança, Pará

### Introdução

Este projeto visa realizar uma análise detalhada do terreno do município de **Bragança**, localizado no nordeste do Pará, Brasil. Utilizando o Modelo Digital de Elevação (MDE) com resolução de 30 metros, obtido por meio do **Open Topography** (dados SRTM), foram gerados diversos produtos derivados. Esses produtos, elaborados com o módulo **Basic Terrain Analysis** no **SAGA GIS**, foram posteriormente modelados em **QGIS** para compor mapas temáticos que evidenciam características geomorfológicas, hidrológicas e de uso do solo.

### Objetivos

- Analisar e representar as características topográficas do município de Bragança.
- Criar mapas temáticos detalhados que representem dados de declividade, aspecto, curvatura, índice de umidade, elevação e pedologia.
- Explorar a integração entre ferramentas de SIG (SAGA GIS e QGIS) para gerar produtos cartográficos de alta qualidade.

### Metodologia

1. **Aquisição dos Dados**:
   - Modelo Digital de Elevação (MDE) obtido via **Open Topography** com resolução espacial de 30 metros.
   - Delimitação da extensão territorial do município de Bragança.

2. **Análise de Terreno**:
   - Processamento dos dados no **SAGA GIS** utilizando o módulo **Basic Terrain Analysis** para gerar:
     - Declividade
     - Aspecto do terreno
     - Curvatura (planta e perfil)
     - Índice de umidade topográfica
     - Elevação reclassificada
     - Rede de drenagem derivada

3. **Modelagem Cartográfica**:
   - Layouts elaborados no **QGIS**, incluindo elementos cartográficos como escala, norte e sistema de coordenadas (SIRGAS 2000).
   - Uso de simbologias e combinações de transparências para aprimorar a visualização dos mapas temáticos.

4. **Classificação e Tematização**:
   - Classificação de uso e cobertura do solo a partir de imagens Sentinel-2, obtidas pelo programa Copernicus, utilizando o **Dzetsaka Plugin** no QGIS.
   - Criação de mapas temáticos relacionados à pedologia e sobreposição de elevação.

### Resultados

Os produtos gerados foram organizados em mapas temáticos. Cada mapa é apresentado com uma breve descrição e interpretação:

#### 1. Mapa de Aspecto do Terreno – Município de Bragança, Pará  
![Mapa de Aspecto do Terreno](terrain_analysis/Mapa%20de%20Aspecto%20do%20Terreno%20–%20Município%20de%20Bragança,%20Pará.png)
O aspecto indica a orientação das encostas do terreno. Este mapa é útil para entender a exposição solar e padrões de drenagem.

Aqui está o conteúdo ajustado para exibir as imagens diretamente no `README.md`:

---

#### 2. Mapa de Declividade – Município de Bragança, Pará  
![Mapa de Declividade](terrain_analysis/Mapa%20de%20Declividade%20–%20Município%20de%20Bragança,%20Pará.png)  
A declividade é expressa em graus, destacando áreas com maior suscetibilidade à erosão e deslizamentos.

---

#### 3. Mapa de Curvatura do Terreno – Município de Bragança, Pará  
![Mapa de Curvatura do Terreno](terrain_analysis/Mapa%20de%20Curvatura%20do%20Terreno%20–%20Município%20de%20Bragança,%20Pará.png)  
Representa a curvatura do terreno, diferenciando áreas de convergência e divergência do fluxo superficial.

---

#### 4. Mapa de Elevação com Curvas de Nível – Município de Bragança, Pará  
![Mapa de Elevação com Curvas de Nível](terrain_analysis/Mapa%20de%20Elevação%20com%20Curvas%20de%20Nível%20–%20Município%20de%20Bragança,%20Pará.png)  
Destaca as curvas de nível para representar a variação altimétrica do terreno.

---

#### 5. Mapa de Elevação com Sombreamento – Município de Bragança, Pará  
![Mapa de Elevação com Sombreamento](terrain_analysis/Mapa%20de%20Elevação%20com%20Sombreamento%20–%20Município%20de%20Bragança,%20Pará.png)  
Combinação de elevação com sombreamento para enriquecer a visualização tridimensional do relevo.

---

#### 6. Mapa de Elevação Reclassificada por Intervalos – Município de Bragança, Pará  
![Mapa de Elevação Reclassificada por Intervalos](terrain_analysis/Mapa%20De%20Elevação%20Reclassificada%20por%20intervalos%20–%20Município%20de%20Bragança,%20Pará.png)  
Reclassificação em faixas altimétricas para simplificar a interpretação das elevações.

---

#### 7. Mapa de Índice de Umidade Topográfica – Município de Bragança, Pará  
![Mapa de Índice de Umidade Topográfica](terrain_analysis/Mapa%20de%20Índice%20de%20Umidade%20Topográfica%20–%20Município%20de%20Bragança,%20Pará.png)  
Evidencia as áreas com maior potencial de saturação do solo.

---

#### 8. Mapa de Pedologia – Município de Bragança, Pará  
![Mapa de Pedologia com Sobreposição de Elevação](terrain_analysis/Mapa%20de%20Pedologia%20com%20Sobreposição%20de%20Elevação%20–%20Município%20de%20Bragança,%20Parácópia.png)  
Combinação do mapa de pedologia com o MDE, facilitando a interpretação do comportamento do solo em função do relevo.

### Conclusões

Este projeto demonstrou a integração entre dados de elevação e ferramentas de SIG para criar representações cartográficas detalhadas do município de Bragança. Os mapas gerados possuem aplicações em planejamento ambiental, estudos hidrológicos e geomorfológicos, além de servirem como base para futuras análises de uso e ocupação do solo.

Próximos passos incluem o desenvolvimento de análises adicionais, como integração com dados socioeconômicos e estudos de impacto ambiental.

---

## Projeto 2: Classificação de Uso e Cobertura do Solo em Bragança, Pará

### Introdução

Este projeto visa apresentar a classificação de uso e cobertura do solo no município de **Bragança**, Pará, utilizando dados de satélite de alta resolução e técnicas avançadas de aprendizado de máquina. O mosaico de imagens Sentinel-2 foi obtido através do programa **Copernicus**, da **Agência Espacial Europeia (ESA)**, utilizando o **Google Earth Engine (GEE)** para a integração e manipulação dos dados. A classificação foi realizada no **QGIS**, utilizando o algoritmo **Dzetsaka** com o método **Random Forest**, que combina alta precisão com eficiência computacional.

### Objetivos

- Representar o uso e a cobertura do solo de forma clara e detalhada.
- Utilizar imagens Sentinel-2 para criar uma base confiável de dados espaciais.
- Aplicar técnicas de aprendizado de máquina para classificar as classes de uso e cobertura do solo com alta precisão.

### Metodologia

1. **Aquisição dos Dados**:
   - As imagens Sentinel-2 foram obtidas através do programa **Copernicus**, acessadas via **Google Earth Engine (GEE)**.
   - Um mosaico foi gerado cobrindo toda a extensão do município de Bragança.

2. **Classificação**:
   - A classificação foi realizada no **QGIS** utilizando o **algoritmo Dzetsaka**.
   - O método **Random Forest**, conhecido por sua robustez e capacidade de lidar com grandes volumes de dados, foi empregado para diferenciar as classes de uso e cobertura do solo.

3. **Produção Cartográfica**:
   - Mapas temáticos foram elaborados no QGIS com base no mosaico e nos dados classificados.

### Resultados

Os produtos gerados incluem:

#### 1. Mosaico de Imagens Sentinel-2 – Município de Bragança, Pará  
![Mosaico de Imagens Sentinel-2](terrain_analysis/Mosaico%20de%20Imagens%20Sentinel-2%20–%20Município%20de%20Bragança,%20Pará.png)  
O mosaico de imagens Sentinel-2 representa a base de dados utilizada para a classificação. Ele foi gerado a partir de cenas ajustadas para minimizar a presença de nuvens, garantindo alta qualidade visual e espacial.

#### 2. Mapa de Classificação de Uso e Cobertura do Solo – Município de Bragança, Pará  
![Mapa de Classificação de Uso e Cobertura do Solo](terrain_analysis/Mapa%20de%20classificação%20de%20uso%20e%20cobertura%20do%20solo.png)  
O mapa apresenta a classificação de uso e cobertura do solo, diferenciando as principais classes presentes na área de estudo. Entre as classes destacam-se:
- **Floresta**
- **Vegetação Herbácea e Arbustiva**
- **Ágropecuária**
- **Áreas Urbanas**
- **Corpos D'água**

### Conclusões

A classificação de uso e cobertura do solo em Bragança demonstra o potencial de integrar dados do **Google Earth Engine** com ferramentas de processamento como o **QGIS**. O uso do algoritmo **Dzetsaka** e do método **Random Forest** proporcionou resultados robustos e confiáveis. Este trabalho contribui para o planejamento ambiental e territorial do município, podendo ser aplicado em estudos de uso sustentável da terra e conservação ambiental.

---

## Projeto 3: Reservas Extrativistas no Litoral Paraense

Este mapa foi elaborado como parte de um estudo de doutorado do Programa de Pós-Graduação em Sustentabilidade da USP, com o objetivo de apresentar a localização e a extensão das Reservas Extrativistas (RESEX) ao longo do litoral do estado do Pará. As áreas foram delimitadas com base em dados fornecidos pelo IBGE e pelo Instituto Chico Mendes de Conservação da Biodiversidade (ICMBio).  

#### Mapa: Reservas Extrativistas no Litoral Paraense  
![Reservas Extrativistas no Litoral Paraense](Reservas%20Extrativistas%20no%20litoral%20paraense.png)

---

## Projeto 4: Mapa de Localização do PRAD da APP do Rio Velho

Este mapa foi elaborado para a **Companhia de Águas de Joinville (Águas de Joinville)**, com o objetivo de representar a localização do Plano de Recuperação de Áreas Degradadas (PRAD) na Área de Preservação Permanente (APP) do Rio Velho.  

O perímetro foi obtido a partir do georreferenciamento de um mapa histórico, utilizando o **georreferenciador do ArcGIS**. As coordenadas do PRAD foram extraídas de documentos oficiais e, posteriormente, plotadas sobre o mapa, resultando no polígono final que delimita a área do PRAD.

#### Mapa: Localização do PRAD da APP do Rio Velho  
![Mapa das propriedades - com lotes](Mapa%20das%20propriedades%20-%20com%20lotes.png)

---

Aqui está o texto consolidado para os **Projetos da DIGEO**:

---

## Projeto 5: Mapas para Relatórios Técnicos da Secretaria de Estado de Meio Ambiente e Sustentabilidade do Pará (SEMAS)

Estes mapas foram elaborados pela **Diretoria de Geotecnologias (DIGEO)** da **SEMAS** para subsidiar relatórios técnicos e análises estratégicas. Cada mapa representa uma dimensão distinta do trabalho desenvolvido pela DIGEO, envolvendo análise territorial, planejamento ambiental e atendimento ao público.

#### 1. Mapa de Análise de CAR no Estado do Pará no Ano de 2024  
![Mapa de Análise de CAR no Estado do Pará no Ano de 2024](Mapa%20de%20Análise%20de%20CAR%20no%20estado%20do%20Pará%20no%20ano%20de%202024.png)  
Este mapa apresenta a quantidade de **Cadastros Ambientais Rurais (CAR)** analisados por município no Pará em 2024, demonstrando a distribuição espacial do esforço de análise ao longo do estado.

#### 2. Atendimentos em Mutirões por Região de Integração no Pará  
![Atendimentos em Mutirões por Região de Integração](Atendimentos%20em%20mutirões%20por%20região%20de%20integração.png)  
O mapa coroplético destaca os atendimentos realizados em mutirões de regularização ambiental organizados por **região de integração** do estado. Ele evidencia as áreas com maior número de ações de atendimento e suporte.

#### 3. Mapa de Calor da Distribuição de CARs Analisados na Região de Integração do Araguaia  
![Mapa de Calor de CARs Analisados no Araguaia](ARAGUAIA%20ANALISE%20MAPA%20DE%20CALOR.png)  
Este mapa utiliza a técnica de **Estimativa de Densidade Kernel** para representar a concentração dos **CARs analisados** na **Região de Integração do Araguaia**, facilitando a identificação de áreas prioritárias para futuras ações.

---

## Projeto 6: Georreferenciamento Urbano para Desmembramento

Este projeto consiste no georreferenciamento de um lote urbano com o objetivo de desmembramento, seguindo as normas técnicas vigentes. Foram geradas três folhas em tamanho **A1**, contendo os detalhes do levantamento topográfico, como planta de situação, coordenadas UTM, azimutes e distâncias.

### Mapa principal:  
![Mapa de Georreferenciamento Urbano – Página 1](georreferenciamento/Mapa%20de%20georreferenciamento%20urgabo_page-0001.jpg)

### Demais páginas:  
- [Página 2](georreferenciamento/Mapa%20de%20georreferenciamento%20urgabo_page-0002.jpg)  
- [Página 3](georreferenciamento/Mapa%20de%20georreferenciamento%20urgabo_page-0003.jpg)

---

## Projeto 7: Levantamento Cartográfico para Projeto de Estradas Vicinais no Município de Tracuateua

Este mapa foi desenvolvido durante minha atuação na Secretaria de Planejamento do município de Tracuateua. Ele serviu como insumo técnico para a elaboração de uma proposta de recuperação de estradas vicinais, contribuindo para que o município pudesse pleitear recursos destinados à melhoria da infraestrutura viária.  

As informações cartográficas incluem a identificação das estradas a serem recuperadas, suas elevações e os perfis altimétricos dos trechos principais.

### Mapa:  
![Levantamento Cartográfico para Projeto de Estradas Vicinais](Levantamento%20cartográfico%20para%20projeto%20de%20estradas%20vicinais.png)

---

## Projeto 8: Municípios da Região Amazônica em Faixa de Fronteira

Este mapa foi elaborado como parte de um estudo do Programa de Pós-Graduação em Epidemiologia e Vigilância em Saúde do Instituto Evandro Chagas (IEC). O objetivo foi caracterizar os municípios da região amazônica brasileira que estão localizados na faixa de fronteira, destacando suas particularidades geográficas e políticas.  

### Mapa:  
![Municípios da Região Amazônica em Faixa de Fronteira](Municipios%20em%20faixa%20de%20fronteira%20na%20região%20amazônica.png)

---

## Projeto 9: Cálculo do Passivo de Reserva Legal no Estado do Pará

### Resumo do Projeto
Este projeto visa estimar o **passivo de Reserva Legal (RL)** no Estado do Pará, auxiliando na compensação e regularização ambiental conforme os requisitos do **Código Florestal (Lei nº 12.651/2012)**. A metodologia considera tipologias vegetais, remanescentes de vegetação nativa e a base do **Cadastro Ambiental Rural (CAR)**, garantindo um mapeamento preciso das áreas deficitárias. Foram utilizadas bases geoespaciais como **MapBiomas, SNIRH/ANA e SICAR**, além de processamento no **PostgreSQL/PostGIS, Python e QGIS 3.34.3**.

O projeto envolveu quatro etapas principais: (i) construção da base de tipologias vegetais, (ii) identificação do remanescente de vegetação nativa em 2008, (iii) processamento da base do CAR e (iv) cruzamento das bases para calcular o passivo de RL. A análise permitiu identificar imóveis rurais com déficits ambientais, considerando restrições como áreas protegidas e corpos d'água.

### Resultado
![Remanescente 2008 sobre Base CAR](https://github.com/nidgeo-digeo-semas/passivo_compensacao/raw/main/remanescente_2008_base_car_II.png)

### Repositório
[Confira o projeto completo no GitHub](https://github.com/nidgeo-digeo-semas/passivo_compensacao)

## Sobre Mim

Sou um profissional apaixonado por geoprocessamento, cartografia e análise espacial. Minha experiência inclui regularização ambiental, desenvolvimento de mapas temáticos e projetos de cartografia aplicada. Busco unir ciência de dados e geotecnologias para criar soluções que contribuam para o desenvolvimento sustentável.

- **LinkedIn**: [Samuel Santos](https://www.linkedin.com/in/samuelsantos-amb/)  
- **Cartão Digital**: [Samuel Santos](https://dot.cards/samuelsantos)  
- **E-mail**: samuelsantosambiental@gmail.com  
- **Portfólio de Análise de Dados**: [Explorar Portfólio](https://github.com/samuel-c-santos)
