@startuml
package "POOP9" #DDDDDD {
    class serVivo{
        -nombre:String
        -edad:int
        -peso:float
        +dormir()
        +comer()
    }
    class mascota {
        -color: String
        -raza: String
        -tamaño: char
        +jugar()
        +correr()
    }
    serVivo <|--mascota

}
@enduml