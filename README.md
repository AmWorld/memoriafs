# memoriafs
el archivo se llama reto1

codigo:
import UIKit

var retos = 1...100

for reto in retos{
    var par = reto%2
    var cinco = reto%5
    if par == 0{
        print("\(reto)\t\("par")")}
    if par == 1{
        print("\(reto)\t\("impar")")}
    if cinco == 0{
        print("\(reto)\t\("BINGO!!!")")}
    if reto>29 && reto<41{
        print("\(reto)\t\("VIVA SWIFT!!!")")}
    }


