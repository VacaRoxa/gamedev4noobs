
 
# UnrealEngine4Noobs
 
<img src="https://i.imgur.com/hDTZYUP.png" alt="Unreal Engine">
 
 
## Objetivo
<p align="left">
O objetivo dessa página é mostrar caminhos para aprender Unreal Engine (UE). Seja para jogos, visualização arquitetônica (Archviz), ou cinema/tv. 
</p>
 
### Introdução
<p align="left">
Unreal Engine (UE) começou com uma ferramenta de desenvolvimento de jogos e com o passar do tempo e avanço da tecnologia da mesma, passou a ser utilizada em outras midias, como Filmes, Arquitetura, Transmissões ao Vivo, Automóveis, Simulações e Treinamento.</p> 
<p>
UE é completamente gratuita para uso pessoal e para uso comercial você paga 5% dos royalties apenas se o seu produto atingir 1 milhão de dolares em receita bruta. Apesar de ser uma engine profissional, seu uso foi simplificado e suas ferramentas são bem acessíveis e fáceis de compreender. Não importa se você é uma pessoa sem experiência alguma, ou se está vindo com experiência de outra engine, a adaptação a Unreal Engine é bem descomplicada.
</p>
Ela é usada em inúmeros jogos e estúdios triplo-A como a Capcom, Nintendo, Square Enix, Xbox Game Studio, Sega e WB Games. Além disso, a <a href="https://insights.stackoverflow.com/survey/2019#technology-_-most-loved-dreaded-and-wanted-other-frameworks-libraries-and-tools">pesquisa de desenvolvedores de 2019 do Stack Overflow</a>. mostra que a engine está entre as 10 habilidades mais requisitadas no mercado de trabalho. 

Alguns dos jogos feitos com a Unreal incluem Final Fantasy 7 Remake, Fortnite, Gears 5, Yoshi's Crafted World e Crash Bandicoot 4.
 
[![State of Unreal Highlights](https://i.imgur.com/tQoYm4Y.png)](https://youtu.be/We1N-7M_hM4)

<br>

### Usando Unreal Engine
<p align="left">
<img src="https://i.imgur.com/BfE2cQj.png">
<br>
<br>

#### Unreal4Noobs
<a href="Unreal/intalando_unreal.md">Instalando a Unreal</a> <br>
<a href="Unreal/primeiro_projeto.md">Criando o primeiro Projeto</a> <br>
<a href="">Se familiarizando com a Unreal</a>

#### Material de Apoio 
<a href="https://docs.unrealengine.com/4.26/en-US/Basics/" target="_blank">Documentação Oficial com Informações básicas de introdução a UE</a><br> 
<a href="https://docs.unrealengine.com/4.26/en-US/BuildingWorlds/" target="_blank">Informações sobre as ferramentas e técnicas para criar um ambiente interativo e design de níveis</a><br> 
<a href="" target="_blank">Unreal Engine 4 Essentials - Uma Introdução Detalhada</a> <br> 
<a href="https://www.unrealengine.com/en-US/onlinelearning-courses" target="_blank">Site oficial com cursos variados sobre UE</a><br> 
<a href="https://docs.unrealengine.com/4.26/en-US/Basics/UnrealEngineForUnityDevs/" target="_blank">Unreal Engine para desenvolvedores Unity</a><br> 

 
### Programando na Unreal Engine
A Unreal Engine dá 2 opções para programar seu jogo: Blueprints e C++. Cada uma dessas opções tem vantagens e desvantagens.
 
**Blueprint:** é muito mais rápido prototipar e programar. É uma linguagem mais visual com acesso a quase toda a API da UE. Você programa usando nodes num gráfico. Caso sua Blueprint fique enorme com muitos cálculos, além de ficar um pouco dificil entender o código, é provavél que você perca um pouco de performance (ultimamente isso é debatível pois você pode usar <a href="https://docs.unrealengine.com/4.26/en-US/ProgrammingAndScripting/Blueprints/TechnicalGuide/NativizingBlueprints/" target="_blank"> Nativization</a>). 
 
**C++:** você tem mais controle sobre o código e menos problemas com performance (ainda assim, depende do seu código), porém é um pouco complicada para iniciantes e leva um tempo a mais compilando o código do seu projeto.
<br>
<br>
**Devo usar Blueprint ou C++?**<br>
**R:** Use os dois. Blueprint e C++ funcionam muito bem usando em conjunto. 
<br>
<br>
<img src="https://i.imgur.com/45TSEfy.png" alt="Alex Forsythe BPs vs C++">
<br>
<br>
A imagem acima mostra a mesma lógica em C++ e Blueprints. É um Actor no mapa que no inicio do jogo cria um outro Actor no mesmo local e executa uma função/evento que existe dentro desse Actor. Parecem ser coisas bem diferentes mas a lógica inserida e o resultado é exatamente a mesma coisa. Você pode entender mais sobre as diferenças <a href="http://awforsythe.com/unreal/blueprints_vs_cpp/" target="_blank">nesse link</a>. No mais, não fique preso apenas a uma delas, use o que você se sentir mais a vontade. Vários jogos já foram lançados em várias plataformas utilizando apenas blueprints ou c++.
 
#### Unreal4Noobs

#### Material de Apoio
<a href="https://docs.unrealengine.com/4.26/en-US/ProgrammingAndScripting/" target="_blank">Programando e Scriptando (Documentação Oficial em Ingles)</a><br>
<a href="https://romeroblueprints.blogspot.com/p/sumario.html" target="_blank">Introdução a C++ e Blueprints</a><br> 
<a href="https://www.udemy.com/share/101sVWAkEad1tSQHg=/" target="_blank">Unreal Engine 4 Blueprints (Legendado em Portugues) (PAGO)</a><br>
<a href="https://www.udemy.com/share/101XsEAkEad1tSQHg=/" target="_blank">UE 4 Multiplayer com C++ (Ingles)</a><br> 
<a href="https://www.udemy.com/share/1024WaAkEad1tSQHg=/" target="_blank">UE Blueprint Game Developer (Ingles)</a><br> 
<a href="https://www.udemy.com/course/logica-de-programacao-para-todos/" target="_blank">Lógica de programação para todos</a><br>
<a href="https://docs.unrealengine.com/4.26/en-US/BlueprintAPI/" target="_blank">Unreal Engine BP API </a><br>
<a href="https://docs.unrealengine.com/4.26/en-US/API/" target="_blank">Unreal Engine C++ API</a><br>
 
### Projetos para Aprendizado
 
| Nome | Descrição |  Link | 
| ------ | ------ | ------ | 
| Aba Learn do Launcher | Vários Projetos para expandir e aprender usando Unreal Engine | <a href="https://launcher-website-prod07.ol.epicgames.com/ue/learn" target="_blank">LINK</a> | 
| Unreal Engine Resources | Elhoussine Mehnik juntou vários recursos e exemplos prontos para serem usados em qualquer projeto.  | <a href="https://unrealengineresources.com/projects" target="_blank">LINK</a> | 
| Tom Looman | Site com vários tutoriais e links para exemplos no github | <a href="https://www.tomlooman.com/" target="_blank">LINK</a> | 
 
 
 
### Assets e Conteúdo Gratuito
Todo mês a Epic disponibiliza alguns assets de graça. 
Alguns são disponíveis por apenas um mês, portanto não esqueça de pegar eles para ativar na sua conta.
 
| Nome | Descrição |  Link | 
| ------ | ------ | ------ | 
| Assets Gratuitos do Mes | Trocam sempre na primeira terça feira do mes | <a href="https://www.unrealengine.com/marketplace/en-US/assets?count=100&sortBy=effectiveDate&sortDir=DESC&start=0&tag=4910" target="_blank">LINK</a> | 
| Epic Content | Conteúdo da própria Epic, só pode ser usado na Unreal Engine | <a href="https://www.unrealengine.com/marketplace/en-US/profile/Epic+Games?count=100&sortBy=effectiveDate&sortDir=DESC&start=0" target="_blank">LINK</a> | 
| Marketplace Collection | Coleção de assets gratuitos que ja foram usados em jogos lançados anteriormente | <a href="https://www.unrealengine.com/marketplace/en-US/assets?count=100&sortBy=effectiveDate&sortDir=DESC&start=0&tag=13960" target="_blank">LINK</a> | 
| Free | Todo conteúdo gratuito disponível no marketplace | <a href="https://www.unrealengine.com/marketplace/en-US/free?count=100&sortBy=effectiveDate&sortDir=DESC&start=0" target="_blank">LINK</a> | 
| Plugins Gratuitos | Plugins gratuitos para sempre que ajudam a expandir as funcionalidades da Unreal Engine. Funcionam em projetos que utilizam somente Blueprints | <a href="https://www.unrealengine.com/marketplace/en-US/content-cat/assets/codeplugins?count=100&priceRange=%5B0%2C0%5D&sortBy=effectiveDate&sortDir=ASC&start=0" target="_blank">LINK</a> | 
 
 
### Canais para Aprendizado
 
| Nome | Descrição |  Link | 
| ------ | ------ | ------ | 
| Mathew Wadstein Tutorials (Ingles) | Mathew ensina usar varias partes da Unreal Engine em videos curtos e objetivos. | <a href="https://www.youtube.com/c/MathewWadsteinTutorials/videos" target="_blank">LINK</a> | 
| Unreal Engine Youtube (Ingles) | Contém as novidades da Unreal Engine e transmissões ao vivo armazenadas | <a href="https://www.youtube.com/c/UnrealEngine/videos" target="_blank">LINK</a> | 
| CodeLikeMe | Tutoriais recriando funcionalidades de outros jogos | <a href="https://www.youtube.com/c/CodeLikeMe/videos" target="_blank">LINK</a> | 
| Virtus DevSquad (Ingles) | Videos Tutoriais ao vivo de programação  | <a href="https://www.youtube.com/user/VirtusEdu/videos" target="_blank">LINK</a> | 
| Twitch Unreal Engine | Canal oficial da Unreal Engine com lives todas semanas sobre UE | <a href="https://www.twitch.tv/unrealengine" target="_blank">LINK</a> | 
| Unreal Slackers | Discord Oficial da Unreal Engine |  <a href="https://discord.gg/unreal-slackers" target="_blank">LINK</a> | 
 
<br>
<a href="https://br.indeed.com/empregos?q=unreal%20engine&chnl=6545_UnrealEngine4" target="_blank">EMPREGOS NO BRASIL PARA DESENVOLVEDORES NA UNREAL ENGINE</a>
<br>
<br>
 
<p align="left">
   Feito com <img height="16" src="https://i.imgur.com/Hcqxxhx.gif">
</p>