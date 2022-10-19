# **INSTALAÇÃO DA TECNOLOGIA 5G NA AMÉRICA DO SUL**

<p align="justify">
  <img src="https://www.ambientelegal.com.br/wp-content/uploads/torre-e1626049808941.jpeg" width="600px"/>
</p>


## **Considerações**

O presente trabalho foi desenvolvido como Projeto Integrador para conclusão do curso de Data Analytics da Digital House. Utilizamos o nome BR CONSULT para uma consultoria fictícia, que fornece soluções por meio de análise de dados, ao cliente Huawei (também fictício).  

<br> 

## **Problema de Negócio**

Mediante o crescente avanço tecnológico, o cliente Huawei gostaria de instalar uma nova filial em algum País. Para isso, solicitou o serviço da BR CONSULT, consultoria especializada em Dados, para orientá-lo sobre qual País melhor atenderia a expectativa de instalação de sua nova fábrica. 
<br> A Huawei é uma empresa que se preocupa com a Agenda 2030 da ONU, a qual é um plano global para atingirmos um mundo melhor para todos os povos e nações. Portanto, para análise, devem ser considerados dados que possam contribuir com os diversos pilares da agenda.

<br> 

## **Objetivos**

Identificar países da américa do sul, a fim de implantar uma filial de empresa de tecnologia (Huawei);
<br> Sugerir países que melhor se adequem aos parâmetros solicitados pela empresa Hauwei para implantação da
tecnologia 5G;

<br> 

## **Squad de Atendimento**

Foi criado uma Squad especializada para atendimento ao cliente.


</br>
<p align="justify">
  <img src="https://raw.githubusercontent.com/dslsvo/pi_data_analytics_dh/main/squad.PNG" width="700px"/>
</p>


</br>

## **Arquitetura**

O pipeline para o desenvolvimento de todo o projeto está resumido na fiugura abaixo.

- **Fase de Coleta**: foram coletados diversos dados que possuíam informações relevantes dos pilares da Agenda 2030 da ONU, em diversas fontes. As bases estão disponíveis no atual repositório.
- **Fase de Armazenamento**: utilizamos o Heroku para criar uma interface compartilhada em que todos pudessem subir os arquivos pesquisados.
- **Fase de Tratamento**: o tratamento dos dados foi realizado no Alteryx, com um fluxo para junção das bases, e tratamento dos dados, a fim de criar uma base que pudesse ser devidamente relacionada ao Power BI, e também, disponibilizar uma base para ser utilizada no Python para análise estatística e de modelagem.
- **Fase de Modelagem**: aqui foi utilizado o Python para realizar análises estatísticas descritivas e também realizar modelagem dos dados (Regressão), pára identificar as melhores variáveis para análise gráfica (afinal, eram muitas, mais de 30), e também direcionar futuras oportunidades preditivas.
- **Fase de Análise**: utilizamos o Power BI, com as devidas DAX, para gerar análises e insights gráficos dos dados, criar o Dashboard do material e direcionar nosso cliente a uma conclusão final.
- **Fase de Visualização**: Enfim, por meio da ferramenta Power BI e Power Point, criamos uma apresentação "Visão Negócio" para seguir com o storytelling e apresentação dos resultados do projeto.


</br>
<p align="justify">
  <img src="https://raw.githubusercontent.com/dslsvo/pi_data_analytics_dh/main/Arquitetura.PNG" width="700px"/>
</p>

</br>
</br>



## **Análise Estatística e das Variáveis**

Abaixo, segue um breve resumo da análise estatística e de modelagem realizada. Caso seja necessário a análise dos códigos, o arquivo/ notebook python "Modelo Final-Vencedor.ipynb" está disponível neste repositório. 
</br>
- Fora realizada a EDA das variáveis, encontrada a correlação dos dados com a target "Índice de Inovação", e a partir disso foram testados três modelos de regressão: Linear Regresison, Ridge Regression e SGD Regressio.
- Dentre os modelos análisados, e as métricas consideradas (R² e RMSE) o modelo vencedor foi o Ridge Regression, apresentando RMSE = 1.1 e R² = 0,80.
- Além disso, foi verificado a importância das variáveis por meio de um gráfico SHAP, o que direcionou nossas análises iniciais no Power BI dentre as tantas variáveis disponíveis para análise.

</br>
<p align="justify">
  <img src="https://raw.githubusercontent.com/dslsvo/pi_data_analytics_dh/main/estatistica.PNG" width="700px"/>
</p>

</br>
</br>


## **Análises Gráficas e Dashboard**

As análises gráficas e dashboards podem ser verificadas utilizando os arquivos do Power BI e PDF disponíveis no repositório



## **Principais Conclusões**

Abaixo, seguem as principais conclusões obtidas através dos dados analisados.

- Recomedação de País Para instalação da nova filial: **CHILE**

- Melhor índice de Inovação (36,42%)

- Melhor infraestrutura de transportes (4,2 pontos)

- Terceiro maior investimento externo (12,74% do PIB)

- Segundo melhor PIB per capta (U$ 75k); 


</br>
<p align="justify">
  <img src="https://raw.githubusercontent.com/dslsvo/pi_data_analytics_dh/main/conclusoes.PNG" width="700px"/>
</p>


## **Links de fontes que auxiliaram no desenvolvimento deste Projeto** 

- [UN DATA](https://data.un.org/)
- [THE GLOBAL ECONOMY](https://www.theglobaleconomy.com/)
- [UNITED NATIONS](https://www.unodc.org/)
- [EL PAIS](https://elpais.com/america/)
- [INFO MONEY](https://www.infomoney.com.br/)
- [BMNAMERICAS](https://www.bnamericas.com/)
- [LABS - Latin America Business Stories](https://labsnews.com/en/)
- [SOMOS IBEROAMERICA](https://www.somosiberoamerica.org/)
- [apexBRASIL](https://apexbrasil.com.br/)


## **Agradecimento** ❤
Aqui ficam meu sinceros agradecimentos a toda a equipe (já mostrada na squad) que auxiliou no desenvolvimento do projeto.
