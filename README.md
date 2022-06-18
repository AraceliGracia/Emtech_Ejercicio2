# Emtech_Ejercicio2

municipio1= input ("Dime un municipio ")
Num_habitantes1= input ("Cuantos habitantes tiene ")

municipio2= input ("Dime un municipio ")
Num_habitantes2= input ("Cuantos habitantes tiene ")

municipio3= input ("Dime un municipio ")
Num_habitantes3= input ("Cuantos habitantes tiene ")

Lista_municipios =[municipio1,municipio2,municipio3]
Num_habitantes=[int(Num_habitantes1),int(Num_habitantes2),int(Num_habitantes3)]

Total_habitantes= sum(Num_habitantes)
Prom_habitantes= float(Total_habitantes)/3

print("El numero total de habitantes es:"+str(Total_habitantes))
print("El promedio de habitantes es:"+str(Prom_habitantes))






