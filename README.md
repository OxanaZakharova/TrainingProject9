# TrainingProject9
MathTest, Java, JUnit, 02/2019


Ni ska skapa enhetstester för en Matematik-klass med Add, Substract, Multiply och Divison. Verktyget som skall användas för att skapa dessa tester heter JUnit.  

Skilja på produktionskod och testkod
En vilktig del när man skriver enhetstester är att man kan skilja på produktionskoden och testkoden. För denna uppgift betyder det att produktionskoden ligger i en mapp som heter src och testkoden ska ligga i en mapp som heter test.

Använda annoteringar 
JUnit använder annoteringar för att styra vad som ska köras och när. Det som krävs är att ni sätter upp ert System Under Test (SUT) i en speciell metod som körs före testerna med hjälp av en annotation och att testmetoderna är annoterade på rätt sätt så att JUnit kan köra testerna.

Testtäckning
När man skapar tester så använder man olika testtekniker för att bestämma vad som skall testas. För varje metod ni gör tester för så måste ni veta vilken eller vilka tekniker ni använder och även kunna förklara varför. Det finns inga rätt och fel här utan det viktiga är att ni kan berätta vad ni valt att testa och varför samt kunna ge för och nackdelar med ert val jämfört med andra.

Ni kan alltså välja flera olika tekniker men alla metoder i SUTen måste vara testade på en av er definierad nivå.

Självständiga tester
Varje test måste kunna köras självständigt så de kan inte vara beroende av varandra. Detta är viktigt då man arbetar med testerna i verkligheten för då vill man kanske köra om ett test som fallerat för att se varför och för att kontrollera att man rättat upp det om det var något fel.

Extrauppgift
Skapa en testsvit som kör två mer avancerade matematiktester, tex Faculty eller Fibonacci etc, beroende på era matematik-kunskaper.

