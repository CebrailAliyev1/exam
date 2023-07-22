# exam
SUAL3
1.Parametrli constructor
class person(val name:String,val age:Int){}
2.paramtersiz constructor
class person(){}
3.nested primary constructor
class person(){var age:Int=0
constructor(name:String,age:Int):this(name){
this.age=age
}
}

SUAL4
data class bize verilen melumatlari saxlamaq dasimaq ucundur.bu verileri tutmaq ucun yaradilan sinifdir icinde properties vs olur
data class person(var name:String,var age:Int)

SUAL 5
var arr=arrayof(1,2,23,45,56)
array ilk indexi 0dan basliyir.
icindeki sayini ise size ile tapa bilerik.

SUAL6 
var is mutable,val is immutable

SUAL7
val a = "Hello"
val b = "World"
val c = "$a $b"
println(c)
SUAL8
?  null olub olmmasini bildilir
! ise deqiq null olmadigini bildilir
SUAL11
life cycyle activitynin basdan sona qederki yolunu gosterir.
burada bir nece metod vardir.
onresume,on destroy,onstart,oncreate vs
on create activitynin baslanmasini bildilir
on start istifadecinin gormden evvelki yoludur
on resume esasen basqa bir activity kecdikde bas verir
on destroy tamam baglandiqda bas verir

SUAL12 butun projectlerde olan ve icinde  Activities, Services, Content Providers, and Broadcast Receivers bunlari saxliyir
SUAL 13 
intent bir activiyden novbeti activity ve ya fragmentden digerine kecemek ucun istifade olunur

SUAL 14
relative layout,linear,constraint layout,grid,table
constraint en yeni ve daha elcatan layoutdur
linear oritentian vermekle horizontal ve ya vertical duzulus
grid row column ile duzmek ucundur
