| [Home](https://techlipe.github.io/Guia-Completo-Elastic-Stack) | [Documentação](https://techlipe.github.io/Guia-Completo-Elastic-Stack/guia-completo) | [Videos](https://techlipe.github.io/Guia-Completo-Elastic-Stack/rasgando-o-bit-com-elastic) | 

![TL](banner-tl.png)

# Workshop Elastic -  O Caminho para se tornar Elastic Certified (Dia 3) - Elasticsearch
* **Criado por:** Felipe Queiroz <br>
* **Última atualização:** 16.12.2020

![banner](workshop-cert-dia03.jpg)

# Utilidades!

[Video do dia](https://www.youtube.com/watch?v=Ynn9YEDPeks)

[Download da Planilha de apoio](https://github.com/techlipe/Guia-Completo-Elastic-Stack/raw/master/Cronograma%20de%20Certifica%C3%A7%C3%A3o%20-%20Certified%20Engineer.xlsx)

# Conteudo

## Elasticsearch - E.D/Text vs Keyword/Mapping/Dynamic/Templates

**Como funciona o padrão de estrutura de dados do Elasticsearch?**
Por padrão, o usuário normalmente não deve se preocupar em criar uma estrutura de dados para suportar o seu indice. Isso se dá pelo fato de que o Elasticsearch trabalha como ferramenta _Schema-Free_.

Isso ocorre por alguns fatores, dentre eles o fato de que o Elasticsearch utiliza de mapeamento dinâmico para realizar os mapeamentos dos indices de maneira automática.

O ponto é, deixar o Elasticsearch mapear automaticamente é uma boa prática pra produção?
