# PDI-Consumindo-Dados-IBGE


O objetivo desta transformação é realizar o consumo de dados que são fornecidos pela API do IBGE. O link se encontra <a href="https://servicodados.ibge.gov.br/api/docs/localidades" target="_blank">aqui</a>.

Ao observar a página, podem ser visualizados diversos conjuntos de dados em seu sumário tais como Distritos, Mesorregiões, Microrregiões, Municípios, Países, Regiões, dentre outros. Neste exemplo o consumo será realizado buscando os Distritos por UF. Na imagem abaixo, tem-se um detalhamento de como é o funcionamento da chamada para este conjunto de dados.


![Screenshot](imgs/Screenshot_1.png)

Observa-se que na imagem acima, os dados podem ser retornados utilizando um ID que representa a UF, porém, nos testes e implementação realizada, o funcionamento é o mesmo ao informar a sigla da UF desejada, como por exemplo "MG". Vale observar ainda, que se utilizado o caracter "|" (pipe) é possível obter o retorno dos dados de mais de uma UF na mesma chamada. 

Por fim, abaixo, tem-se um exemplo de como o array é retornado. 

![Screenshot](imgs/Screenshot_2.png)

