se hace click en "Tools -> Kotlin -> Kotlin REPL"

Y esto es lo que hice dentro de la sandbox
"C:\Program Files\Android\Android Studio\jre\bin\java.exe" -Dkotlin.repl.ideMode=true -Dfile.encoding=UTF-8 @C:\Users\victo\AppData\Local\Temp\idea_arg_file139724769 Welcome to Kotlin version 1.5.31-release-550 (JRE 11.0.10+0-b96-7249189) Type :help for help, :quit for quit

1+1 res0: kotlin.Int = 2

1+ 1.0 res1: kotlin.Double = 2.0

30/10 res2: kotlin.Int = 3

30/10.0 res3: kotlin.Double = 3.0

val i : Int = 6

println(i) 6

val I =.itoByte() error: expecting an expression val I =.itoByte() ^ error: property getter or setter expected val I =.itoByte() ^

val I = i.toByte()

println(I) 6

I = 257 error: val cannot be reassigned I = 257 ^ error: the integer literal does not conform to the expected type Byte I = 257 ^

I = 257 error: val cannot be reassigned I = 257 ^ error: the integer literal does not conform to the expected type Byte I = 257 ^

I = i error: val cannot be reassigned I = i ^ error: type mismatch: inferred type is Int but Byte was expected I = i ^

val I : Int 257 incomplete code

val I : int = 257 error: unresolved reference: int val I : int = 257 ^

val I : Int = 257

println(I) 257

val b2 : Byte = 100

println(b2) 100

val i3 : Int = b2 error: type mismatch: inferred type is Byte but Int was expected val i3 : Int = b2 ^

val i4 : Int = b2.toInt()

println(i4) 100

var numeroDeManzanas = 5

println (numeroDeManzanas) 5

var numeroDePlatanos = 12

println (numeroDePlatanos) 12

"Tenemos en la Frutera $numeroDeManzanas manzanas" + " y $numeroDePlatanos platanos" res25: kotlin.String = Tenemos en la Frutera 5 manzanas y 12 platanos

numeroDeManzanas = numeroDePlatanos

println (numeroDeManzanas) 12

"Tenemos en la Frutera $numeroDeManzanas manzanas" + " y $numeroDePlatanos platanos" res28: kotlin.String = Tenemos en la Frutera 12 manzanas y 12 platanos

lateinit var adapter : Posillo error: unresolved reference: Posillo lateinit var adapter : Posillo ^

lateinit var adapter: Adapter = Posillo error: 'lateinit' modifier is not allowed on properties with initializer lateinit var adapter: Adapter = Posillo ^ error: unresolved reference: Adapter lateinit var adapter: Adapter = Posillo ^ error: unresolved reference: Posillo lateinit var adapter: Adapter = Posillo ^

fun printHello() { prinln("Hola Kotlin") } error: unresolved reference: prinln prinln("Hola Kotlin") ^

fun printHello() { println("Hola Kotlin") }

printHello() Hola Kotlin

fun colacion () { val dia: Int =6 val fruta = "arandanos" println("Hoy es el día $dia y la colación que se come es $fruta") }

colacion() Hoy es el dï¿½a 6 y la colaciï¿½n que se come es arandanos

fun colacion () { val dia: Int =5 val fruta = "peras" println("Hoy es el dia $dia y la colacion que se come es $fruta") }

colacion() Hoy es el dia 5 y la colacion que se come es peras
