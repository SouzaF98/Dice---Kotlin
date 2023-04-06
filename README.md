# Dice-Kotlin
Resolução do problema "Dice" em Kotlin adotando boas práticas de programação (refatoração).

fun main() {

    val myFirstDice = Dice(6)
  //  val diceRoll = myFirstDice.roll()
    println("Your ${myFirstDice.numSides} sided dice rolled ${myFirstDice.roll()}!")

    val mySecondDice = Dice(20)
    println("Your ${mySecondDice.numSides} sided dice rolled ${mySecondDice.roll()}!")
}

class Dice (val numSides: Int) {

    fun roll(): Int {
       // val randomNumber = 
        return (1..numSides).random()
    }
}


