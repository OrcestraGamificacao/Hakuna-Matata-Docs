# Documento de Visão

|  Autor | Descrição | Data | Versão |
|--|--|--|--|
| [Gabriel Sabanai](https://github.com/Sabanai104) | Tópicos 1.1, 1.3, 1.6  | 29/03/2021| 0.1 |
| [Natan Santana](https://github.com/Neitan2001) | Tópico 4.1, 4.2  | 31/03/2021| 0.2 |
| [Natan Santana](https://github.com/Neitan2001) | Tópico 5.1, 5.2, 5.3, 5.4, 5.5, 5.6, 5.7, 5.8  | 31/03/2021| 0.3 |
| [Gabriel Sabanai](https://github.com/Sabanai104) | Tópicos 1.2, 1.4, 1.5, 2.1, 2.2, 2.3   | 01/03/2021| 0.4 |
| [Gabriel Sabanai](https://github.com/Sabanai104) | Tópicos 3.1, 3.2, 3.3, 3.4   | 02/03/2021| 0.5 |
| [Gabriel Sabanai](https://github.com/Sabanai104) | Tópicos 3.5, 3.6   | 01/03/2021| 0.4 |

## 1 _ Introdução

### 1.1 Finalidade 

Este documento tem como objetivo esclarecer e documentar as características e aplicações do desenvolvimento do projeto Hakuna Matata (nome em desenvolvimento).

### 1.2 Escopo 

O estudo online já se tornou a realidade em tempos de pandemia e com o decorrer do ultimo ano, a quantidade de plataformas de ensino a distância teve um grande aumento. Entretanto, o EAD vem se mostrando um desafio tanto para professores, por alguns demonstrarem dificuldade em se adaptar, tanto para os alunos, que possuem dificuldade em se concentrar por meio de video aulas.

Dessa forma, é preciso inovar e explorar técnicas e tecnologias com própositos diferentes. É em meio a essa crise que entra o projeto Hakuna Matata(nome em desenvolvimento), uma plataforma de ensino, gamificada e gratuita para todos, idealizada por Gino Terentim, desenvolvida pela Orc'estra Gamificação e ilustrada pela Lamparina Designs.

Gino teve a ideia da plataforma atráves de seu contato e estudo com a gamificação, além de utilizar plataformas de ensinos gamificados, como o Octalysis Prime. Dessa forma, percebeu que com ela poderia oferecer uma forma de ensino interativa, engajadora e única para todos.

O escopo do Hakuna Matata(nome em desenvolvimento) se encontra um software que atua como uma plataforma web gamificada, que traz elementos de narrativa, evolução, interação, compras e, principalmente, conhecimento progressivo. Assim, o usuário se cadastra e acessá a mesma para aprender diversos conteúdos passados por Gino Terentim.

### 1.3 Não Escopo

O *software* previsto não tem a finalidade de se tornar uma plataforma de video generica ou uma plataforma de download de video aulas.

Além disso, diferentemente de outras plataformas parecidas, o *software* não é uma plataforma de video aulas sem a presença de nenhum elemento de gamificação, também não é uma plataforma que só pode ser acessada com uma assinatura e não é direcionada apenas para um público em especifico. 

Por fim, a plataforma não é qualquer tipo de jogo ou simulação.

### 1.4 Definições, Acrônimos e Abreviações

* Hakuna Matata (Nome em desenvolvimento): Produto a ser criado para solucionar a temática anteriormente referenciada;
* Software: Sequência de instruções escritas para serem interpretadas por um computador com o objetivo de executar tarefas específicas;
* Gamificação: Técnica de design que busca utilizar elementos e atributos presentes em jogos e aplica-las em áreas do trabalho ou em tarefas do dia-a-dia;
* EAD: Ensino a distância.
### 1.5 Refências
* [https://insights.liga.ventures/edtechs/ferramentas-de-ensino-baseadas-em-jogos-e-gamificacao/](https://insights.liga.ventures/edtechs/ferramentas-de-ensino-baseadas-em-jogos-e-gamificacao/);

* [https://porvir.org/8-plataformas-adaptativas-voce-precisa-conhecer/](https://porvir.org/8-plataformas-adaptativas-voce-precisa-conhecer/);

* [https://www.terra.com.br/noticias/dino/durante-a-quarentena-aumenta-o-numero-de-buscas-por-cursos-em-formato-ead,e4e11a6c5fc5b5f3e1d0b435ffbf006dsx21lq9x.html](https://www.terra.com.br/noticias/dino/durante-a-quarentena-aumenta-o-numero-de-buscas-por-cursos-em-formato-ead,e4e11a6c5fc5b5f3e1d0b435ffbf006dsx21lq9x.html);

* [https://www.gazetadopovo.com.br/educacao/ensino-superior-ead-ganha-impulso-na-pandemia-mas-inadimplencia-tambem-aumenta/](https://www.gazetadopovo.com.br/educacao/ensino-superior-ead-ganha-impulso-na-pandemia-mas-inadimplencia-tambem-aumenta/);

* [https://ginoterentim.com/](https://ginoterentim.com/);

* [https://www12.senado.leg.br/radio/1/noticia/2020/10/26/ensino-a-distancia-ganha-preferencia-dos-calouros-em-2019#:~:text=Segundo%20o%20Censo%20da%20Educa%C3%A7%C3%A3o,Dez%20anos%20depois%20s%C3%A3o%2043%25..](https://www12.senado.leg.br/radio/1/noticia/2020/10/26/ensino-a-distancia-ganha-preferencia-dos-calouros-em-2019#:~:text=Segundo%20o%20Censo%20da%20Educa%C3%A7%C3%A3o,Dez%20anos%20depois%20s%C3%A3o%2043%25..).

### 1.6 Visão Geral

Este documento tem como visão fazer a documentação descritiva dos fundamentos, organização e desenvolvimento do Hakuna Matata, bem como contextos levados a sua criação. Dessa maneira representa a oportunidade de negócio com a problematica em questão, incluindo uma visão macro dos requisitos e funcionalidades ciradas e utilizadas pelo mesmo, a fim, de cumprir seu papel.

## 2 _ Posicionamento

### 2.1 Oportunidade de Negócios

A tendência do EAD é grande, afinal, de acordo com os ultimos dados da Google, houve um aumento de 130% nas buscas por especialização a distância. Além disso, dados mostram que, mesmo após o fim da pandêmia, a busca pelo ensino a distância vai contninuar crescendo, já que, mesmo em um período pré Covid-19 foi levantado um censo pelo Inep, o qual, em 2009 16% dos estudantes que ingressaram no ensino superior optaram pelo ensino a distância e 10 anos depois, em 2019, esse valor cresceu para 43%.

Assim sendo, várias plataformas de ensino online estão chegando. Porém, poucas optam por utilizar designs únicos como a gamificação, que vem se mostrando grande aliada em atrair e engajar úsuarios, como afirma um censo da Talent LMS o qual quase 80% das pessoas dizem que seriam mais produtivas se sua universidade ou empresa fosse mais game-like.

Dessa forma, pode-se acreditar que, em meio a essa crise, investir em uma plataforma de ensino a distância gamificada é um investimento promissor.

### 2.2 Descrição do Problema

|                       |                                                                                                                                                                                                |
| --------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| O problema         | Necessidade de uma plataforma de ensino gamificada.                                                                                                     |
| Quem afeta                | Usuários que buscam aprender.                                                                                                                                                                  |
| Impacto        | Usuários menos engajados e ativos com o EAD e empresas com imagem ruim.                                                                                              |
| Solução | Criação de uma aplicação web gamificada que visa passar contéudos de forma dinâmica, interativa e mais divertida. |

### 2.3 Sentença de Posição do Produto

|                   |                                                                                                                    |
| ----------------- | ------------------------------------------------------------------------------------------------------------------ |
| Para              | Comunidade do Gino Terentim e futuros alunos.                                                                                   |
| Cujo              | Problema se encontra na demora e burocracia na de resolução de problemas.                                           |
| O Hakuna Matata (nome em desenvolvimento) | Problema se encontra na vontade em criar uma plataforma de ensino web gamificada.                                                     |
| Que               | Visa aumentar o engajamento, o retorno e o conhecimento do usuário durante seu momento de aprendizagem. |

## 3 _ Descrição dos Envolvidos e dos Usuários

### 3.1 Resumo dos Envolvidos

|  Nome | Descrição | Responsabilidades |
|--|--|--|
| Time de desenvolvimento | Equipe de membros da Orc'estra Gamificação, Empresa Júnior de Engenharia de Software da UnB | Responsáveis por desenvolver a aplicação web |
| Gino Terentim | Idealizador da ideia e presidente da PMI DF | Responsável pela criação dos materiais e conteúdos disponiveis na plataforma  |
| Time de ilustrações | Equipe de membros da Lamparina Design, Empresa Júnior de Desenho Industrial da UnB  | Responsáveis pelas ilustrações da aplicação web |

### 3.2 Resumo dos Usuários

|  Nome | Descrição | Responsabilidades |
|--|--|--|
| Usuários interessados em gerenciamento de projetos | Pessoas que desejam aprender sobre gerenciamento de projetos, utilizando uma plataforma gamificada | Responsáveis por utilizar o sistema para aprender sobre gerenciamento de projeto por meio de uma experiência interativa, dinâmica e progressiva |


### 3.3 Ambiente do Usuário

A aplicação web poderá ser utilizada por qualquer pessoa por meio de um navegador web presente no computador de cada usuário. A interação do usuário com a plataforma se dará unica e exclusivamente por meio de um navegador.


### 3.4 Perfis dos Envolvidos

#### 3.4.1 Equipe de desenvolvimento 


|                      |                                                                                                                                                                                                                                                                        |
| -------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Representantes       | [Gabriel Sabanai](https://github.com/Sabanai104) <br> [Natan Tavares](https://github.com/Neitan2001) <br> [Arthur Matos](https://github.com/Arthur-Matos) |
| Descrição            | Equipe responsável pelo desenvolvimento da aplicação web.                                                                                                                                                                                                                   |
| Tipo                 | Membros da Orc'estra Gamificação                                                                                                                                      |
| Responsabilidades    | Desenvolver                                                                                                                                                                                                                                                            |
| Critérios de Sucesso | Entregar a aplicação, com os requisitos atendidos, dentro do prazo estabelecido.                                                                                                                                                                                |
| Envolvimento         | Alto      

#### 3.4.2 Equipe de Ilustração

|                      |                                                                                                                                                                                                                                                                        |
| -------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Representantes       | Luma Lima <br> A declarar <br> A declarar |
| Descrição            | Equipe responsável pelo criação das ilustrações.                                                                                                                                                                                                                  |
| Tipo                 | Membros da Lamparina Design                                                                                                                                      |
| Responsabilidades    | Ilustrar                                                                                                                                                                                                                                                            |
| Critérios de Sucesso | Entregar as ilustrações, dentro do prazo estabelecido.                                                                                                                                                                                |
| Envolvimento         | Alto      

### 3.5 Principais Necessidades da Parte Interessada e do Usuário

#### 3.5.1 Parte Interessada

| Necessidade                                                                                | Prioridade                                                   | Solução atual                                                                                                                                                                                                | Soluções propostas                                                                                                                                 |
| ------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| Uma ferramenta de ensino que auxilie no engajamento e interesse dos usuários em gerenciamento de projeto. | Promover engajamento. | Cursos onlines | Plataforma online gamificada com módulos sobre gerenciamento de projetos. |

#### 3.5.2 Usuário

| Necessidade                                                                                | Prioridade                                                   | Solução atual                                                                                                                                                                                                | Soluções propostas                                                                                                                                 |
| ------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| Aprender gerenciamento de projeto de uma forma menos monotona e cotidiana | Engajar usuários a usar e a se manter na plataforma. | Cursos onlines | Plataforma online gamificada com módulos sobre gerenciamento de projetos. |

### 3.6 Alternativas e concorrẽncia

Se formos levar em consideração apenas as plataformas de ensino gamificada, existem algumas alternativas no Brasil, como a [*Geekie Games*](https://geekiegames.geekie.com.br/) e, fora do Brasil, existe a [*Octalysis Prime*](https://island.octalysisprime.com/#/). Entretanto, ainda não se tem conhecimento de nenhuma plataforma online gamificada focado em ensinar gerenciamento de projeto. Dessa forma, a única alternativa disponivel, atualmente, é por meio de cursos em plataformas de videos como o Youtube e o Coursera.

## 4 _ Visão geral do produto

### 4.1 Perspectiva do produto

Esse produto tem como objetivo democatrizar o acesso à edução relacionada a temas de Gerenciamento de Projetos de uma forma Gamificada, contendo uma narrativa que irá motivar o usuário a estudar os conteúdos da plataforma. Os usuários serão recompensados com pontos de status e moedas à medida que progridem, podendo testar o conhecimento adquirido realizando "quizzes". Por fim, o conteúdo terá acesso grátis, contudo para adquirir os certificados é necessário realizar uma assinatura.

### 4.2 Resumo dos recursos

|  Benefício para o cliente | Recursos de suporte | 
|--|--|--|--|
| Acesso gratuito a conteudos de Gerenciamento de Projetos | O usuário poderá assistir vídeos e responder "quizzes" de todos os cursos da plataforma gratuitamente  |
| Acompanhamento do progresso e evolução | O usuário poderá acompanhar o seu progresso e evolução por meio dos pontos de status que recebe ao ver vídeos e acertar as perguntas dos "quizzes". Além de receber insígnias das trilhas que foram completas  |
| Narrativa interativa | O usuário poderá interagir com a narrativa da plataforma, conhecendo personagens que irão ajudá-lo a progredir  |
| Loja de conteúdos extras | O usuário poderá ganhar moedas ao completar atividades da plataforma para poder desbloquear conteúdos extras  |
| Assinatura da plataforma | O usuário poderá assinar a plataforma para adiquirir os certificados dos cursos que tiver completado  |

## 5 _ Recursos do produto

### 5.1 Acesso

O usuário deve ser capaz de acessar a plataforma através de autenticação por login.

### 5.2 Cadastro

O usuário deve ser capaz de realizar o cadastro através da própria aplicação.

### 5.3 Narrativa

O usuário deve ser capaz de interagir com a narrativa à medida que navega pela plataforma.

### 5.4 Mapa Inicial

O usuário deve ser capaz de vizualizar o mapa inicial e acessar as outras páginas da plataforma por ele.

### 5.5 Trilhas de Conteúdo

O usuário deve ser capaz de vizualizar e acessar as trilhas de conteúdo pelo mapa principal, podendo ver os vídeos e responder "quizzes" e desafios.

### 5.6 Pontos de Status, Moedas

O usuário deve ganhar pontos de status e moedas ao ver vídeos, responder "quizzes e passar por desafios.

### 5.7 Insígnias

O usuário deve ser capaz de ganhar pontos de status e moedas ao ver vídeos, responder "quizzes e passar por desafios. 

### 5.8 Assinatura

O usuário deve ser capaz de realizar uma assinatura para receber os certificados dos cursos que concluir.

### 5.9 Perfil de Usuário
O usuário deve ser capaz de acessar o próprio perfil para vizualizar e editar as informações pessoais, além de vizualizar pontos de status, moedas, insígnias e certificados.


