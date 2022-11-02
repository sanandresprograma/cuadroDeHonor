estudiante1 = {'cédula':'00014301503', 'nombre': 'Pepito', 'nota_fundamentos': 4.3}
estudiante2 = {'cédula': '1037678471', 'nombre': 'Fulanito', 'nota_fundamentos': 3.2}
estudiante3 = {'cédula': '71023567', 'nombre': 'Pancho', 'nota_fundamentos': 5}
estudiante4 = {'cédula': '32276123', 'nombre': 'Rita', 'nota_fundamentos': 4.7}
estudiante5 = {'cédula': '1036765245', 'nombre': 'Anita', 'nota_fundamentos': 4.3}
estudiante6 = {'cédula': '89122456', 'nombre': 'Pedrito', 'nota_fundamentos': 4.5}
estudiante7 = {'cédula': '289765345', 'nombre': 'Mat', 'nota_fundamentos': 4.8}
estudiante8 = {'cédula': '4576890', 'nombre': 'Dan', 'nota_fundamentos': 4.8}


grupo = [estudiante1, estudiante2, estudiante3, estudiante4, estudiante5, estudiante6, estudiante7, estudiante8]

suma_notas = []
for k in grupo:
  suma_notas.append((k['nota_fundamentos']))
  promedio = (sum((suma_notas)) / len(grupo))

grupo_2 = []
grupo_3 = []

for h in grupo:
  grupo_2.append((h['nota_fundamentos'],h['cédula']))
  grupo_2.sort(reverse=True)
  if h ['nota_fundamentos']:
    notas_grupo=(h['nota_fundamentos'])
    grupo_3.append(notas_grupo)
    grupo_3=list(set(grupo_3))
    grupo_3.sort(reverse=True)

puesto_1=((grupo_3[0]))
puesto_2=((grupo_3[1]))
puesto_3=((grupo_3[2]))

cuadro_honor={}
puesto_A=[]
puesto_B=[]
puesto_C=[]

for item1 in grupo_3:
  for item2 in grupo_2:
    if item1 == item2[0] and item2[0]==puesto_1:
      puesto_A.append(item2[1])
    if item1 == item2[0] and item2[0]==puesto_2:
      puesto_B.append(item2[1])
    if item1 == item2[0] and item2[0]==puesto_3:
      puesto_C.append(item2[1])


cuadro_honor={1:puesto_A,2:puesto_B,3:puesto_C}
promedio = round(promedio,1)
print('El promedio de las notas es: ',promedio,'  Acontinución el documento de los 3 primeros puestos',cuadro_honor)
