# programa-media-aritmetica
bim1 = int(input("nota bimenstre 1: "))
bim2 = int(input("nota bimenstre 2: "))
bim3= int(input("nota bimenstre 3: "))
bim4 = int(input("nota bimenstre 4: "))

media = int(bim1+bim2+bim3+bim4)/4
print ("sua media foi:",media)

if media >=9:
    print("aprovado com louor")
elif media >=7:
    print ("aprovado")
elif media <7:
    print("reprovado")
