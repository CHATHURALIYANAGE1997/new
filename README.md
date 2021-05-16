# new
Assignment 01
package demo

object demo {

  def temperature(celsius:Int):Double={
    var Fahrenheit:Double=0;
    Fahrenheit=celsius*1.8 +32
    return Fahrenheit
  }

  def volume(radius:Int):Double={
    var Tot:Double = 0
    val pi:Double = (22).toDouble./(7:Double)
    var r3 = scala.math.pow(5,3)
    Tot = (4).toDouble./(3:Double)*pi*r3
    return Tot

  }

  def cost(books:Int):Double={
    var totalcost:Double =0
    totalcost=((60).toDouble./(100:Double)*24.95*books)+3+(books-50)*0.75
    return totalcost
  }



  def main(args: Array[String]): Unit = {
    println("Temperature is " + temperature(celsius=35) +"F")
    println("volume is  " + volume(5))
    println("Total cost  is Rs." + cost(60))
  }
}
