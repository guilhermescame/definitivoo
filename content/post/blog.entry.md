---
title: "Blog Entries"
date: 2020-06-10
image: "blog2.png"
---

# Blog Entry 

## Processo de criação do blog - Blog entry 1.
* Passo a passo sobre os passos dados na criação do nosso portfólio.

### Hugo
* Inicialmente tentamos outras plataformas até chegar ao Hugo, começamos com o Next.js porém não deu muitos frutos e acabamos tentando outra plataforma que no caso foi a Jekyll que usa a linguagem Ruby que também não estava dando frutos, ai acabamos ouvindo de alguns colegas de classe sobre o Hugo, inicialmente ficamos um pouco confusos no final conseguimos, foi bem divertido trabalhar com ele no inicio por conta da variedades de temas e a variedade de coisas que se dava pra fazer, digamos era até sugestivo de mais.

### Compra de dominio
* O dominio utilizado foi o 1124r23.site, escolhemos este baseado principalmente no preço. Fizemos a ativação do dominio usando o Amazon SES, onde recebemos uma chave CNAME e adicionamos no conjunto de DNS do nosso dominio, para que ele pudesse ser verificado com sucesso. Como foi nossa primeira vez mexendo com este tipo de serviço ficamos bem perdidos, ao ponto de não sabermos nada do que estavamos fazendo, mas no final deu tudo certo.

### Serviços utilizados para o hosting do blog na nuvem.

 * Primeiro tentamos com o AWS amplify, onde diversas vezes fizemos o upload do site de diversas formas diferentes, usando vários repositórios e metodos diferentes, mas sem nenhum resultado. Mesmo mostrando que a build tinha sido um sucesso e colocando o dominio junto da build, o blog sempre dava o mesmo erro, "ERR_TOO_MANY_REDIRECTS". Imaginamos que o erro fosse algo relacionado ao sistema de redirect index do AWS Amplify, então partimos para a utilização do AWS EC2, onde criamos um servidor em ubuntu e utilizamos do PuTTY para acessá-lo com a chave nos dada pela AWS. O resultado foram mais erros, e como o prazo chegava ao fim, resolvemos apenas rodar o servidor localmente até encontrarmos uma solução e um host funcional.

 ### Conclusão
 * No fim, o projeto foi bem interessante e produtivo, mesmo não alcançando um sucesso definito e muitos erros, aprendemos muito sobre novas linguagens, como o Gatsby, Hugo, Next.js e etc. Também aprendemos muito sobre SSH e sua utilização, enquanto tentávamos resolver todos os erros.