import proj_fuzz
from proj_fuzz import *

import matplotlib.pyplot as matpl


valor_pontuacao = int(input("Qual a sua pomtuação atual? "))

valor_tempo = int(input("Qual o seu tempo de jogo em minutos? "))


dif = passar_valores(mostrar, valor_pontuacao, valor_tempo)

pontuacao.view()
tempo.view()
dificuldade.view()


print(f"A dificuldade atual da fase é : {dif} ")

matpl.show()
