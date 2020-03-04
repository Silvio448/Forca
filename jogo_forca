# Forca
Jogo da forca com python
palavra_secreta = ["M","O","R","C","E","G","O"]
letras_descobertas = []

print('\n*** Jogo da Forca ***\n')

for i in range(0,len(palavra_secreta)):
    letras_descobertas.append('-')

acertou = False

while acertou == False :
    print('-=' * 15)
    letra = str(input('Digite a letra: '))
    print('-=' * 15)

    for i in range(0, len(palavra_secreta)):
        if letra == palavra_secreta[i] :
            letras_descobertas[i] = letra

        print(letras_descobertas[i]) 

    acertou = True

    for x in range(0, len(letras_descobertas)) :
        if letras_descobertas[x] == '-' :
            acertou = False       

