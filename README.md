import random

def roll_dice():
  "Simula o lançamento de um dado e retorna um número aleatório entre 1 e 6."
  for i in range(1):
    roll =  random.randint(1,6)
    print(f"rolledd a {roll}")
    
roll_dice()
