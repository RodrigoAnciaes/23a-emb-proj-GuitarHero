# 23a-emb-proj-GuitarHero
 Projeto de criação de um controle para Guitar Hero utilizando sensores de contração muscular.
## Autores:
- Enzo Luidge Peixoto da Silva Bozelli
- Rodrigo Anciães Patelli
- Caio Ribeiro de Paula

Já pensou em jogar o clássico Guitar Hero, mas com os músculos da perna, do braço e do peito?
Agora você consegue! Com os sensores MYOWARE® 2.0 Muscle Sensor, você pode programá-los para funcionar como um controle, recebendo o movimento dos músculos como uma ativação para o botão.
O músculo do braço direito, por exemplo, pode ser utilizado para pressionar o botão verde, enquanto o músculo do braço esquerdo pode ser utilizado para o botão vermelho, e assim por diante. 

![MyoWare_v2_QuickStartGuide](https://user-images.githubusercontent.com/81188402/226212412-9473d7af-d993-474e-9a8d-25e1f4f86a63.jpg)

Quanto aos outputs, pode-se colocar Leds de cada cor das teclas do Guitar Hero, que são ativados conforme as teclas são pressionadas pelos músculos. 
Esse sensor já tem led imbutido nele que é aceso quando recebe input, portanto, vamos incluí-lo no projeto também, podendo ser utilizado como debug.

O sensor será ativado a partir da detecção da movimentação do músculo, que será enviado como um botão do teclado sendo pressionado, que ativará a nota no jogo Guitar Hero. Para isso, estabeleceremos um limite mínimo dessa movimentação muscular, que garantirá que o usuário quis pressionar o botão. 


https://user-images.githubusercontent.com/81188402/226213531-74d4d2d4-6e38-4e48-b2fd-17a2aa6ffd12.mp4

Vídeo retirado de Product Showcase: MyoWare 2.0 https://www.youtube.com/watch?v=d1oUHqPa35I&t=724s

![image](https://user-images.githubusercontent.com/81188402/226377592-a3384047-56d9-4231-91b4-2f8e862fe552.png)

Imagem de Guitar Hero 3, jogo para consoles e PC. Ilustra-se como serão feitos os leds de cada cor (verde,vermelho, amarelo, azul e laranja), que serão acesos ao pressionar da tecla/músculo, no tempo certo.
