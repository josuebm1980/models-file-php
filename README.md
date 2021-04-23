# 

<h1>Modelo básico de organização de arquivos em PHP | Páginas dinamicas em PHP </h1>


<p align="center">
  <a href="#por que?">Por Que?</a>&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;
  <a href="#design-memo">O arquivo de configuração</a>&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;
  <a href="#sobre-memo">Tag Head Content</a>&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;
  <a href="#tecnologias-rocket">Include de arquivos design e conteúdos</a>&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;
  <a href="#para-contribuir-">Para Contribuir</a>&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;
  <a href="#licença-scroll">Licença</a>&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;
</p>


## Apresentação do Projeto :sparkles:

Modelo de estrutura em PHP para modularizar diferentes partes de um site. Com isso, se tem um arquivo separado para a “navegação” para o “rodapé” e outras partes do site. 

---
## Por Que?

Isso facilita e simplifica inclusão de arquivos em seu código.

## O arquivo de configuração:memo:

O arquivo de configuração detecta em qual página você está e define algumas variáveis que posteriormente exibirão esse conteúdo. Se você estiver usando um banco de dados, a string de conexão também aparecerá aqui.

## Tag Head Content :memo:

Isso permite que cada página tenha seu próprio título exclusivo (conforme definido no arquivo de configuração).
Na página “índice” (também definida por uma das variáveis no arquivo de configuração), eu mostro as tags META. Nas páginas não iniciais, não mostro isso.

## Include de arquivos design e conteúdos :computer:

**parte superior do design**

Apenas um cabeçalho geral. Freqüentemente, a navegação será incluída neste arquivo, no entanto, para fins de demonstração, separei-a em dois arquivos.

**Navegação**

No código PHP está incluindo dinamicamente uma classe adicional em cada link, de forma que dependendo da página em que você estiver, esse link será destacado (indicando que está “ativo”).

**Rodapé**

Há um código lá para exibir dinamicamente o ano atual (para que você não precise alterá-lo manualmente todos os anos!).



## Tecnologias :rocket:

**PHP*

**HTML5** 

**CSS3**

## Para contribuir 🤔

- Faça um fork desse repositório;
- Cria uma branch com a sua feature: `git checkout -b minha-feature`;
- Faça commit das suas alterações: `git commit -m 'feat: Minha nova feature'`;
- Faça push para a sua branch: `git push origin minha-feature`.

## Licença :scroll:

> Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

##### Feito por Josué Moraes :wave:



