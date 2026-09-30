peliculas = {
    "accion": ["Avengers", "Misión Imposible", "John Wick"],
    "comedia": ["Son como niños", "¿Qué pasó ayer?", "Mi pobre angelito"],
    "drama": ["Titanic", "Forrest Gump", "En busca de la felicidad"]
}

print("Sistema de recomendación de películas")
print("Categorías disponibles: accion, comedia, drama")

categoria = input("Ingresa una categoría: ").lower()

if categoria in peliculas:
    print("Películas recomendadas:")
    for pelicula in peliculas[categoria]:
        print("-", pelicula)
else:
    print("No encontramos recomendaciones para esa categoría.")
