# Especificação Suplementar 

## 1. Introdução
&emsp;&emsp;A especificação suplementar descreve os requisitos não-funcionais que não foram englobados nos outros artefatos que especificam requisitos, como nos casos de uso.
É possível capturar com essa técnica:

- Requisitos legais e de regulamentação e padrões de aplicativo
- Atributos de qualidade do sistema a ser criado, incluindo requisitos de usabilidade, confiabilidade, desempenho e suportabilidade
- Outros requisitos, como aqueles para os sistemas e ambientes operacionais, compatibilidade com outro software e restrições de design
 

&emsp;&emsp;Pode-se entender, por tanto, cenários como situações de interações entre usuários ou agentes externos com o sistema em desenvolvimento, e possívelmente suas interações com sistemas semelhantes. Essas interações consistem em atividades reais e concretas que o usuário possívelmente buscaria completar no sistema, e por fornecerem essa visão do usuário, podem facilitar o processo de descoberta de novos requisitos, ou de desconsideração de requisitos já elicitados, com base nas necessidades e dificuldades identificadas durante o fluxo do usuário pelo sistema.


## 2. FURPS+

&emsp;&emsp;O FURPS+ é um modelo em que cada letra significa uma categoria de requisitos:

- Funcionality
- Usability
- Reliability
- Performance 
- Suportability

## 2.1 F - Funcionality - Funcionalidade

&emsp;&emsp;Representa todo aspecto funcional do software, ou seja, seus requisitos. É uma categoria com diversas subcategorias que variam de acordo com a aplicação. Sua medição considera, principalmente, o cumprimento dos requisitos especificados.

## 2.2 U - Usability - Usabilidade

&emsp;&emsp;É o atributo que avalia a interface com o usuário. Possui diversas subcategorias, entre elas:

- Prevenção de erros.
- Ajudas.
- Consistência.
- Padrões.
- Documentação.

## 2.3 R - Reliability - Confiabilidade

&emsp;&emsp;São requisitos relacionados à integridade e interoperabilidade (comunicação com outros sistemas) do software. Exemplos:

- Frequência de falhas.
- Possibilidade de recuperação.
- Duração da falha.
- Estabilidade.


## 2.4 P - Performance - Performance

&emsp;&emsp;São requisitos relacionados ao desempenho do software. Exemplos:

- Tempo de resposta.
- Consumo de recursos.
- Escalabilidade.
- Disponibilidade.

## 2.5 S - Suportability - Suportabilidade

&emsp;&emsp;São requisitos relacionados a capacidade de suporte do software, tanto para consigo mesmo, quanto para o usuário. Exemplos:

- Testabilidade.
- Adaptabilidade.
- Manutenibilidade.
- Compatibilidade.
- Instalabilidade.
- Portabilidade.

## 2.6 +

&emsp;&emsp;Com a evolução do FURPS, foram encontradas algumas outras categorias para requisitos de software, tais como:

- Design: restringem o design de um sistema. Exemplos: padrões de design, processo de desenvolvimento de software, uso de ferramentas de desenvolvimento etc.
- Implementação: restringem a construção/código do software. Exemplos: linguagens de programação, políticas de integridade do banco de dados, ambientes operacionais etc.

## 3. Especificação Suplementar
|   ID  |             Requisito                                                     |Classificação|
|-------|---------------------------------------------------------------------------|---|
|B03	|O usuário deve ser capaz de compartilhar os melhores momentos da partida	|U|
|B04	|O usuário deve ser capaz de avaliar os melhores momentos da partida	|U|
|B05	|O usuário deve ser capaz de compartilhar o video de melhores momentos da partida na sua TV	|U|
|B19	|O usuário deve ser capaz de visualizar o horário de jogo de cada seleção dependendo do seu pais de origem	|U|
|B22	|O usuário deve ser capaz de escolher seleção favorita a ganhar a copa	|U|
|B23	|O usuário deve ser capaz de escolher seleção favorita a ganhar o jogo	|U|
|B24	|O usuário deve ser capaz de escolher o saldo de gols de cada jogo	|U|
|B25	|O usuário deve ser capaz de escolher a estrela da partida	|U|
|B26	|O usuário deve ser capaz acumular pontos com palpites do jogos	|U|
|B27	|O usuário deve ser capaz de cadastrar email	|U|
|B28	|O usuário deve ser capaz de cadastrar senha	|U|
|B29	|Deve ser possível reenviar e-mail de validação	|U|
|B30	|O usuário deve ser capaz alterar email	|U|
|B31	|O usuário deve ser capaz alterar senha	|U|
|B32	|O usuário deve ser capaz de inserir Login	|U|
|B33	|O usuário deve ser capaz de inserir uma senha	|U|
|OB01	|O usuário deve ser capaz de buscar pelo jogo	|U|
|OB02	|O usuário deve poder trocar o idioma do app	|S|
|OB03	|O usuário deve ser capaz de transmitir a tela	|+|
|OB04	|O usuário deve poder escolher a qualidade do vídeo	|P|
|OB05	|O usuário deve poder usar a opção de tela cheia	|U|
|OB06	|O usuário deve ser capaz de ver os jogadores do time	|U|
|OB07	|O usuário deve ser capaz de ver o calendario dos jogos	|U|
|OB08	|O usuário deve ser capaz de ver onde o jogo será transmitido	|U|
|OB09	|O usuário pode ver informações da conta	|U|
|OB10	|O usuário pode escolher bloquear assitir via dados de celular	|S|

## 4. Histórico de versão

|    Data    | Versão |                     Descrição                     |        Autor(es)        | Revisor(es) |
| :--------: | :----: | :-----------------------------------------------: | :---------------------: | :---------: |
| 30/11/2022 |  1.0   | Adicionado o resultado do FURPS+                  | Rafael Fernandes        |  Raphaela Guimarães|