# 294_ConstruindoSimuladorBatalhasLua


Construindo um Simulador de Batalhas com Lua



- CONTEÚDOS
- INFORMAÇÕES

###### DESCRIÇÃO

Crie um Simulador de Batalha no terminal, dessa vez usando múltiplos scripts em Lua como módulos, um loop lógico infinito e uma janela de ação para o usuário tomar decisões e alterar como a batalha se desenrola

**Lua**

------

###### Full-Stack

###### Intermediário

------

###### ESPECIALISTA

![author](https://hermes.dio.me/users/author/photos/acccac5a-58ce-483b-a0df-d9a3b06b28e7.jpeg)

###### Rafael Skoberg

Founder, Patosaur[**](https://www.linkedin.com/in/rafaskoberg/)



https://web.dio.me/project/construindo-um-simulador-de-batalhas-com-lua/learning/7f74b618-19a9-4176-831a-782bcb690490?back=/track/formacao-lua-developer&tab=undefined&moduleId=undefined



[**](https://web.dio.me/track/formacao-lua-developer)

##### Construindo um Simulador de Batalhas com Lua

**

[**](https://web.dio.me/lab/construindo-um-simulador-de-batalhas-com-lua/learning/7f74b618-19a9-4176-831a-782bcb690490)[**](https://web.dio.me/lab/construindo-um-simulador-de-batalhas-com-lua/learning/f35323e1-cedf-4b3f-a734-baf8b2f3154d)

<iframe id="ytc20" frameborder="0" allowfullscreen="1" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" title="Introdução ao desafio" width="100%" height="100%" src="https://www.youtube.com/embed/c3eE17LTP3A?controls=0&amp;disablekb=1&amp;enablejsapi=1&amp;fs=0&amp;iv_load_policy=3&amp;modestbranding=1&amp;showinfo=0&amp;rel=0&amp;html5=1&amp;cc_load_policy=0&amp;origin=https%3A%2F%2Fweb.dio.me&amp;widgetid=1" data-gtm-yt-inspected-19="true" style="box-sizing: inherit; max-width: none; float: none; margin: 0px; padding: 0px; border: 0px; font-style: inherit; font-variant: inherit; font-weight: inherit; font-stretch: inherit; line-height: inherit; font-family: inherit; font-optical-sizing: inherit; font-kerning: inherit; font-feature-settings: inherit; font-variation-settings: inherit; font-size: 14px; vertical-align: baseline;"></iframe>



00:31

 

09:25







normal

auto

- CONTEÚDOS
- INFORMAÇÕES

[Introdução ao desafio](https://web.dio.me/lab/construindo-um-simulador-de-batalhas-com-lua/learning/7f74b618-19a9-4176-831a-782bcb690490)[Criando um plano de projeto](https://web.dio.me/lab/construindo-um-simulador-de-batalhas-com-lua/learning/f35323e1-cedf-4b3f-a734-baf8b2f3154d)[Código esqueleto e header](https://web.dio.me/lab/construindo-um-simulador-de-batalhas-com-lua/learning/7f91ae89-4dbb-4295-b596-0c9e57da7476)[Já podemos subir o código no Github](https://web.dio.me/lab/construindo-um-simulador-de-batalhas-com-lua/learning/8c56d450-ebad-45c1-8995-18eabad49799)[Definições de criaturas](https://web.dio.me/lab/construindo-um-simulador-de-batalhas-com-lua/learning/a4ea318b-adab-4a81-a821-c516773b9c6a)[Mostrando informações de uma criatura](https://web.dio.me/lab/construindo-um-simulador-de-batalhas-com-lua/learning/2501b20d-f8a2-4b27-adad-de6a8a4df1bf)[Criando um loop infinito](https://web.dio.me/lab/construindo-um-simulador-de-batalhas-com-lua/learning/2a67a69e-8008-49cf-a3e9-a7e58d483ccc)[Refatorando nosso código para receber ações](https://web.dio.me/lab/construindo-um-simulador-de-batalhas-com-lua/learning/98589f6d-196d-4953-86f2-4c65e1951767)[Criando ações do jogador](https://web.dio.me/lab/construindo-um-simulador-de-batalhas-com-lua/learning/99a45b31-eb58-489a-a684-120778bb8262)[Executando as ações](https://web.dio.me/lab/construindo-um-simulador-de-batalhas-com-lua/learning/387c2b41-e62a-4c74-b9ac-c1781e50d4da)[Simulando o turno da criatura](https://web.dio.me/lab/construindo-um-simulador-de-batalhas-com-lua/learning/7624e8d0-bcaf-4652-993e-7cb615455d1d)[Finalizando o desafio](https://web.dio.me/lab/construindo-um-simulador-de-batalhas-com-lua/learning/cc426863-f992-464d-95d1-a9bf955bb7fa)[Reforço sobre Github](https://web.dio.me/lab/construindo-um-simulador-de-batalhas-com-lua/learning/74bc15bd-082c-494d-8ee7-cb0066b36437)[Entendendo o Desafio](https://web.dio.me/lab/construindo-um-simulador-de-batalhas-com-lua/learning/0857707e-415b-4df9-8d04-828bf72c0c23)



[**](https://web.dio.me/track/formacao-lua-developer)

##### Construindo um Simulador de Batalhas com Lua

**

[**](https://web.dio.me/lab/construindo-um-simulador-de-batalhas-com-lua/learning/74bc15bd-082c-494d-8ee7-cb0066b36437)[**](https://web.dio.me/lab/construindo-um-simulador-de-batalhas-com-lua/learning/undefined)

# Entendendo o Desafio

 

**Agora é a sua hora de brilhar e construir um perfil de destaque na DIO! Explore todos os conceitos explorados até aqui e replique (ou melhore, porque não?) este projeto prático. Para isso, crie seu próprio repositório e aumente ainda mais seu portfólio de projetos no GitHub, o qual pode fazer toda diferença em suas entrevistas técnicas** 😎

 

**Neste repositório, insira todos os links e arquivos necessários para seu projeto, seja um arquivo de banco de dados ou um link para o template no Figma.**

 

*Dica: Se o expert forneceu um repositório Github, você pode dar um "fork" no repositório dele para organizar suas alterações e evoluções mantendo uma referência direta ao código-fonte original.*

 

### **Repositório Git**

 

O Git é um conceito essencial no mercado de trabalho atualmente, por isso sempre reforçamos sua importância em nossa metodologia educacional. Por isso, todo código-fonte desenvolvido durante este conteúdo foi versionado no seguinte endereço para que você possa consultá-lo a qualquer momento:

 

[https://github.com/digitalinnovationone/trilha-lua/tree/main/Módulo%202/Simulador%20de%20Batalha](https://github.com/digitalinnovationone/trilha-lua/tree/main/Módulo 2/Simulador de Batalha)

 

 

 

 

Bons estudos 😉

- CONTEÚDOS
- INFORMAÇÕES

[Introdução ao desafio](https://web.dio.me/lab/construindo-um-simulador-de-batalhas-com-lua/learning/7f74b618-19a9-4176-831a-782bcb690490)[Criando um plano de projeto](https://web.dio.me/lab/construindo-um-simulador-de-batalhas-com-lua/learning/f35323e1-cedf-4b3f-a734-baf8b2f3154d)[Código esqueleto e header](https://web.dio.me/lab/construindo-um-simulador-de-batalhas-com-lua/learning/7f91ae89-4dbb-4295-b596-0c9e57da7476)[Já podemos subir o código no Github](https://web.dio.me/lab/construindo-um-simulador-de-batalhas-com-lua/learning/8c56d450-ebad-45c1-8995-18eabad49799)[Definições de criaturas](https://web.dio.me/lab/construindo-um-simulador-de-batalhas-com-lua/learning/a4ea318b-adab-4a81-a821-c516773b9c6a)[Mostrando informações de uma criatura](https://web.dio.me/lab/construindo-um-simulador-de-batalhas-com-lua/learning/2501b20d-f8a2-4b27-adad-de6a8a4df1bf)[Criando um loop infinito](https://web.dio.me/lab/construindo-um-simulador-de-batalhas-com-lua/learning/2a67a69e-8008-49cf-a3e9-a7e58d483ccc)[Refatorando nosso código para receber ações](https://web.dio.me/lab/construindo-um-simulador-de-batalhas-com-lua/learning/98589f6d-196d-4953-86f2-4c65e1951767)[Criando ações do jogador](https://web.dio.me/lab/construindo-um-simulador-de-batalhas-com-lua/learning/99a45b31-eb58-489a-a684-120778bb8262)[Executando as ações](https://web.dio.me/lab/construindo-um-simulador-de-batalhas-com-lua/learning/387c2b41-e62a-4c74-b9ac-c1781e50d4da)[Simulando o turno da criatura](https://web.dio.me/lab/construindo-um-simulador-de-batalhas-com-lua/learning/7624e8d0-bcaf-4652-993e-7cb615455d1d)[Finalizando o desafio](https://web.dio.me/lab/construindo-um-simulador-de-batalhas-com-lua/learning/cc426863-f992-464d-95d1-a9bf955bb7fa)[Reforço sobre Github](https://web.dio.me/lab/construindo-um-simulador-de-batalhas-com-lua/learning/74bc15bd-082c-494d-8ee7-cb0066b36437)[Entendendo o Desafio](https://web.dio.me/lab/construindo-um-simulador-de-batalhas-com-lua/learning/0857707e-415b-4df9-8d04-828bf72c0c23)

