# Escala de três níveis

## 1. Definição

O método conhecido originalmente como Three-Level Scale(TLS), consiste em agrupar os requisitos em uma escala de urgência e de importância da funcionalidade no sistema, de acordo com as necessidades do usuário, e de acordo com os objetivos de negócio do sistema a ser desenvolvido. 

## 2. Metodologia

A aplicação do método baseia-se em estimar prioridades relativas para um grupo de requisitos em uma escala de níveis de prioridade. No caso do FIFA+ o método aplicado utilizou a escala composta por:

- Alta Prioridade: Requisitos que tem alta importância no sistema e consequentemente agregam muito valor para o cliente, e paralelamente possuem uma alta urgência para o cliente.
- Prioridade Média: Requisitos cuja presença no sistema tem alta importância para o cliente, mas que possuem baixa urgência de serem implementados.
- Baixa Prioridade: Requisitos que possuem baixa importância e baixa urgência para o cliente. Podem ser requisitos necessários para o sistema, porém que podem esperar para serem desenvolvidos.
- Sem Prioridade (Não faça esses): Esses requisitos são um ponto de atenção, já que distoam do natural em relação à priorização. Faz pouco sentido que um requisito que não tenha importância para que o sistema atinja seus objetivos de negócio, tenha alta urgência. Nesses casos, provavelmente a urgência foi atribuida por motivações externas ou pessoais de determinados stakeholders. Dessa forma, o ideal é não gastar tempo desenvolvendo essas funcionalidades, pois não agregam valor suficiente ao produto de software. 

O método foi aplicado utilizando a ferramenta Miro, e os resultados podem ser observados no (Quadro 1).


## 3. Participantes

- Eric Chagas
- Rafael Fernandes

## 4. Resultados
A aplicação do TLS resultou nas sequências de requisitos que podem ser visualizadas por meio do miro no (Quadro 1):

(É possível visualizar o quadro miro em tela cheia clicando no ícone de fullscreen no canto inferior direito do quadro)

<iframe width="768" height="432" src="https://miro.com/app/live-embed/uXjVP-a_3ck=/?moveToViewport=-15069,-4479,23161,12080&embedId=256509459112" frameborder="0" scrolling="no" allowfullscreen></iframe>

###### Quadro 1 - Método aplicado no miro. Fonte: Autoria própria.

Os requisitos funcionais e não funcionais podem ser visualizados em ordem decrescente de prioridade, na (Tabela 1) e na (Tabela 2):

## 4.1 Requisitos Funcionais
| Número | Requisitos Funcionais                                         |
| ------ | ------------------------------------------------------------- |
| RF1    | O usuário deve ser capaz de transmitir a tela                 |
| RF2    | O usuário deve ser capaz de ver o calendario dos jogos        |
| RF3    | O usuário deve ser capaz de ver onde o jogo será transmitido  |
| RF4    | O usuário deve poder usar a opção de tela cheia               |
| RF5    | O usuário pode ver informações da conta                       |
| RF6    | O usuário deve ser capaz de ver os jogadores do time          |
| RF7    | O usuário deve ser capaz de buscar pelo jogo                  |
| RF8    | O usuário deve poder escolher a qualidade do vídeo            |
| RF9    | O usuário deve poder trocar o idioma do app                   |
| RF10   | O usuário pode escolher bloquear assitir via dados de celular |

###### Tabela 1: Requisitos Funcionais priorizados pelo TLS. Fonte: Autoria própria.


### 4.2 Requisitos Não Funcionais

| Número | Requisitos Não Funcionais                                                                                                |
| ------ | ------------------------------------------------------------------------------------------------------------------------ |
| RNF1   | O sistema deve possuir uma boa conexão com o servidor                                                                    |
| RNF2   | A pessoa física usuária do aplicativo deve conseguir obter informações e acompanhar o resultado dos jogos em tempo real. |
| RNF3   | A pessoa física usuária do aplicativo deve conseguir obter notícias sobre seus jogadores favoritos.                      |
| RNF4   | A pessoa física usuária do aplicativo deve conseguir obter informações sobre o calendário de jogos                       |
| RNF5   | O sistema deve possuir uma aba de melhores momentos                                                                      |

###### Tabela 2: Requisitos não Funcionais priorizados pelo TLS. Fonte: Autoria própria.



## 5. Referência bibliográfica

> Wiegers, K. E., & Beatty, J. (2013). Software Requirements 3 (3o ed). Microsoft Press.

## 6. Histórico de versão

|    Data    | Versão |                          Descrição                           |  Autor(es)  | Revisor(es) |
| :--------: | :----: | :----------------------------------------------------------: | :---------: | :---------: |
| 30/11/2022 |  1.0   | Criado e adicionado conteúdo da página e aplicação do método | Eric chagas |   Wengel    |