# Resum T1 Introdrucció a la programació
#### En aquest primer tema, aprendrem a reconèixer els elements i les eines que intervenen en el desenvolupament d'un programa informàtic, analitzant-ne les característiques i les fases en què actuen fins a arribar a la posada en funcionament.

## 1. Introducció
- Un ***programa*** és un conjunt d’instruccions (aritmètico-lògiques), executades de manera seqüencial, per tal d’obtenir el resultat esperat.
- Una ***instrucció*** és un conjunt de dades dins d’una seqüència estructurada que el processador interpreta i executa.

### 1.1. Orígens de la programació

- ***Joseph Marie Jacquard***: inventor francès conegut per automatitzar, mitjançant l'ús de targetes perforades, l'anomenat teler de Jacquard.
- ***Charles Babbage***: creador de la màquina diferencial i la màquina analítica (basada en el teler de Jacquard).
- ***Ada Lovelace***: desenvolupadora de programes per a la màquina analítica de Baggage. A causa d'això va ser considerada la primera programadora de la història. Va ser la primera a utilitzar instruccions condicionals i iteratives, que són la base de la programació actual.
- ***Alan Turing***: creador de la màquina de Turing, va treballar en camps com la informàtica teòrica, la criptoanàlisi o la intel·ligència artificial. És considerat el pare de la informàtica moderna.
- ***Grace Hopper (Amazing Grace)***: es va allistar en la marina on va treballar com a programadora en el computador Harvard Mark I. És la creadora del primer compilador i del llenguatge de programació Cobol.

### 1.2. Llenguatges de programació

- Codi font: fitxer o conjunt de fitxers que contenen les instruccions del programa.

- Linker: encarregat d’inserir al codi objecte les funcions de les llibreries que són necessàries per al programa i de dur a terme el procés de muntatge generant un arxiu executable.

- Llibreria: col·lecció de codi predefinit que facilita la tasca del programador a l’hora de codificar un programa.

Els llenguatges de programació es classifiquen:

- segons el nivell d’abstracció del llenguatge

- segons el tipus de traducció del programa al llenguatge màquina

#### 1.2.1. Nivells d'abtracció dels llenguatjes

Un llenguatge de programació ***d'alt nivell*** es caracteritza per expressar els algorismes d'una manera adequada a la capacitat cognitiva humana.

En un llenguatge de programació ***de baix nivell***, en canvi, les seves instruccions exerceixen un control directe sobre el maquinari.

#### 1.2.2. Tipus de traducció dels programes

Els ***llenguatges compilats*** tradueixen (compilen) tot el codi font i contenen aquesta traducció en un arxiu executable comprensible per a la màquina en la plataforma en què s'ha compilat.

Els ***llenguatges interpretats*** tradueixen (interpreten) el codi font pas a pas.

#### 1.2.3. Com executa un programa l'orginador

1. S’introdueixen les dades a l’ordinador

2. El processador executa les instruccions

3. Els resultats de les operacions s’emmagatzemen a la RAM

4. Els resultats finals s’emmagatzemen al disc du

#### 1.2.4. Com codifica la informació l'ordinador

Quan treballem amb números, acostumem a treballar en codificació ***decimal*** (en base 10). L'ordinador, en el seu nivell més baix, treballa en format ***binari*** (en base 2). No obstant, també farem servir altres tipus de codificacions: ***octal*** (en base 8) i ***hexadecimal*** (en base 16).

En el cas de la codificació de caràcters, es fa servir la taula ***ASCII*** i la taula ***Unicode***, que estandaritzen la relació entre caràcters alfabètics i símbols amb valors decimals.

### 1.3. Llenguatges y paradigmes de programació

#### 1.3.1. Generacions dels llenguatges de programació

##### **Llenguatge de primera generació**

Correspon al ***llenguatge de baix nivell*** o ***llenguatge màquina***. És màquina-dependent i les sentències del programa s'escriuen en codi binari (0/1).

- Avantatges:

  1. Ràpid i eficient, ja que les declaracions s'escriuen directament en llenguatge binari.

  2. No cal traductor.

- Inconvenients:

  1. Dificultat per aprendre codis binaris.

  2. Dificultat d'entendre (el programa i on s'ha produït l'error).

##### **Llenguatges de segona generació**

Són anomenats llenguatges ***d’assemblador***.

- Avantatges:

  1. És més fàcil d'entendre si es compara amb el llenguatge màquina.

  2. Les modificacions són fàcils.

  3. La localització d'errors i la seva correcció són fàcils.

- Inconvenients:

  1. Es requereix un assemblador.

  2. Aquest llenguatge depèn de l'arquitectura /màquina, amb un conjunt d'instruccions diferent per a diferents màquines (depèn de l'arquitectura de l'ordinador).

##### **Llenguatges de tercera generació**

La tercera generació també s'anomena ***llenguatge procedimental*** o ***llenguatge de programació d'alt nivell***.

- Avantatges:

  1. L'ús de paraules semblants a l'anglès el converteix en un llenguatge comprensible per a l'ésser humà.

  2. Requereix un menor nombre de línies de codi en comparació amb els dos llenguatges anteriors.

  3. El mateix codi es pot copiar a una altra màquina i executar-lo utilitzant el compilador específic d'aquesta màquina.

- Inconvenients:

  1. Cal un compilador/intèrpret.

  2. Es necessiten diferents compiladors per a diferents màquines.

##### **Llenguatges de quarta generació**

Els llenguatges de quarta generació també s'anomena ***llenguatges no procedimentals*** o de ***propòsit específic***.

- Avantatges:

  1. Fàcil d'entendre i aprendre.

  2. Es requereix menys temps per a la creació de l'aplicació.

  3. És menys propens a errors.

- Inconvenients:

  1. El consum de memòria és elevat.

  2. Té un mal control sobre el maquinari.

  3. Menys flexible que els llenguatges de 3a generació.

##### **Llenguatges de cinquena generació**

Els llenguatges de cinquena generació es basen en el concepte d'intel·ligència artificial.

- Avantatges:

  1. Les màquines poden prendre decisions.

  2. L'esforç del programador es redueix per resoldre un problema.

  3. Més fàcil que els llenguatges de 3a o 4a generació per aprendre i utilitzar.

- Inconvenients:

  1. Codi complex i llarg.

  2. Es necessiten més recursos i també són cars.

#### 1.3.2. Paradigmes de programació

Un ***paradigma*** de programació consisteix en els mètodes per dur a terme càlculs i en la forma en la qual han d'estructurar-se i organitzar-se les tasques que ha de realitzar un programa.

- **Programació imperativa o per procediments**: És el més usat en general i  es basa a donar instruccions a l'ordinador de com fer les coses en forma d'algorismes, en lloc de descriure el problema o la solució.
- **Programació orientada a objectes**: Està basada en el paradigma imperatiu, però encapsula elements denominats objectes que inclouen tant variables com funcions.
- **Programació dirigida per esdeveniments**: La programació dirigida per esdeveniments és un paradigma de programació en el qual tant l'estructura com l'execució dels programes van determinats pels successos que esdevenen el sistema, definits per l'usuari o que ells mateixos provoquin.
- **Programació declarativa**: Està basat a descriure el problema declarant propietats i regles que han de complir-se, en lloc d'instruccions.
- **Programació multiparadigma**: És l'ús de dos o més paradigmes dins d'un programa.

## 2. Disseny d'algorismes

##### **Etapes del disseny d'un programa**

1. **Anàlisi**: s’estudia el problema a resoldre.

2. **Disseny**: es defineix la manera de resoldre el problema (algorisme), indicant els passos a seguir mitjançant una especificació formal (tècniques descriptives).

3. **Programació**: s'implementen les instruccions l’algorisme en un llenguatge de programació d’alt nivell.

4. **Compilació**: el codi d’alt nivell es tradueix de manera que l’ordinador pugui executar el programa.

5. **Execució i proves**: s’executa el codi amb diferents valors d’entrada per provar que aquest funciona per a qualsevol cas (esperat i obtingut).

### 2.1. Anàlisi

Durant la fase d’anàlisi, no es busca una forma de resoldre el problema, només es tracta de comprendre’l. 

Un algorisme ben format haurà de complir les següents condicions:

- Precís: ha d’indicar pas a pas totes les operacions i instruccions a seguir per a resoldre el problema.

- Ben definit: si coneixem les entrades de l’algorisme, aquest sempre produirà la mateixa sortida i la màquina interna passarà per la mateixa seqüència d’estats (és un algorisme determenístic).

- Finit: l’algorisme ha d’acabar en algun moment.

- Robust: l’algorisme ha de tenir una resposta clara, independentment de la seva entrada i la seva execució.

- Transportable: un algorisme estarà dissenyat de manera que pugui executar-se, independentment del maquinari (hardware) i programari (SO) instal·lat.

A l’hora de plantejar la solució a un problema, cal tenir resoltes les següents preguntes:

- Pregunta: què és el que ens demanen, que hem d’obtenir?

- Dades: de quina informació disposem (directa o calculada) per a resoldre el problema?

- Operacions: quines accions haurem de realitzar per a resoldre la pregunta?

- Sortida: les operacions executades resolen la pregunta?

- Errors: és possible que en executar alguna operació, es pugui donar un error?

#### 2.1.1. Les dades

##### **Què és una dada?

Una dada és una representació simbòlica (numèrica, alfabètica, …) d'una característica d’una entitat (un objecte de la vida real). No té valor semàntic (sentit) per si mateixa, però convenientment tractada (processada) es pot emprar en la realització de càlculs o presa de decisions. 

##### **Tipus de dades**

Tipus de dades
Els tipus de dades que es faran servir en el disseny d'algorismes (i la seva posterior implementació en un llenguatge d'alt nivell) es classifiquen en:

- Simples

  - numèriques

    - enter: representa un valor numèric, positiu o negatiu, sense cap decimal

    - real: representa un valor numèric, positiu o negatiu, amb decimals

  - no numèriques

    - booleà: representa un valor de tipus lògic per tal d’establir la certesa o falsedat d’un estat o afirmació

    - caràcter, cadena de caràcters: representa una unitat fonamental de text usada en qualsevol alfabet, un nombre o un signe de puntuació o exclamació

- Estructurades

  - internes

    - estàtiques (registres, vectors, taules)

    - dinàmiques (llistes, cues, piles, arbres)

  - externes

    - fitxers

    - bases de dades

#### 2.1.2. Les expressions

##### **Què és una expressió?**

Una expressió és la representació de diversos operands, units entre ells mitjançant operadors, per tal de realitzar una acció sobre ells, ja sigui aritmètica, lògica o d'ambdues.

Els operadors bàsics que ens permeten realitzar accions sobre els operands són els següents:

- assignació: x = y

- aritmètics:

  - addició: x = x + y

  - sostracció: x = x - y

  - multiplicació: x = x * y

  - divisió: x = x / y

  - mòdul: x = x % y

  - increment: ++

  - decrement: --

  - potenciació: **

- comparació:

  - == (igual)

  - != (diferent)

  - < (menor que),  > (més gran que)

  - <=  (menor o igual que), >= (més gran o igual que)

### 2.2. Disseny

S’utilitza habitualment la tècnica del disseny “top-down” (descendent), basada en el principi de “dividir i vèncer”.

Quines són les característiques del disseny “top-down”?

1. Es planteja el problema utilitzant termes del mateix problema (nivell d’abstracció 1).

2. Es descompon en diversos subproblemes, expressats també en termes del problema i intentant de fer-los de la manera que aquests siguin el més independent entre ells possible (nivell d’abstracció 2).

3. Es repeteix el pas 2 per a cada subproblema, tantes vegades com aquest sigui necessari, fins a arribar a una descripció del problema que utilitzi instruccions senzilles que puguin ser transformades de manera simple a codi en un llenguatge de programació (nivell d’abstracció 3).

#### 2.2.1. Especificació

##### **Especificació de l'algorisme**

La descomposició del problema es pot representar de maneres diferents:

- Pseudocodi: és una descripció informal d’alt nivell de l’algorisme.

- Diagrames de flux: són una representació gràfica del disseny de l’algorisme.

- Diagrames de Nassi-Shneiderman: són una representació gràfica del disseny de l’algorisme.

Abans d’especificar el nostre programa, cal que tinguem en compte:

- Precondició: propietats que han de complir els paràmetres perquè l’operació faci el que està previst;

- Postcondició: propietats que han de complir els resultats després de cridar l’operació, incloent-hi els paràmetres per referència si volem modificar-los.

#### 2.2.2. Pseudocodi

El pseudocodi és una descripció a molt alt nivell de l'estructura d'un programa.

Les primeres línies del programa contenen les declaracions de les constants i les variables que requerirà l'algorisme. El cos del programa conté totes les instruccions que ha d’executar l’ordinador de manera seqüencial. Aquestes poden ser de diferents tipus:

##### Simples

- primitives (declaratives)

  - entrada

  - sortida

  - assignació

- de control

  - alternatives (condicionals)

    - simples

    - dobles

    - múltiples

  - repetitives (iteratives)

##### Compostes (funcions)

Els comentaris en realitat no es consideraran instruccions, ja que aquests són missatges indicatius per a nosaltres o altres programadors i aquests no són traduïts pel compilador.

Les ***estructures condicionals*** controlen la seqüència d’execució d’altres instruccions, segons una determinada condició. Poden ser simples, dobles o múltiples.

##### Condició simple

    if <condicio_certa> then
        instruccio_condicio_certa;
    endif

##### Condició doble

    if <condicio_certa> then
        instruccio_condicio_certa;
    else
        instruccio_condicio_falsa;
    endif

##### Condició múltiple

    if <condicio_certa> then
        instruccio_condicio_certa;
    else
        if <condicio_certa> then
            instruccio_condicio_certa;
        else
	        instruccio_condicio_falsa;
        endif
    endif

##### Compte!

En una decisió, si no es compleix la condició “si”, no cal definir la condició “si no”

Les iteracions o bucles repeteixen un cert nombre de vegades les expressions que hi ha contingudes dins d’un algorisme. Segons la condició de repetició, hi ha tres tipus diferents d'estructures de repetició:

##### While (mentre)

    while <condicio> do
        instruccio_1;
        instruccio_2;
        …
    endwhile

##### Do...While (fer...mentre)

    do
        instruccio_1;
        instruccio_2;
        …
    while <condicio>;

##### For (repetir)

    for <vinicial> to <vfinal>
        instruccio_1;
        instruccio_2;
        …
    endfor

#### 2.2.3. Diagrames de flux

El diagrama de flux (flowchart) és una representació gràfica simple de l'estructura d'un programa.

De la mateixa manera que podem especificar i combinar diferents tipus d'instruccions (declaratives, iteratives, de decisió...) dins d'un pseudocodi, es poden encadenar diferents símbols en un diagrama de flux.

#### 2.2.4. Diagrames de Nassi-Shneiderman

Els diagrames de Nassi-Shneiderman són una representació gràfica del disseny per a la programació estructurada. Estan basats en la representació de les diferents instruccions en forma de caixes, dins de les quals es descriuen les accions.

#### 2.2.5. Jocs de proves

Els jocs de proves documenten els casos provats i els resultats obtinguts, per tal de corregir i millorar els programes.

Un error no detectat a l’inici del desenvolupament d’un projecte pot arribar a necessitar cinquanta vegades més esforços per ser solucionat que si és detectat a temps. Per tant, es considera una bona pràctica elaborar el joc de proves de l'algorisme abans de ser implementat en un llenguatge d'alt nivell.

## 3. Implementació d'algorismes

Un error no detectat a l’inici del desenvolupament d’un projecte pot arribar a necessitar cinquanta vegades més esforços per ser solucionat que si és detectat a temps. Per tant, es considera una bona pràctica elaborar el joc de proves de l'algorisme abans de ser implementat en un llenguatge d'alt nivell.

Tot i que podem programar només amb un editor de text i el compilador corresponent, disposem d'una eina que ens facilita la nostra tasca, no només en la implementació de codis, sinó també en la detecció d'errors. Ens referim als IDEs (Integrated Development Environments).

Les característiques principals són:

- Remarcat de sintaxi

- Compleció de codi

- Refactorització

- Control de versions

- Debugging (depuració)

- Cerca dins del codi

- Programació visual

- Suport per a llenguatges (documentació

### 3.1. Visual studio community

Visual Studio és un IDE desenvolupat per Microsoft que permet desenvolupar aplicacions en diferents llenguatges de programació, especialment tots aquells de la família de C.

Visual Studio conté el programa dins la solució del projecte.

##### .vs

És un directori ocult que conté la informació del projecte, com ara projectes recents, arxius de configuració, … Permet recuperar el darrer estat en el que es va treballar el projecte (snapshot).

##### Directori del projecte

El directori del projecte és una carpeta que conté diferents arxius i carpetes:
- codi font del projecte (.cs)

- fitxer de configuració del projecte (.csproj)

- directori de depuració i execució bin (conté el fitxer .exe per a distribuir el programa)

- directori obj  (conté arxius temporals necessaris pel VS en el procés d’edició i compilació del codi font)

##### .sln

És un fitxer que permet obrir tot el projecte, fent doble clic sobre ell.

### 3.2. El llenguatge C#

C# (pronunciat "si sharp" en anglès) és un llenguatge de programació modern, basat en objectes i amb tipatge de dades.

C# permet crear molts tipus d'aplicacions segures i sòlides que s'executen en .NET. Té les seves arrels en la família de llenguatges C i és un llenguatge de programació orientat a components i orientat a objectes.

El recol·lector d'elements no utilitzats de .NET (garbage collector) administra l'assignació i alliberament de la memòria de l'aplicació.

No és obligatori però sí recomanable formatar bé el codi (evitar codi ofuscat). El propi IDE permet formatar tot el codi font.

#### 3.2.1. Tipus des dades

##### 3.2.1.1. Comentaris

Els comentaris són anotacions dels desenvolupadors, tant per la resta de l’equip com per si mateix. Indiquen breument el funcionament del fragment de codi.

El compilador, en arribar a una línia comentada (o bloc comentat), no el tradueix a llenguatge màquina i passa a la següent línia de codi.

    //Comentari en una línia

    /*

	    Comentari en

        diverses línies

    */

##### 3.2.1.2. Variables

Una variable és una dada emmagatzemada en una posició de la memòria, que pot veure modificat el seu valor en qualsevol moment durant l’execució del programa.

A l’hora de declarar una variable, s’ha d’indicar el tipus de dada que es vol emmagatzemar i el nom de la variable.

    int num; 
    int a = 5;
    int b = a + 2; //OK
    bool test = true;

Es poden declarar més d’una variable del mateix tipus en la mateixa línia d’instrucció:

    int a = 3, b = 15, c = 30;

També es pot assignar el mateix valor a diverses variables en la mateixa línia d’instrucció:

    int a, b, c;
    a=b=c=20;

Respecte els identificadors (noms de les variables), hem de tenir en compte que:

- Els noms poden contenir lletres, dígits i el caràcter de subratllat (_))

- Els noms han de començar amb una lletra o guió baix  i no poden contenir espais en blanc. Se segueix la notació lowerCamelCase.

- Els noms distingeixen entre majúscules i minúscules ("myVar" i "myvar" són variables diferents). C# és case sensitive.

- Les paraules reservades (com les paraules clau C#, com ara int o double) no es poden utilitzar com a noms de variables

Una constant és un tipus especial de variable que té la particularitat que dins del codi del programa el seu valor només pot ser llegit, però mai modificat. Se segueix la nomenclatura UpperCamelCase.

    const int MyNum = 15;
    const bool Test = true;

##### 3.2.1.3. Tipus de dades

C# implementa els tipus de dades bàsics i aporta alguns més, per donar més flexibilitat a l'hora d'optimitzar els algorismes. Aquests tipus de dades d'anomenen built-in types:

Els tipus de dades lògics (booleans) només poden prendre dos valors: cert (true) o fals (false):

    bool myBool = false;
    const bool MyBool = true;

La seva mida és de 1 byte.

Els valors a les variables de tipus caràcter (char) s’assignen amb cometes simples (‘’). En la declaració es reserven 2 bytes de memòria i segueixen la codificació UNICODE.

    char myChar = ‘a’;
    const char Val = ‘Y’;

Els valors a les variables de tipus cadenes de caràcter (string) s’assignen amb cometes dobles (“”). Segueixen la codificació UNICODE.

    string myString = “Hola”;
    const string Msg = “Vols introduir un valor?”;

#### 3.2.2. Operadors

##### 3.2.2.1. Operadors aritmètics

    +
    -
    *
    /
    &

    +=
    -=
    *=
    /=

    ++
        x++ "Assigna i després incrementa"
        ++x "Incrementa i després assigna"
    --
        x-- "Assigna i després decrementa"
        --x "Decrementa i despés assigna"

##### 3.2.2.2. Operadors (relació) i operadors lògics

    <
    >
    <=
    >=
    ==
    !=
    ? :

    !
    &&
    ||

#### 3.2.3. Conversio de tipus

El casting (conversió de tipus) consisteix en assignar un valor d'un tipus de dades a un altre tipus.

En C#, hi ha dos tipus de càsting:

Càsting implícit (automàtic): converteix un tipus més petit a una mida de tipus més gran
    
    char -> int -> long -> float -> double

Càsting explícit (manual): converteix un tipus més gran a un tipus més petit:
    
    double -> float -> long -> int -> char

El casting implícit es fa automàticament en passar un tipus de mida més petita a un tipus de mida més gran:

    int myInt = 9;
    double myDouble = myInt;       // Automatic casting: int to double
    Console.WriteLine(myInt);      // Mostra 9
    Console.WriteLine(myDouble);   // Mostra 9

El casting explícit s'ha de fer manualment indicant el tipus entre parèntesis davant del valor.

    double myDouble = 9.78;
    int myInt = (int) myDouble;	   // Manual casting: double to int
    Console.WriteLine(myDouble);   // Mostra 9.78
    Console.WriteLine(myInt);  	  // Mostra 9

També és possible convertir els tipus de dades explícitament utilitzant mètodes integrats (built-in methods) de la classe Convert (ToBoolean, ToByte, ToChar, ToDateTime, ToDecimal, ToDouble, ToInt16, ToInt32, ToInt64, ToSbyte, ToSingle, ToString, ToType, ToUInt16, ToUInt32, ToUInt64). Aquests mètodes converteixen un valor especificat en un tipus específic (segons el mètode emprat).

Un altre cas són els mètodes Parse i TryParse, que permeten convertir un string a valor de tipus numèric. És una mica més eficient i senzill invocar un mètode TryParse o un mètode Parse que no pas utilitzar un mètode de de la classe Convert, ja que aquests fan servir internament el mètode Parse.

    num = Convert.ToInt32(Console.ReadLine());
    num = int.Parse(Console.ReadLine());
    bool isInt = int.TryParse(Console.ReadLine(), out num);

Tenint en compte que esperem rebre una dada convertible a un valor de tipus enter, és possible que hi hagi un error en la introducció per teclat, fet que ens generarà un error.

Això es pot solucionar recollint les excepcions que es poden generar, mitjançant la clàusula try-catch.

    int num;
    Console.WriteLine("Introdueix un número: ");
    try
    {
        num = Convert.ToInt32(Console.ReadLine());
        Console.WriteLine("El valor introduït és {0}", num);
    }
    catch (FormatException)
    {
        Console.WriteLine("No has introduït un número enter");
    }
    catch (OverflowException)
    {
        Console.WriteLine("El número introduït és massa gran");
    }
    catch (Exception)
    {
        Console.WriteLine("Error inesperat");
    }

Dins del bloc try s'indiquen aquelles instruccions susceptibles de generar un error (de format, de número d'arguments, de límit, ...) i a continuació, s'indiquen com es recullen aquells errors (catch ). Com a mínim, s'ha de recollir un Exception, que és el més genèric.

#### 3.2.4. Entrada i sortida de dades

L'entrada i sortida de dades per consola es fa mitjançant els diferents mètodes de la classe Console. 

##### 3.2.4.1. Entrada de dades

    string userName = Console.ReadLine(); //retorna una línia de caràcters
    char letter = (char)Console.Read(); //casting per obtenir el caràcter (retorna un int)
    Console.ReadKey(); //retorna la tecla introduïda per consola

##### 3.2.4.2. Sortida de dades

    Console.Write("Hello"); //posiciona el cursor a continuació
    Console.Write(" world!");
    
    Console.WriteLine("Hello world!"); //posiciona el cursor a la línia següent

A l'hora de mostrar literals i variables per consola, cal tenir en compte el formateig de les dades, de manera que la informació sigui més amigable per a l'usuari final. Quan parlem de cadenes de text (strings) podem fer servir dos tipus:

- interpolació

- composite formatting

El caràcter $ identifica una cadena literal com una cadena interpolada. Una cadena interpolada és una cadena literal que pot contenir expressions d'interpolació. Quan una cadena interpolada es resol a una cadena de resultat, els elements amb expressions d'interpolació se substitueixen per les representacions de cadena dels resultats de l'expressió.

    int age = 18;
    string name = "Maria";
    string surname = "Garcia";
    Console.WriteLine($"L'alumna {name} {surname} té {age} anys.");

La interpolació de cadenes proporciona una sintaxi més llegible i convenient per formatar cadenes. És més fàcil de llegir que la formatació composta de cadenes.

En el cas del composite formatting, la cadena es forma a partir d'una llista de valors que se substitueixen en les posicions indicades.

    int age = 18;
    string name = "Maria";
    string surname = "Garcia";
    Console.WriteLine("L'alumna {0} {1} té {2} anys.", name, surname, age);

#### 3.2.5. Namespaces

Els namespaces (espais de noms) proporcionen una manera d'agrupar els membres de nivell superior relacionats en una jerarquia. També s'utilitzen per evitar conflictes de noms. Un membre de nivell superior, com una classe, que no està inclòs en un espai de noms es diu que pertany a l'espai de noms predeterminat.

Es pot moure a un altre espai de noms si està tancat en un bloc d'espai de noms. Es pot utilitzar un espai de noms per organitzar elements de codi i per definir els propis espais de noms i utilitzar-los als programes.

Propietats dels namespaces:

- Organitzen grans projectes de codi.

- Estan delimitats mitjançant l'ús de l'operador .

- L'ús de la paraula clau indica que el programa està utilitzant un espai de noms donat.

- L'espai de noms global és l'espai de noms «arrel»: 1global::System sempre es referirà a l'espai de noms del sistema .NET.

- La convenció de noms per als espais de noms és la mateixa que per a les classes, amb cada paraula inicialment en majúscula.

- El marc de treball .NET utilitza espais de noms per organitzar les seves classes.

Exemple:

    using System; 
    namespace HelloWorldProject
    {
        public class HelloWorld
        {
            public static void Main()
            {
                int num;
                const string Msg = "Introdueix el teu nom: ";
                string name;
                Console.WriteLine(Msg);
                name = Console.ReadLine();
                Console.WriteLine("Hola, " + name + "!");
            }
        }
    }

#### 3.2.6 Estructures de control

##### 3.2.6.1. Estrures de control condicionals

**Exemple condicional múltiple**

    const string Msg = "Introdueix un número: ";
    const string MsgZero = "El número introduït és 0";
    const string MsgEven = "El número introduït és parell"; 
    const string MsgOdd = "El número introduït és senar";

    int num;
    Console.WriteLine(Msg);
    num = Convert.ToInt16(Console.ReadLine());
    if (num == 0)
    {
        Console.WriteLine(MsgZero);
    }
    else {
        if (num % 2 == 0) {
            Console.WriteLine(MsgEven);
        }
        else {
            Console.WriteLine(MsgOdd);
        }
    }

El fragment anterior es pot simplificar mitjançant l'operador condicional ternari:

    Console.WriteLine(num == 0 ? MsgZero : num % 2 == 0 ? MsgEven : MsgOdd);

A més de les estructures de control que ja havíem vist en la fase de disseny, C# (i altres llenguatges d'alt nivell) incorporen l'estructura condicional switch. La instrucció switch selecciona una llista d'instruccions per a executar-la en funció de la coincidència d'un patró amb una expressió de coincidència.
    
    const string Msg = "Introdueix el número del mes: ";

    int month;
    Console.WriteLine(Msg);
    month = Convert.ToInt16(Console.ReadLine());
    string montString;
    switch (month)
    {
        case 1:
            montString = "Gener";
            break;
        case 2:
            montString = "Febrer";
            break;
        case 3:
            montString = "Març";
            break;
        case 4:
            montString = "Abril";
            break;
        case 5:
            montString = "Maig";
            break;
        case 6:
            montString = "Juny";
            break;
        case 7:
            montString = "Juliol";
            break;
        case 8:
            Console.WriteLine("Agost");
            break;
        case 9:
            montString = "Setembre";
            break;
        case 10:
            Console.WriteLine("Octubre");
            break;
        case 11:
            montString = "Novembre";
            break;
        case 12:
            Console.WriteLine("Desembre");
            break;
        default:
            montString = "Número de mes incorrecte";
            break;
    }
    Console.WriteLine(monthString);

En el cas que la sentència switch retorni una variable, la seva estructura es pot refactoritzar (simplificar):

    const string Msg = "Introdueix el número del mes: ";
    
    int month;
    Console.WriteLine(Msg); 
    month = Convert.ToInt16(Console.ReadLine());
    string monthString = month switch
    {
        1 => "Gener",
        2 => "Febrer",
        3 => "Març",
        4 => "Abril",
        5 => "Maig",
        6 => "Juny",
        7 => "Juliol",
        8 => "Agost",
        9 => "Setembre",
        10 => "Octubre",
        11 => "Novembre",
        12 => "Desembre",
        _ => "Número de mes incorrecte",
    };
    Console.WriteLine(monthString);

##### 3.2.6.2. Estructures de control iteratives

while

    int num = 0;
    while (num < 5)
    {
        Console.WriteLine(num);
        num++;
    }

do (while)

    int num = 0;
    do
    {
        Console.WriteLine(num);
        num++;
    }while (num < 5);

for

    for (int i = 0; i < 5; i++)
    {
        Console.WriteLine(num);
    }

foreach

    int[] nums = { 1, 2, 3, 4, 5 };
    foreach (int num in nums)
    {
        Console.WriteLine(num);
    }

### 3.3. Execució de proves

Un pas important en la implementació d'un algorisme amb un llenguatge d'alt nivell és l'execució  de les proves. És a dir, cal elaborar els jocs de proves que cobreixin els casos més significatius, des dels valors esperats fins a aquells que ens poden donar errors.

L'IDE ens permet no només seguir el fluxe d'execució del programa segons les variables que li indiquem, sinó que també ens facilita l'avaluació de diferents expressions.

Per poder comprovar si el programa s'executa correctament (segueix el flux d'execució esperat) disposem de dues eines diferents:

- Traces

- Debugger

Les traces ens permeten saber de manera ràpida si s'està executant l'estructura de control esperada o quin valor s'està emmagatzemant en una variable. Simplement hem de mostrar un missatge per consola.

El debugger és una eina de depuració de codi, que ens permet inspeccionar les instruccions que conté el programa, així com avaluar les diferents expressions.

Per poder executar el debugger i accedir a les pestanyes Autos, Locals i Watch 1, cal que primer fixem un breakpoint (punt de ruptura). Un cop iniciat, la fletxa groga anirà marcant la línia que s'executa en aquell moment. Per avançar en l'execució, farem servir l'opció "Step over (F10)".

Les finestres Autos i Locals mostren valors variables mentre s'està depurant. Les finestres només estan disponibles durant una sessió de depuració. La finestra Autos mostra les variables utilitzades a la línia actual en la qual es troba el depurador i la línia anterior. La finestra Locals mostra les variables definides a l'àmbit local, que normalment és la funció o el mètode actual.

Dins la finestra Watch 1 podem observar les mateixes variables que a les anteriors i a més podem indicar expressions, de manera que sabrem si s'avaluen correctament.

### 3.4. Best practices

Les best practices (bones pràctiques) són un conjunt d'estàndards de codificació definits per a un llenguatge de programació en concret. Diferents llenguatges de programació segueixen uns estàndards similars, tot i que d’altres poden ser ben diferents.

Seguir les convencions de la comunitat de desenvolupadors del llenguatge en qüestió donarà com a resultat un codi amb menys errors, permetrà un millor manteniment d’aquest i garantirà la coherència de la codificació d’estils entre tots els equips.

Les convencions que se seguiran en aquest curs són les següents:

- Variables: fer servir noms descriptius, amb significat i en anglès, utilitzant la notació lowerCamelCase. NO afegir sufixos numèrics, ni notació HungarianCase ni guió baix (underscore). Triar sempre el tipus de dades més senzill.

- Comentaris: no utilitzar comentaris en línia per explicar el codi obvi. El codi ben escrit és autodocumentació.

- Control de fluxes: Si el bloc de control està format per diverses línies, sempre s'usen claudàtors ({}). L'operador condicional ternari només per a condicions trivials. Evitar avaluar les condicions booleanes contra «true» o «false».