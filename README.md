# portifa-comunity

## Após muitas pessoas me procurar querendo saber como fazer portifólio decidi fazer esse com um tutorial de como mudar cada parte e ao mesmo tempo vpcê aprender um pouco mais sobre html e css.

<a href="https://eliasgabriel1.github.io/portifa-comunity/"> ESSE PORTFÓLIO</a>
### Primeiro gostaria de pedir pra dar aquela estrelinha se ajudar em algo eu vou continuar fazendo esse tipo de conteúdo (da mo trabalho)

<h2>Como foi algo feito para iniciantes, vou mostrar desde o inicio</h2>

<h3>!!! ATENÇÃO É NECESSARIO TER INSTALADO O GIT !!!</h3>
<a href="https://git-scm.com/book/pt-br/v2/Come%C3%A7ando-Instalando-o-Git">CLIQUE AQUI PARA SABER COMO INSTALAR O GIT</a>
<h3>!!! USAREMOS VISUAL STUDIO CODE !!! </h3>
<a href="https://code.visualstudio.com/">CLIQUE AQUI SE NÃO USA VS CODE E GOSTARIA DE INSTALAR</a>
<p>para pegar esse arquivo é simples, vamos clonar ele, se você ja sabe como clonar e ja clonou, pula essa parte</p>
<p>sobe a página até projeto e vá até o botãozinho "code"</p>

![image](https://user-images.githubusercontent.com/50595684/137573470-9b4df528-5df2-496a-90f5-a523f33c6140.png)

<p>Vamos clonar por HTTPS, então clica no HTTPS e em "Clonar com HTTPS"</p>

![image](https://user-images.githubusercontent.com/50595684/137573475-e94f42e5-2564-4f09-95ad-f48c95467732.png)

![image](https://user-images.githubusercontent.com/50595684/137573486-fa5a1da4-d781-4358-877f-0d607ca5e711.png)

<p>agora vamos clonar pra ter o arquivo na sua máquina, vá ate o cmd(terminal) </p>
<P>Deixe ele aberto e abre as pastas e procure a pasta que tu quer deixar o arquivo clonado </P>
<p>escreva "cd" no cmd e arraste a pasta até o cmd(terminal)</p>
<p>clique no enter, e digite "git clone https://github.com/EliasGabriel1/portifa-comunity.git" e aperte enter</p>
<p>logo terminar o clone, digite "portifa-comunity"</p>
<p> e logo digite "code ."para abrir o projeto no vs code </p>

## E aqui encerra o tutorial de clone

# A árvore do projeto foi divida em 

![image](https://user-images.githubusercontent.com/50595684/137573458-e8f8ddd1-722e-406b-a899-77c2dbf27c45.png)


Sendo assim O primeiro arquivo a alterar é o index.html

![image](https://user-images.githubusercontent.com/50595684/137573547-90dca47d-858e-417a-a923-c76feba74fbe.png)


Eu tirei um tempo e comentei tudo que fiz, cada parte está comentada, iniciando então, a primeira coisa a mudar é a tag title dentro do head,
mude para seu nome, portifólio - seu nome, ou qualquer coisa que você goste, esse title iráaparecer em cima da aba do projeto, assim: 
![image](https://user-images.githubusercontent.com/50595684/137573962-db11f5f7-6038-42a1-bdde-0d16a866b5ec.png)

dentro do head possui também uma tag assim:

<link rel="shortcut icon" type="image/x-icon" href="./../content/img/favicon.ico">

## Ela representa a imagem que aparece do lado do titulo da pagina do seu site 

![image](https://user-images.githubusercontent.com/50595684/137574130-4d95f660-7912-431a-b99e-f717c06ed3cb.png)

Sendo assim, pegue sua imagem que deseja por la em cima, e transforme em um favicon, pelo site <a href="http://www.favicon.pro/pt/"> http://www.favicon.pro/pt/</a>
troque no caminho content>img o favicon para aparecer o seu, lembrese de trocar, e por com o mesmo nome que esta na tag falado acima
<br>
<br>
logo explicando como fora feito o menu mobile e o desktop foi comentado no código, são dois, pois um é do mobile e outro do desktop

Logo após fazer todo processo de mudança pras suas coisas, nome, profissão e a frase de impacto, é hora de trocar a imagem coloque uma imagem de preferencia no tamanho de 500x500 no diretorio content>img 

Mude os projetos em destaque, e os posts principais do blog, coloque os principais que voce fez, mesmo sendo muito simples, coloque uma imagem de destaque e um pequeno texto e o ano

Em sequencia dos trabalhos principais, sempre fora imagem portifólio 1 a 4 e cada um sucessivamente com seu texto

![image](https://user-images.githubusercontent.com/50595684/137573765-c9013340-783d-4f11-b919-b71c7d271cf8.png)

Ao clicar na imagem voce vai ser direcionado ao trabalho 1, aonde é o que o href esta falando, logo dentro da tag <figure>, possui o src da imagem, mude o nome da imagem colocada em content>img, de acordo com o tipo, png, ou jpg, ex <img src="./content/img/projeto1.png" alt="">o
  
  Próxima página é pages>works.html
  
  os works funcionam da mesma maneira citada anteriormente, cada imagem que esta do lado de um texto no projeto 
  
  ![image](https://user-images.githubusercontent.com/50595684/137573861-2072fd33-6449-4a99-aadb-6698652e6bd8.png)
  
  no codigo esta embaixo, seguindo sequencia, a imagem do 1ºprojeto  é correspondente a primeira tag de img do codigo
  ![image](https://user-images.githubusercontent.com/50595684/137573881-71d6d6b9-fc16-46c4-b3f0-70b08b9b4ef1.png)

## !!! TODO O PROJETO, EXISTE MOMENTOS REPETIDOS, COMO O NOME DO TITLE É NECESSÁRIO TROCAR EM TODAS PÁGINAS SE O PROJETO MUDAR DE NOME !!!
  
Como falado o blog funciona da mesma maneira, cada href tem um caminho até o projeto desse blog ou work, logo irei falar mais sobre, mas altere conforme sua necessidade, apague ou comente se a quantidade de postagens for maior do que voce quer ter, para comentar basta apertar 'crtl k c' sucessivamente.
  
  E a ultiam parte contém a página de contato, aonde é a mais simples, dentro da section possui o nome, email e github, altere conforme o seu.
  
  e nas públicações, cada vez que existir uma nova postagem, faça um novo documento html, e coloque no href da pagina de postagem dentro do pages>blog se for blog e pages>work se for de trabalho, dessa maneira:
  
  ![image](https://user-images.githubusercontent.com/50595684/137574035-2cd14968-0c21-4463-8acd-a5f0b3f46a1d.png)
  
  ![image](https://user-images.githubusercontent.com/50595684/137574051-0c7c5ef3-20c7-4718-b049-ba42a11bcb8f.png)

  cada arquivo corresponde a um href, mude as imagens de acordo com o que preferir, coloque o ano da postagem e um titulo bem interessante 😉😉
  
  e por ultimo, se isso foi minimament util, compartilhe com alguém que ta começando e quer ter um portifólio simples e descente, me siga aqui no github <3
  se faltou algo, bora trocar uma ideia no instagram: <a href="https://www.instagram.com/eliasgahh/">Elias Gabriel <a>

