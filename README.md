# Tarea-3-Mec-nica-Estad-sitca-Ising-Model
#Contenido

- `ising_metropolis.py`: implementación de Metropolis para el
  modelo de Ising.
- `generar_graficas.py`: reproduce las dos gráficas para el informe (energía vs
  tiempo de simulación, y magnetización vs temperatura).

#Uso

Correr una simulación individual:
python ising_metropolis.py

Reproducir las graficas del informe:
python generar_graficas.py

#Parámetros usados en el informe
- Tamano de red: L = 20 (N = 400 espines)
- Unidades: J = 1, k_B = 1 (T en unidades de J/k_B)
- Termalización: 800-1500 barridos Monte Carlo (1 barrido = N intentos de volteo)
- Medición: 4000 barridos, muestreando cada 5 barridos
- Temperatura crítica teórica: T_c = 2/ln(1+sqrt(2)) ~= 2.269
