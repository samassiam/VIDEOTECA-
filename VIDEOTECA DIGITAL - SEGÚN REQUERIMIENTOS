# ============================================
# VIDEOTECA DIGITAL - SEGÚN REQUERIMIENTOS
# ============================================

# -------------------------------
# ENTRADA (MATRIZ DE DATOS)
# -------------------------------
# [Título, Año, Calificación, Género]

videoteca = [
    ["Avengers: Endgame", 2019, 9.0, "Acción"],
    ["Inception", 2010, 8.8, "Ciencia Ficción"],
    ["Titanic", 1997, 7.8, "Romance"],
    ["Parasite", 2019, 8.6, "Drama"],
    ["Joker", 2019, 8.5, "Drama"],
    ["Frozen II", 2019, 7.0, "Animación"],
    ["The Batman", 2022, 8.2, "Acción"]
]

# -------------------------------
# MÓDULO (FUNCIÓN)
# -------------------------------
def contar_titulos(matriz, umbral_calificacion, anio_limite):
    """
    Procesa la matriz y cuenta los títulos que cumplen:
    - Calificación >= umbral
    - Año >= año límite
    """
    
    contador = 0  # Variable de salida interna
    
    # -------------------------------
    # PROCESAMIENTO
    # -------------------------------
    for titulo in matriz:
        nombre = titulo[0]
        anio = titulo[1]
        calificacion = titulo[2]
        genero = titulo[3]
        
        # -------------------------------
        # LÓGICA DE NEGOCIO
        # -------------------------------
        if calificacion >= umbral_calificacion and anio >= anio_limite:
            contador += 1
            print(f"✔ Cumple: {nombre} | Año: {anio} | Calificación: {calificacion}")
    
    return contador


# -------------------------------
# ENTRADA DE CRITERIOS
# -------------------------------
umbral = float(input("Ingrese la calificación mínima (ej: 8): "))
anio_minimo = int(input("Ingrese el año mínimo (ej: 2018): "))


# -------------------------------
# LLAMADO AL MÓDULO
# -------------------------------
resultado = contar_titulos(videoteca, umbral, anio_minimo)


# -------------------------------
# SALIDA
# -------------------------------
print("\n===================================")
print(f"Total de títulos que cumplen: {resultado}")
print("===================================")
