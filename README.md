#Respostas em Python

p4.30 - 

  num = 1
  for num in range(1,51):
	  print(num)
	  num = num + 1
	  
p4.31 - 

  num = 2
  while (num<=100):
  	print(num)
	  num = num + 2
	  
p4.32 - 

  num = 10
  while (num <= 1000):
	  print(num)
	  num = num + 10
	  
p4.33 - 

  num = 100
  while (num != 1):
	   print(num)
	  num = num-1
  print(num)

p4.34 - 

  N = int(input("Informe um número: "))
  num = 1
  soma = 0
  while (num <= N):
	  soma = soma + num
	  num = num + 1
	  continue
  print("A soma dos números é igual a: ", soma)
