# exercicio-22-
Exercício Python 22: Crie um programa que leia o nome completo de uma pessoa e mostre:  – O nome com todas as letras maiúsculas e minúsculas.  – Quantas letras ao todo (sem considerar espaços).  – Quantas letras tem o primeiro nome.
exercicio22.py
nome = str (input ()).strip()

print('nome tem {}'.format(nome.upper()))
print('tem isso ai {} '.format(nome.lower()))

print ((len(nome) - nome.count(' ')))
separado =nome.split()
print('seu primeiro nome {} tem {}'.format(separado[0],(len(separado [0]))))  
