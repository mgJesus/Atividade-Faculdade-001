# Atividade Faculdade 001
 Criei um programa que calcula o desconto da renda 
 
 #rnd é a variavel que utilizei para guardar o valor da renda.
rnd = float(input('Qual a sua renda : R$ '))

#aqui e onde realiza os calculos para que possa saber o valor descontado da renda.

#Na linha 7 eu quis dizer que se o valor incial for de 0 até 2.000, o programa ira dizer que não será descontado do valor da renda.
if rnd >= 0 and rnd <= 2000.00:
    print('você está livre de imposto!')

#Na linha 11 quis que o programa pegasse o valor entre 2000 à 3000 e descontasse 8% do valor da renda.
elif rnd >= 2000.00 and rnd <= 3000.00:
    print('será descontado 8% da sua renda que ficará :', rnd-(rnd*8/100))

#Na linha 15 pedi que o programa pegasse o valor entre 3000 à 4500 e descontasse 18% do valor da renda.
elif rnd >= 3000.00 and rnd <= 4500.00:
    print('será descontado 18% da sua renda que ficará :', rnd-(rnd*18/100))
#Por fim na linha 18 pedi para que o programa pegasse qualquer falor acima de 4500 e descontasse 24% do valor da renda.
else:
    print('será descontado 24% da sua renda que ficará :',rnd-(rnd*24/100))

