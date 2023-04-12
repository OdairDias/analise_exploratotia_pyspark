# Análise_exploratotia_pyspark
Objetivo deste projeto foi demonstrar uma aplicação pratica de pyspark para análise de dados.
Estamos utilizando um dataSet com os dados de roubos de celulares no estado de SP ocorridos no mês de fevereiro de 2023

## Análise: 

Os dados abaixo nos trazem algumas informações relevantes sobre o roubo de celulares no estado de São Paulo ocorridos em janeiro deste ano, vamos a análise: 

**Primeiro**: Os crimes acontecem preferencialmente a noite e menos de madrugada. 

**Segundo**: A cidade com mais registros de crimes é São Paulo seguida por São Bernado do campo.

**Terceiro**: o bairro mais violento é o da República seguido pelo centro. 

**Quarto**: a rua onde mais roubaram celular no perdido analisado foi na rodovia regis bittencourt seguida pela rodovia presidente dutra. 

**Quinto**: as marcas de celulares mais roubadas foram Samsung, Motorola e Apple.

E por **último**, em 98% dos roubos foram levados apenas um aparelho sedo dois aparelhos responsável por 2% das ocorrências. 

Abaixo seguem os dados utilizados para análise:

**Primeiro passo importamos os dados e já solicitamos uma visualização dos dados importados:**

![image](https://user-images.githubusercontent.com/117185803/231448267-d45dc34e-fd4b-4cb2-b61a-17d4ace17918.png)


**Em seguida iremos observar quais colunas temos e o tipo de dado em cada coluna:**

![image](https://user-images.githubusercontent.com/117185803/231448796-c2ba4b4f-74b3-4ebc-9f88-f3bb8928c759.png)

**Agora iremos montar um novo df com alguns dados considerados relevantes para esta análise:**
![image](https://user-images.githubusercontent.com/117185803/231449225-45aa529b-938b-4e53-8a4d-63f35a736cb5.png)

**Também devemos olhar a integridade dos nossos dados, descobrir quantas celular vazias ou nulas nós temos:**

![image](https://user-images.githubusercontent.com/117185803/231451687-701929cc-326f-4611-91f3-40500ce2174a.png)


**A Seguir seguem os dados usados para análise:**

![image](https://user-images.githubusercontent.com/117185803/231450593-f9f95471-ec68-4e5c-9180-68f5bb8b9203.png)

![image](https://user-images.githubusercontent.com/117185803/231450821-ed1187eb-336c-4346-915b-174ac0ff31f7.png)

![image](https://user-images.githubusercontent.com/117185803/231450923-7c00ef67-dd05-470a-b8d8-bcd437df6ad4.png)

![image](https://user-images.githubusercontent.com/117185803/231451060-05b6dd0f-a878-4d6c-834f-40d62f48cf98.png)

![image](https://user-images.githubusercontent.com/117185803/231451137-53b941bf-4992-4539-967b-8c35002a6b3e.png)

![image](https://user-images.githubusercontent.com/117185803/231451263-b8b73b2f-2a82-4565-8ac5-559c3e915590.png)


O notebook com os códigos e metodologia utilizados seguem neste repositório. 

