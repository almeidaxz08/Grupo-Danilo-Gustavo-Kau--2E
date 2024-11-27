# Grupo-Danilo-Gustavo-Kau--2E
guardinha = int(input("De uma nota de 0 a 10 para guardinha: "))
ronda = int(input("De uma nota de 0 a 10 para a ronda: ")) 
dp = int(input("De uma nota de 0 a 10 para a dp: "))
base = int(input("De uma nota de 0 a 10 para a base militar: ")) 
seguranca = int(input("De uma nota de 0 a 10 para segurança: "))
cameras = int(input("De uma nota de 0 a 10 para câmeras: "))


soma = guardinha + ronda + dp + base + seguranca + cameras


if soma <= 30:
    print("Seu bairro é péssimo")
elif soma <= 40:
    print("Seu bairro é mediano")
elif soma <= 60:
    print("Seu bairro é ótimo")
else:
    print("Seu bairro tem uma excelente segurança")


p1 = input("Você tem a inteligência IoT em sua rua? (s/n): ").strip().lower()
Iot = input("Gostaria de obter a inteligência IoT? (s/n): ").strip().lower()


if p1 == "s" and Iot == "s":
    print("Ok, instalaremos a inteligência IoT em sua rua.")
elif p1 == "n" or Iot == "n":
    print("Obrigado pelo feedback.")
else:
    print("Resposta inválida. Por favor, responda com 's' ou 'n'.")


