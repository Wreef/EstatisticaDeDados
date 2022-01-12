![logo](https://i.ibb.co/YthtbLh/Giifff-mid.gif)
***
# Introdução ao Google Colaboratory
Neste guia iremos conhecer e acessar uma ferramenta para desenvolvimento de código Python em núvem. O Google Colaboratory.

Nesse ambiente é possível programar seus códigos sem fazer uso do desempenho do seu computador. Para utilizar essa ferramenta é necessário ter uma conta Google.

## Acessando o Google Colaboratory
Inicialmente pesquise "Google Colaboratory" no Google. Acesse o link da imagem abaixo:

<p align="center">
  <img src="https://i.ibb.co/PzpvrWr/collab1.png" alt="1"/>
</p>

Em seguida clique em "Novo notebook".

<p align="center">
  <img src="https://i.ibb.co/fFrFZYc/collab2.png" alt="1"/>
</p>

Pronto! Esse é o Google Colaboratory.

<p align="center">
  <img src="https://i.ibb.co/3CX1H9t/collab3.png" alt="1"/>
</p>

Agora iremos conhecer algumas funcionalidades dele.

## Abrindo Arquivo de Dados
Para baixar o arquivo de dados [Clique Aqui](https://github.com/Wreef/EstatisticaDeDados/raw/main/Introdu%C3%A7%C3%A3o%20ao%20Google%20Colaboratory/dados.csv).

Clique com o botão direito do mouse na tela e selecione "Salvar como". Escolha uma paste e clique em "Salvar".

<p align="center">
  <img src="https://i.ibb.co/pxb6y87/collab4.png" alt="1"/>
</p>

No Google Colaboratory clique no ícone de pasta da imagem a seguir:

<p align="center">
  <img src="https://i.ibb.co/V350Y2Y/collab5.png" alt="1"/>
</p>

Arraste o arquivo dados.csv para a nova área que foi aberta. Clique em "Ok" na janela que irá aparecer.

<p align="center">
  <img src="https://i.ibb.co/Sc7xbsx/collab6.png" alt="1"/>
</p>

Após o upload digite "import pandas as pd" no campo (célula) que foi criado quando você abriu o Google Colaboratory.

Após escrever aperte no botão "play" que fica do lado esquerdo do texto.

<p align="center">
  <img src="https://i.ibb.co/cYCmcwr/collab7.png" alt="1"/>
</p>

Esse código irá carregar a biblioteca Pandas. Essa bilioteca é utilizada para trabalhar com dados.

Para mais detalhes: https://pandas.pydata.org/

Clique em "+ Texto" para acrescentar uma célula de texto.

<p align="center">
  <img src="https://i.ibb.co/pw2PppX/collab8.png" alt="1"/>
</p>

> Nesse tipo de célula você pode digitar qualquer informação. Como a célula é somente de texto, seu código não será afetado.

Clique em "+ Código" para acrescentar uma célula de código.

<p align="center">
  <img src="https://i.ibb.co/KXDPL5R/collab9.png" alt="1"/>
</p>

Na célula de código digite:

```cpp
df = pd.read_csv('dados.csv')
df
```

Ao rodar o código, seus dados estarão carregados e aparecerá uma breve visualização deles. Na saída do código serão exibidas as 5 primeiras e as 5 últimas linhas da planilha.

<p align="center">
  <img src="https://i.ibb.co/2vP0G60/collab10.png" alt="1"/>
</p>

> Vale lembrar que seu arquivo de dados irá sumir após fechar o Google Colaboratory. Caso não queira ficar realizando upload sempre que for programar, coloque seus arquivos no Google Drive.

## Conclusão
Pronto! Agora é só programar!

Esse guia exibiu somente o básico do Google Colaboratory. Os próximos guias serão focados em Estatística e aplicados no Google Colaboratory.
Até mais!
