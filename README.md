# APC-B_Pygame

### Jogo em Python usando a biblioteca [PyGame](https://www.pygame.org/news)

<br>

#### Como executar

Para iniciar e conseguir jogar, é necessário ter o PyGame instalado na máquina<br>

```
pip install pygame
```

<br>

É aconselhável que instale o PyGame em um ambiente virutal.<br>
Para criar um ambiente virutal basta usar este código:<br>

```
python -m venv <nome do ambiente>
```

#### Problema de som no windows

Por algum motivo a biblioteca não reproduz a música no windows caso esteja no formato MP3, ao menos no computador que eu use para testar, mas quando coloquei em formato WAV, reproduziu sem erros.<br>
Não coloquei essa mudança no código final por não ser necessário, já que ao compilar, o jogo vai ser apenas um executável, independente do formato dos arquivos, eu acho...

<br>

#### Sobre

Este jogo foi feito para um trabalho avaliativo da Universidade Federal de Alagoas [UFAL](https://ufal.br/), para a disciplina de Algorítimos e Programação de Computadores.<br>
O jogo é uma versão alternativa do popular jogo [Flappy Bird](https://pt.wikipedia.org/wiki/Flappy_Bird), porém com o tema de computadores.<br>
As músicas que são reproduzidas durante o jogo foram retiradas do site https://incompetech.com/
