LOC za kompletan projekat (Calculator.java i Start.java) iznosi 188
LOC za Calculator.java iznosi 188
LOC za Start.java iznosi 26

Code Complexity Report za Calculator: umereno kompleksan kod
cikomatska slozenost Calculator::evaluateExpression je 12
cikomatska slozenost Calculator::Calculate je 12

Code Complexity Report za Start: jednostavan kod
cikomatska slozenost Start::main je 3
Kognitivna slozenost
kognitivna slozenost metoda evaluateExpression je 6
kognitivna slozenost metoda Calculate je 9

Statička analiza fajla koristeći Sonarlint:
Calculator.java - linija 4 - dodati privatni konstruktor umjesto javnog (Add a private constructor to hide the implicit public one)
Calculator.java - linija 18 - metoda "ToString" treba biti zamijenjena "toString" (Rename method "ToString" to prevent any misunderstanding/clash with method "toString" defined in superclass "java.lang.Object")
Calculator.java - linija 24 - metoda "Run" treba niti zamijenjena sa "run" (Rename this method name to match the regular expression)
Calculator.java - linija 183 - "return" može da se ukloni (Remove this redundant jump)
Start.java - linija 6 - "Expression" zamijeniti sa "expression" (Rename this local variable to match the regular expression)
Start.java - linija 8 i linija 19 - "System.out" zamijeniti sa logger (Replace this use of System.out by a logger)

