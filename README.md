# For
Listas
fun main(){
    val nombres = list0f(
        "Kirby",
        "Ness",
        "Fox",
        "Luigi",
        "Mario",
        "Link",
        "Captain Falcon",
        "Samus",
        "Pikachu",
        "Jigglypuff",
        "Donkey Kong",
        "Yoshi"
        
    )
    for (nombre in nombres){
        println(nombre)
        if (nombre=="Link"){
            println("Personaje Encontrado!")
            break
        }
    }
}
