
# 1. Replicazione del DNA

La replicazione del DNA è un processo molecolare che porta alla formazione di due molecole di DNA *identiche*.
La replicazione del DNA si definisce **semiconservativa**, poichè da una doppia elica madre si ottengono *due doppie eliche figlie* formate da un filamento di *neosintesi* (filamento nuovo) e da un filamento *madre* (filamento conservato).
Nella divisione cellulare a ciascuna delle due cellule figlie andrà una delle due copie di doppie eliche.

Al processo di duplicazione partecipano diversi enzimi e proteine. Gli enzimi fondamentali della replicazione sono:
1. **elicasi**  si muove lungo il DNA e separa i due filamenti rompendo i legami a idrogeno tra le basi complementari, formando la forcella di replicazione che è la zona in cui i due filamento si separano
2. **single-strand binding proteins (SSB)** si legano ai filamenti di DNA quando sono singoli e li mantengono separati.
3. **primasi** costruisce un piccolo frammento di RNA chiamato *primer* o *innesco* che permette alla DNA polimerasi di iniziare
4. **DNA polimerasi III** utilizza il filamento vecchio come stampo e aggiunge nucleotidi complementari per costruire il nuovo filamento in direzione $5'-3'$ (solo in questa direzione).
   Si hanno 
   Filamento 1:  5' ───────────── 3'
   Filamento 2:  3' ───────────── 5'
   Per il filamento 1 è necessario creare dei filamenti di Okazaki perchè il DNA polimerasi costruisce solo in direzione 5'-3'.
   
5. **DNA polimerasi I** rimuove i primer, li sostituisce con DNA  e effettua il proofreading cioè la correzione delle bozze per eliminare eventuali errori della DNA polimerasi III
6. **ligasi** unisce i vari frammenti di Okazaki 


La replicazione inizia in punti specifici chiamati **origini di replicazione**
Nei procarioti (es. Escheria Coli) è presente una sola origine di replicazione per cromosoma chiamata **OriC**
Negli eucarioti dato che i cromosomi sono molto più lunghi e complessi, esistono migliaia di origini di replicazione distribuite lungo il genoma.


## 1.1 Processo di replicazione degli eucarioti

La replicazione negli eucarioti è bidirezionale.
Da ogni origine di replicazione si formano due forcelle che avanzano in due direzioni opposte
**1.  Riconoscimento e attivazione dell'origine di replicazione** 
Il complesso **ORC** si lega all'origine indicando l'origine di replicazione.
ORC è formato da sei subunità, chiamate ORC1-ORC6.
Entrano in azione Cdc6 e Cdt1 che partecipano al caricamento sul DNA del complesso MCM2-7, che costituisce il core dell'elicasi. Questo processo avviene durante la fas G1 del ciclo cellulare.


**2.  Caricamento delle elicasi e formazione del complesso d'inizio**
Dopo aver caricato MCM2-7, la cellula deve assicurarsi che la replicazione avvenga una sola volta per ogni ciclo cellulare.
Durante G1 viene preparata l'origine.
Nella fase S avviene l'attivazione della replicazione quando il DNA viene effettivamente duplicato.
Nella fase S intervengono varie chinasi, tra cui le CDK, cioè chinasi ciclina-dipendenti.

*chinasi* $\rightarrow$ enzima che aggiunge un gruppo fosfato a una proteina, effettua quindi una fosforilazione.

La fosforilazione modifica l'attività delle proteine coinvolte nella replicazione. 


Per attivare l'elicasi, MCM2-7 si associa ad altre proteine **Cdc45** e **GINS**, formando il complesso **CMG**.

Il **CMG** costituisce l'elicasi replicativa attiva. Ora è possibile aprire il DNA e formare la forcella replicativa.

L'elicasi CMG separa i due filamenti del DNA, rompendo le interazioni (legami a idrogeno)  che mantengono appaiate le basi complementari e consumando ATP.
Per evitare che i singoli filamenti possano riappaiarsi o formare strutture secondarie, alle singolo filamento di DNA  si legano **RPA**, cioè *Replication Protein A*.
Nei batteri si parla di **SSB**
RPA stabilizzano i filamenti, impedenndo che i filamenti si riuniscano.



Quando il DNA polimerasi deve replicare ha necessità di una breve sequenza di RNA complementare al DNA dove partire chiamato **primer**.
Specialmente il DNA polimerasi ha bisogno di una piccola estremità libera **3'-OH** (carbonio 3 legato a un OH), quindi il primer termina con un 3'-OH.
Il primer viene costruito dall'enzima primasi.

Successivamente entra in azione il DNA polimerasi che è di 3 tipi ( $\alpha, \delta, ε$ ) che svolgono diverse funzioni

La DNA polimerasi $\alpha$ prende il primer RNA (creato dalla primasi) e aggiunge dei nucleotidi di DNA (brevi).
Il complesso primasi-DNA polimerasi $\alpha$ realizzano l'inizio della sintesi.

Una volta iniziata la sintesi intervengono il **DNA polimerasi ε** e **DNA polimerasi $\delta$**.

Il DNA polimerasi lavora solo in una direzione $5'-3'$ quindi si avranno due tipi di modalità per creare i due filamenti nuovi.

Il DNA ha una struttura:
```
Filamento 1: 3'-----5'
Filamento 2: 5'-----3'
```

Il DNA polimerasi ε sintetizza il **leading strand** che è il filamento nuovo continuo, quindi si leggerà con il filamento 1.
Il DNA polimerasi $\delta$ sintetizza invece il filamento complementare del filamento 2 dato che non possiamo avere una situazione:
```
Filamento 1:    3'-----5'
Leading strand: 5'-----3'

                    |--> frammenti di Okazaki
Lagging strand: ---   --- 
Filamento 2:    5'-----3'
```

La sintesi del leading strand avviene in maniera continua mentre quello del lagging strand invece crea dei Frammenti di Okazaki che è il tratto di DNA.

La DNA polimerasi $\delta$ quando arriva al frammento precedente, elimina il primer (RNA) precedente (quello che si trova davanti a quello che il pol $\delta$ sta sintetizzando) e lo rimpiazza con DNA.

Per rimuovere i primer intervengono RNasi H e FEN1.
- **RNasi H** riconosce l'RNA (primer) e lo rimuove
- **FEN1** elimina particolari strutture a flap che si formano durante la sostituzione del primer
Il vuoto lasciato dal RNA viene sostituito con i nucleotidi del DNA.
Tra i vari nucleotidi potrebbero comparire delle interruzione nello scheletro zucchero-fosfato chiamato **nick**.
Interviene il DNA ligasi che salda le interruzioni rimaste tra i frammenti, formando il legame fosfodiestere 

Il DNA polimerasi $\alpha$ non ha attività di correzione (proofeading), per questo il tratto di DNA che crea deve essere breve. 
Il DNA polimerasi $\delta \text{ e } \epsilon$  hanno l'attività proofeading che consiste nella correzione di nucleotidi inseriti in maniera errata, viene utilizzata l'attività **esonucleasica 3'-5'**.
Se l'ultimo nucleotide è sbagliato, la polimerasi lo rimuove andando verso il 3'-5' per poi ritornare alla direzione 5'-3' continuando la sintesi.

Errori non corretti possono portare a mutazioni permanenti oncogeniche.

Durante la sintetizzazione dei nucleotidi è necessario che il DNA rimanga ancorata nel filamento madre ed entra in azione il **PCNA** ( *Proliferating Cell Nuclera Antigen* ) che è una sliding clamp che forma un anello attorno al DNA e mantiene associata la DNA polimerasi al filamento.
![[Pasted image 20260929173221.png]]


Il PCNA viene caricato sul DNA da un complesso chiamato **RFC** (*Replication Factor C*).

Durante l'apertura della doppia elica, davanti alla forcella si accumula **tensione torsionale**. 
([DNA Topoisomerase | Topoisomerase I and II mechanism | Releasing the tension of DNA](https://www.youtube.com/watch?v=T06lo8T8Pmw))

In parole povere, continuando ad aprirsi la parte rimanente tende ad accumulare tensione fino ad arrivare a non poter piu aprire la doppia elica.
Per risolvere tale problema, vi è il **topoisomerasi** che effettua un taglio temporaneo del DNA, permettendo di eliminare una parte della tensione e poi richiude il DNA .

Esistono due tipi di **topoisomerasi**:
- **topoisomerasi I**: taglia un solo filamento di DNA e non consuma ATP.
- **topoisomerasi II**: taglia entrambi i filamenti e richiedono ATP.


### Replicazione DNA procarioti vs eucarioti

### Procarioti
Nei batteri come E. coli non si hanno diversi tipi di polimerasi ma solo polimerasi I e polimerasi III.
Polimerasi III sintetizza il nuovo DNA e pol I rimuove i primer e li sostituisce con DNA.
Succesivamente il DNA ligasi salda i frammenti.


### Eucarioti
Si hanno 
- pol $\alpha$
- pol $\delta$
- pol $\epsilon$
- RNasi 1 e FEN1
- ligasi I


## 1.2 Telomeri

I telomeri sono le regioni alle estremità dei cromosomi lineari.
Nell'uomo contengono molte ripetizioni della sequenza `5'-TTAGGG-3'` e vengono ripetute in tandem.
I telomeri hanno una funzione protettiva, quando avviene la replicazione del DNA i due filamenti si separano e la cellula potrebbe scambiare i filamenti come rottura del DNA ma i telomeri permettono di distinguere una normale estremità cromosomica da una vera lesione.

Le sue funzioni sono evitare:
- le estremità dei cromosomi vengano degradati
- cromosomi diversi si fondano tra loro
- vengono scambiati per danno del DNA


Come studiato precedentemente, i telomeri durante la divisone cellulare si accorciano. Infatti indicano il ciclo di vita della duplicazione cellulare. 

Il motivo per cui si accorciano è la sostituzione del primer nel lagging strand. 
Per inserire un DNA ha necessità di un primer ma se l'ultimo primer viene rimosso arrivati all'estremità del cromosoma, non ha più un estremità **3'-OH** e un tratto di DNA che permetta al normale DNA polimerasi di riempire quello spazio quindi quel tratto terminale non può essere copiato completamente nella replicazione.
Il risultato ha quindi un'estremità più corta.
A ogni duplicazione i telomeri si accorciano.
Questo problema viene chiamato **problema della replicazione delle estremità**

Però esiste un'enzima chiamato telomerasi che "risolve" questo problema.
Il telomerasi è un ribonucleoproteina cioè contiene sia proteine che componente di RNA:
- **TERT** $\rightarrow$  è la trascrittasi inversa (componente enzimatica) che da RNA sintetizza DNA
- **TERC** $\rightarrow$ è l'RNA che contiene la sequenza (serve come stampo)

La telomerasi si lega all'estremità **3' del DNA** che deve essere allungata.
Il suo TERC contiene una sequenza complementare a quella telomerica quindi funge da stampo per aggiungere nuove ripetizioni telomeriche al DNA.


**Funzionamento**
1. Si ha il DNA 
DNA:  5' ─────────────── TTAGGG 3'

2. La telomerasi ha al suo interno TERC = ACCU (complementare dell'ultima sequenza del DNA)
3. La telomerasi ha TERT che usa TERC per sintetizzare DNA usando TERC e viene aggiunta all'estremità del DNA (allungandolo)
PRIMA:
DNA ───────────── TTAGGG 3'

DOPO:
DNA ───────────── TTAGGG TTAGGG 3'
                         ↑
                  nuova sequenza aggiunta

4. Si avvia il complesso **primasi-Pol** $\alpha$ che crea un primer e aggiunge DNA complementare

Il telomerasi non impedisce la perdita di DNA ma previene l'accorciamento. 
Aggiungere nuove sequenze di DNA puà portare  a pensare che si modifichi il gene ma poiché queste sequenze sono ripetitive e non codificanti, l'allungamento del telomero non modifica direttamente i geni.

Nella maggior parte delle cellule somatiche adulte, l'attività telomerasica è molto bassa, portando alla **senescenza replicativa**.

Molte cellule tumorali riescono a riattivare il mantenimento dei telomeri, molto spesso attraverso la riattivazione di TERT, potendo permettere la proliferazione molto prolungata delle cellule tumorali.
La riattivazione della telomerasi è spesso associata all'attivazione del gene **hTERT**

#### Differenza fra cellule somatiche e tumorali

|**Caratteristica PNG**|**Cellule Somatiche PNG**|**Cellule Tumorali PNG**|
|---|---|---|
|**Attività telomerasica**|Assente o molto bassa|Elevata|
|**Accorciamento telomeri**|Presente ad ogni divisione|Assente (telomeri mantenuti)|
|**Capacità replicativa**|Limitata (20–60 divisioni)|Illimitata|
|**Espressione gene hTERT**|Spenta|Attiva|
|**Stato finale**|Senescenza replicativa|Proliferazione continua|
|**Contributo all'invecchiamento**|Principale|Assente|
|**Rischio trasformazione tumorale**|Basso|Molto alto|


---

# 2. Geni

Un gene è una regione di DNA che contiene l'informazione necessaria per produrre un prodotto funzionale:
- una proteina
- RNA funzionale come rRNA, tRNA, snRNA e altri RNA non codificanti

Inizialmente si pensava che il gene fosse un enzima, concetto proposto da Beadle e Tatum.
L'idea era che se un gene subisce una mutazione, ne impedisce il corretto funzionamento. 

Successivamente è nato una nuova idea dove il gene è una catena polipeptidica perchè una proteina può essere costituita da più catene polipeptidiche.

Un gene può essere definito in base a tre criteri principali:
- **Cistrone** è l'elemento base responsabile del trasferimento dell'informazione genetica dai genitori alla progenie.
- **Recon**
  E'  la più piccola regione di DNA in grado di separarsi e ricombinarsi tramite crossing-over durante la meiosi. La ricombinazione può avvenire all'interno del gene stesso
  ![[Pasted image 20260930105759.png]]
- **Muton**
  è l'elemento più piccolo di DNA la cui alterazione o sostituzione causa una mutazione genetica

## 2.1 Struttura del gene

### Procarioti

Un gene batterico è molto compatto, priva di sequenze interrotte (privi di introni).
I geni procarioti contengono solo regioni codificanti chiamati **esoni**.
Ogni gene contiene:
- sequenze regolatorie come il promotore e il terminatore
- codone di inizio, solitamente è AUG che avvia la sintesi proteica
- sequenza codificante, costituita da esoni disposti in sequenza continua.

La traduzione e la trascrizione sono strettamente accoppiate in quanto non è presente una membrana nucleare che , mentre l'mRNA viene sintetizzato, i ribosomi iniziano subito a tradurre il messaggio in proteine.


### Eucarioti

Oltre ai componenti simili ai procarioti, i geni includono anche:
- promotore e enhancers: sequenze che regolano l'inizio della trascrizione
- introni e esoni: Gli introni vengono rimosse durante il processo di slipicing e gli esoni vengono unite per formare l'mRNA maturo
- Sequenza 5' UTR e 3' UTR sono regioni non codificanti che regolano la traduzione e la stabilità dell'mRNA



## 2.2 Geni policistronici e monocistronici

#### Geni policistronici ( tipico dei Procarioti )

I geni policistronici sono tipici dei **procarioti** e di alcuni virus.
Nei procarioti, una stessa molecola di mRNA può contenere le informazioni necessarie per produrre più proteine.
Per esempio nel DNA sono presenti 3 geni che possono produrre 3 proteine. 
Per produrre le proteine il DNA non lo fa automaticamente ma prima trascrive queste informazioni in un mRNA.

Nel nostro caso invece di trascrivere 3 tipi mRNA, viene trascritto un solo mRNA.

Quando più geni sono organizzati nel DNA in modo da essere **regolati e trascritti insieme**, questa organizzazione prende il nome di **operone**.

La trascrizione è il processo in cui il DNA copia le informazioni del gene in un unico mRNA. 
I ribosomi leggono le 3 parti separatamente che si trova nel mRNA e producono 3 proteine da un unico mRNA.
L'mRNA si chiama **policistronico**, perchè contiene più cistroni.



#### Geni monocistronici ( tipico dei Eucarioti )

Negli eucarioti, ogni mRNA contiene l'informazione per produrre una sola proteina.
L'mRNA maturo possiede un solo sito di inizio e un solo codone di stop espresso per la traduzione della proteina specifica.
Però un gene eucariotico può comunque produrre proteine diverse grazie allo splicing alternativo.


---

# 3 Trascrizione nei Procarioti

Le cellule procarioti non hanno un nucleo delimitato da una membrana. Il DNA si trova in una regione del citoplasma chiamato nucleoide, quindi quando la RNA polimerasi sta trascrivendo un gene e produce l'mRNA, un ribosoma può tradurre quell'mRNA subito.

La regolazione trascrizionale nei procariorti è affidata a delle unità funzionali chiamati **operone**.
Un **operone** è un'organizzazione del DNA tipica dei procarioti nella quale più geni che svolgono funzioni correlate vengono regolati insieme.
L'operone è un segmento di DNA costituito da 3 regioni fondamentali:
**1. PROMOTORE**
è una sequenza di DNA che permette il legame con la RNA polimerasi per avviare la trascrizione.
**2. OPERATORE**
è una sequenza di DNA localizzata tra il promotore e i geni strutturali. Funziona da interruttore ed è il sito di legame per il repressore, una proteina codificata da un gene regolatore esterno o adiacente all'operone.
**3. GENI STRUTTURALI**
sono sequenze che codificano per le proteine del batterio.

Un esempio di operone è l'**operone lac**.

#### Operone lac

Il lattosio è uno zucchero che il batterio *E. coli*  può utilizzare come fonte di energia. Per poterlo utilizzare il batterio ha bisogno di alcun proteine come **β-galattosidasi**, **permeasi** e **transacetilasi**.
Il batterio potrebbe continuare  produrre queste proteine anche in assenza del lattosio quindi è necessario qualcuno che coordini la produzione, per questo eisste l'operone lac.
L'operone lac contiene al suo interno tre geni principali:
**lacZ → β-galattosidasi**  
**lacY → permeasi**  
**lacA → transacetilasi**

Queste tre geni sono diversi e producono diverse proteine ma sono tutti collegati allo sfruttamento del lattosio.

L'operone lac al suo interno contiene il promotore e operatore prima dei 3 geni. 
Il promotore è la regione dove la RNA polimerasi si lega e inizia la sintetizzazione del RNA. Mentre l'operatore si lega a una proteina chiamato **repressore**. Il repressore serve a reprimere cioè ridurre o impedire la trascrizione.

#### Assenza di lattosio
La cellula possiede il gene lacl, che produce il repressore. In assenza del lattosio il gene lacl si lega all'operatore, che ostacola il passaggio dell'RNA polimerasi verso i geni che devono essere trascritti. 

#### Presenza di lattosio
Una parte del lattosio viene trasformata in una molecola chiamata **allolattosio**. L'allolattosio è importante perché si lega al repressore.
Quando l'allolattosio si lega al repressore, **il repressore cambia forma**.

Questo cambiamento di forma è importante perché il repressore non riesce più a legarsi all'operatore nello stesso modo.

Quindi il repressore si stacca dall'operatore.
A questo punto viene eliminato il blocco.

L'allolattosio viene chiamato **induttore** dato che permette l'espressione dei geni che prima erano repressi.

Il batterio *E. coli* preferisce utilizzare il glucosio come fonte di energia, quindi prima di utilizzare il lattosio, il batterio si chiede prima se è presente molto glucosio, in quanto non conviene investire molte risorse nella produzione degli enzimi per utilizzare il lattosio.

Quando il glucosio è scarso, aumenta nella cellula una molecola chiamata **cAMP**.
Il cAMP può legarsi a una proteina **CAP**.
Quando cAMP si lega a CAP (proteina regolatrice), forma un complesso che può legarsi al DNA vicinio al promotore dell'operone lac.
Questo complesso aiuta la RNA polimerasi a lavorare più efficacemente sul promotore 



---

# 4 Trascrizione degli eucarioti

## 4.1 Promotori ed elementi regolativi in cis


Quando una cellula eucariotica deve produrre una proteina, deve prima trascrivere il gene, cioè utilizzare l'informazione contenuta nel DNA per produrre una molecola di RNA.
La RNA polimerasi II costruisce il pre-mRNA usando un filamento di DNA come stampo.

La RNA polimerasi per capire dove iniziare la trascrizione e quanto deve essere attivo quel gene, la cellula deve inviare segnali che lo indicano.
Questi segnali sono costituiti da particolari sequenze di DNA che regolano l'espressione di un gene e vengono chiamate **elementi regolatori in cis**.

Tra gli *elementi regolatori in cis* troviamo
- promotore 
- enhancer
- silencer
- insulator

A questi elementi si legano delle proteine prodotte dalla cellula chiamate **fattori in trans**. Per esempio, un fattore di trascrizione può riconoscere una determinata sequenza di DNA e legandosi ad essa, favorisce o ostacola la trascrizione.

I promotori sono sequenze di DNA che avviano la trascrizione dei geni e si trovamp all'inizio del gene.

Il punto preciso dove comincia la sintesi dell'RNA viene chiaamto **TSS** (*Transcription Start Site*).

All'interno di alcuni promotori eucariotici può essere presente una sequenza chiamata **TATA box**. 
Si chiama TATA box perché è ricca di adenina e timina e una sequenza di consenso tipica è **TATAAA**.
Si trova circa 25-30 nucleotidi prima del TSS.
Il TATA box aiuta la cellula a riconoscere e organizzare il promotore.

La TATA box viene riconosciuta da una proteina chiamata **TBP** ( *TATA-Binding Protein* ).
Il TBP è una proteina che si lega alla TATA box.

La TBP non lavora da sola, ma fa parte di un complesso più grande chiamato **TFIID**, che è uno dei fattori generali di trascrizione. 

I fattori generali di trascrizione sono proteine che aiutano a preparare tutto ciò che serve per iniziare la trascrizione da parte della RNA polimerasi II.

La RNA polimerasi II è l'enzima che sintetizza il pre-mRNA dei geni che codificano proteine, però non si posiziona automaticamente sul promotore.
Per questo sono necessari i vari fattori di trascrizione come TBP, TFIID, TATA-box e TSS che insieme al RNA polimerasi II formano il **complesso di pre-inizio** chiamato PIC ( *Pre-Initiation Complex* ).

Non tutti i geni hanno una TATA box, alcuni promotori eucariotici ne sono primi.

Per capire quanto attivamente trascrivere un gene, se ne occupano altre sequenze regolatrici.
Alcune di queste si trovano vicine al promotore e vengono chiamate **elementi del promotore prossimale**.
Gli elementi del promotore prossimale sono sequenze di DNA alle quali possono legarsi specifici fattori di trascrizione come la **GC box** e la **CAAT box**.

La GC box sono breve sequenza di DNA ricca di guanina e citosina, mentre la CAAT box è caratterizzata dalla presenza della sequenza CAAT.
Favoriscono la trascrizione ovvero aumentano la probabilità che il sistema di trascrizione si formi e che l'inizio della trascrizione avvenga e rendere più efficiente.
Il GC box può essere riconosciuto da specifici fattori di trascrizione come **SP1**.

Esistono poi sequenze regolatrici che possono trovarsi molto lontane dal promotore e sono gli **enhancer** e i **silencer**.

Un enhancer è una sequenza di DNA che può aumentare la trascrizione di un determinato gene.
All'enhancer si lega un proteina chiamata **attivatore** che è un fattore di trascrizione che favorisce l'espressione del gene.
Anche se l'enhancer potrebbe trovarsi dal gene, per via della struttura del DNA che può ripiegarsi nello spazio, può diventare fisicamente vicino al promotore. Questo ripiegamento viene chiamato **DNA looping**, cioè formazione di un'ansa del DNA.

La proteina attivatrice legata all'enhancer può interagire con le proteine presenti sul promotore direttamente o attraverso altri complessi proteici come il **Mediatore**.
L'enhancer aumenta la produzione di RNA.

Il silencer è una sequenza di DNA alla quale si legano le proteine chiamate **repressori**. 
Il silencer possono ostacolare la formazione o il funzionamento del complesso necessario alla trascrizione oppure favorire uno stato della cromatina meno favorevole alla trascrizione.

Gli insulator aiutano a creare dei confini tra diverse regioni regolatrici del genoma.
Dato che gli enhancer può agire anche a grande distanza, possono influenzare il promotore di un gene vicino che non dovrebbe essere attivato, per questo intervengono gli insulator.
Oltre alla creazione di confini, gli insulator partecipano anche alla separazione tra regioni di cromatina inattivo si propaghi verso una regione che deve rimanere attiva.
Una proteine associata ad alcuni insulator è la **CTCF**

*Sintesi*
Una regione del DNA che deve essere "accesa". Il **promotore** indica dove deve partire la trascrizione. La **TATA box**, quando presente, contribuisce al riconoscimento del promotore attraverso **TBP/TFIID**. I **fattori generali di trascrizione** permettono di assemblare il sistema di inizio e posizionare la **RNA polimerasi II**. Gli **enhancer** possono aumentare l'attività del gene attraverso gli **attivatori**, mentre i **silencer** possono ridurla attraverso i **repressori**. Gli **insulator** aiutano invece a mantenere correttamente separati i diversi sistemi regolatori.


## 4.2 Controllo dell'espressione genica 

*gene*  $\rightarrow$ produce RNA
*gene codificante*  $\rightarrow$  produce proteina

Una cellula eucariotica non deve produrre tutte le proteine continuamente e nella stessa quantità o negli stessi momenti.
Per questo l'espressione genica può essere controllata in diversi momenti del processo della sintetizzazione della proteina.

La sintetizzazione della proteina avviene in più fasi
$$\boxed{DNA \rightarrow \text{pre-mRNA } \rightarrow \text{ mRNA maturo } \rightarrow \text{ proteina } \rightarrow \text{ proteina modificata/ attiva}}$$

La cellula può intervenire in diversi punti e può decidere:
1. se trascrivere il gene $\rightarrow$ **controllo trascrizionale**
2. come modificare l'RNA prodotto $\rightarrow$ **post-trascrizionale**
3. se e quanto tradurre quell'mRNA $\rightarrow$  **traduzionale**
4. che cosa fare della proteina appena prodotta $\rightarrow$  **post-traduzionale**


#### 1) Controllo trascrizionale

E' il primo punto in cui la cellula può intervenire.
Se la cellula impedisce la trascrizione, non verrà prodotta l'mRNA e quindi neanche la proteina.
Nei batteri (cellula procariote) la trascrizione può essere regolata da repressore e attivatori (come operone Lacl).
Negli eucarioti il DNA è organizzato in maniera complessa sottoforma di cromatina, quindi il primo "ostacolo" è che l'RNA polimerasi possa accedere fisicamente al DNA.
Per farlo bisogna effettuare il rimodellamento della cromatina.
Una delle modificazioni che apre il DNA è l'**acetilazione degli istoni**, catalizzata dalle **HAT**, cioè 

*catalizzare*  $\rightarrow$ far avvenire una reazione chimica più velocemente

Aggiungere gruppi acetile agli istoni, riduce l'interazione tra istoni e DNA rendendo la cromatina più accessibile

La cromatina più compatta assume il nome di **eterocromatina** mentre quello meno condensata viene chiamato **eucromatina**.

Quando il DNA è sufficientemente accessibile, la cellula inizia la trascrizione utilizzando i fattori di trascrizione. (  vedi **2.4.1**  )


#### 2) Post-trascrizionale

Una volta terminata la trascrizione, la RNA polimerasi II ha prodotto un **pre-mRNA** non mRNA maturo.
Il pre-mRNA deve essere modificato e maturato prima di iniziare la sintesi della proteina. 
Per fare la maturazione dell'RNA vengono 
1. aggiunti un cappuccio all'estremità 5' chiamato 5'-cap e una coda di poli-A all'estremità 3'
2. gli introni vengono rimossi
3. gli esoni uniti attraverso lo splicing
Si forma mRNA maturo, che viene esportato dal nucleo al citoplasma e successivamente utilizzato dai ribosomi per produrre una proteina. 
Il 5'-cap è costituita da una 7-metilguanosina collegata all'RNA attraverso il legame 5'-5' trifosfato.
La coda poli-A è una coda costituita da molte adenine.
Quando gli esoni vengono uniti, ma non è detto che vengono uniti tutti gli stessi esoni.
```
Originale: esone 1 - introne 1 - esone 2 - introne 2 - esone 3 - introne 3

Splicing: esone 1 - esone 2 - esone 3
Splicing alternativo: 
esone1 - esone 3
esone1 - esone 2
esone2 - esone 3
```
Lo stesso gene può dare quindi origine a mRNA maturi differenti producendo diversi proteine differenti.

*Esempio*: immunoglobuline ***IgM***

#### 3) Traduzionale

Il controllo traduzionale controlla quanto spesso la cellula deve utilizzare l'mRNA maturo per produrre la proteina.
La traduzione avviene nel citoplasma attraverso i ribosomi.
I ribosomi leggono le informazioni contenute nell'mRNA e assemblano gli amminoacidi per formare una proteina.
I ribosomi per formare la proteina necessita di formare prima un complesso chiamato **fattori di inizio della traduzione**.

Questi fattori aiutano a preparare e assemblare i componenti necessari per avviare la traduzione, riducendo l'attività di alcuni fattori, diventa difficile avviare la traduzione.

Per sintetizzare proteine, la cellula utilizza energia e amminoacidi, ma se le risorse sono limitate o ambiente sfavorevole, si rischia di sprecare le risorse.

La cellula può attivare meccanismi che riducono temporaneamente la sintesi proteica.
Uno di questi meccanismi è la proteina **elF2** che svolge un ruolo importante nell'inizio della traduzione.
L'elF2 contribuisce a portare il tRNA inziatore.
Il tRNA è la molecola che trasporta gli amminoacidi e li mette a disposizione del ribosoma durante la costruzione della proteina.

Quando la cellula è sottoposta a determinati tipi di stress ( non può quindi produrre proteine in maniera continuata ), può attivare enzimi che aggiungono un gruppo fosfato a elF2, modificandone il funzionamento e diminuendo la sintesi proteica globale.

Non deve necessariamente fermare uno per uno tutti i ribosomi che stanno già lavorando ma può impedire o ridurre l'avvio di nuove traduzioni.
Non blocca tutti gli mRNA 




#### 4) Post-traduzionale

Il ribosoma ha gia prodotto una catena polipeptidica nel punto 3. 
Questa proteina potrebbe essere non funzionante.
La catena appena sintetizzata deve:
- ripiegarsi correttamente
- modificata chimicamente
- trasportata nella posizione corretta
- degradata se non serve più

$\boxed{\text{ FOLDING }}$
La proteina appena sintetizzata è una catena di amminoacidi perchè per funzionare deve avere una struttura 3D.
Il processo viene chiamato **folding**.
Per il folding intervengono chaperone e chaperonine (sono proteine) come **HSP60** ( chaperonina ) negli eucarioti che si trova nei mitocondri mentre nei batteri si hanno il sistema omologo **GroEL**

L'accumulo di proteine ripiegate male possono causare diverse patologie come malattie neurodegenerative

$\boxed{\text{ MODIFICAZIONI COVALENTI POST-TRADUZIONALI }}$
Le modifiche chimiche possono cambiare attività, stabilità, localizzazione o interazioni della proteina.
Esistono divere modifiche chimiche come 
- **fosforilazione**
  enzima chinasi aggiunge gruppo fosfato e fosfotasi lo rimuove
  
- **glicosilazione**
  aggiunta di catene di zucchero alla proteina. Possono influenzare stabilità, ripiegamento e riconoscimento 
  
- **acetilazione** 
  modificano proprietà e le interazioni della proteina o la sua posizione

- **acilazione** 
  modificano proprietà e le interazioni della proteina o la sua posizione


$\boxed{\text{ PROTEOLISI }}$

La proteina prodotta sotto forma di precursore che deve essere tagliata per diventare attiva, come l'insulina.
Viene inizialmente prodotta come preproinsulina, che viene poi modificata ottenendo proinsulina che viene successivamente sottoposta a taglio proteolitico per ottenere l'insulina.



$\boxed{\text{ PROTEIN TARGETING }}$

Le proteine una volta prodotte devono arrivare in posti diversi come nucleo, mitocondri, all'interno della membrana, fuori della cellula o rimanere nel citoplasma.


$\boxed{\text{ DEGRADAZIONE }}$

La cellula deve eliminare le proteine che sono:
- danneggiate
- mal ripiegate
- vecchie
- non servono

Per eliminare le proteine vengono utilizzate altre proteine come ubiquitina e proteasoma.
L'**ubiquitina** è una piccola proteina che può essere legata covalentemente alla proteina bersaglio.

Questa marcatura può funzionare come un segnale che indirizza la proteina verso il **proteasoma**.

Il proteasoma è un grande complesso proteico che riconosce le proteine marcate e le degrada in peptidi, permettendo poi il recupero degli amminoacidi.


## 4.3  Le Tre RNA Polimerasi ( I - II - III )

Nelle cellule eucariotiche esistono diversi RNA polimerasi che trascrive diversi RNA.
Esistono tre tipi di RNA polimerasi e si differenziano dal tipo di RNA prodotti:

**Pol I** → principalmente rRNA  
**Pol II** → mRNA e diversi RNA non codificanti  
**Pol III** → tRNA, rRNA 5S e alcuni piccoli RNA

Il ribosoma è formato da proteine + rRNA.
Per costruire il ribosoma servono $\text{ 18S, 5.8S, 28S 5S }$ 

### RNA polimerasi I

Lavora principalmente nel nucleolo, una regione del nucleo coinvolta nella produzione dei ribosomi. 

Produce un grande precursore chiamato **45S pre-rRNA**.  
Il precursore viene modificato e tagliato per ottenere 3 rRNA : 
- 18S
- 5.8S
- 28S

*S*  $\rightarrow$  unità Svedberg

Affinché **RNA polimerasi I** possa iniziare la trascrizione del **45S pre-rRNA**, deve essere posizionata correttamente sul DNA. Per stabilire dove deve iniziare la trascrizione è presente un **promotore**, cioè una regione di DNA che precede il tratto che verrà trascritto.

Il promotore della Pol I comprende principalmente due elementi: l'**UCE (Upstream Control Element)**, che si trova più a monte, e il **core promoter**, che si trova vicino al **punto di inizio della trascrizione**.

Per il riconoscimento e l'organizzazione del promotore intervengono diversi fattori. **UBF** si lega all'UCE, mentre **SL1** si associa al core promoter. Questi fattori contribuiscono a formare il complesso di inizio e a **reclutare e posizionare correttamente RNA polimerasi I**, permettendole di iniziare la trascrizione del gene che produce il **45S pre-rRNA**.




### RNA polimerasi II

La **RNA polimerasi II** si trova nel **nucleoplasma**, cioè nella parte del nucleo al di fuori del nucleolo.

La Pol II trascrive principalmente i geni che producono:

- **mRNA**, che verranno utilizzati per produrre proteine;
- diversi **RNA non codificanti**, come **lncRNA** e alcuni **miRNA**.

Per posizionare correttamente la **RNA polimerasi II sul promotore** sono necessari i **fattori generali di trascrizione**.

I principali fattori generali sono **TFIID, TFIIA, TFIIB, TFIIF, TFIIE e TFIIH**.

Il **TFIID** è formato da **TBP + TAF**.

In alcuni promotori eucariotici è presente una sequenza chiamata **TATA box**.

Alla TATA box si lega **TBP**, che fa parte di **TFIID**. In questo modo TFIID viene posizionato sul promotore.

Una volta che **TFIID** si è posizionato sul promotore, vengono reclutati gli altri **fattori generali di trascrizione** e la **RNA polimerasi II**.

L'insieme di questi componenti forma il **PIC (Pre-Initiation Complex, complesso di pre-inizio)**, che permette alla Pol II di iniziare correttamente la trascrizione.


### RNA polimerasi III

La pol III produce diversi proteine:
**tRNA** → porta gli amminoacidi al ribosoma  
**5S rRNA** → componente del ribosoma  
alcuni **snRNA**, come **U6** → coinvolti nello splicing

Normalmente i promotori si trovano all'inizio del gene ma nel Pol III i promotori si trovano all'interno della regione del gene che verrà trascritta e da lì organizzano il reclutamento della polimerasi.

Nei geni dei **tRNA** sono presenti elementi chiamati **Box A** e **Box B**.
I Box sono sequenze di DNA presenti all'interno del gene.
Il TFIIC riconosce e si lega alle Box A e Box B ma non posiziona il RNA pol III ma fa da intermediario e permette il reclutamento di TFIIIB.
**TFIIIB** viene quindi posizionato nella regione corretta e permette il corretto reclutamento e posizionamento della **RNA polimerasi III**, che può così iniziare la trascrizione.


## 4.4 Fattori generali di trascrizione

Per posizionare l'RNA polimerasi II sono necessari dei fattori generali di trascrizione.

I fattori di trascrizione sono:
- **TFIID** riconosce  e si lega la promotore, contribuisce a stabilizzare dove deve iniziare la trascrizione. E' composto da TBP e TAF
- **TFIIA** stabilisce il complesso formato da TFIIS e DNA, rendendo più stabile il legame con il promotore
- **TFIIB** contribuisce a posizionare correttamente la pol II rispetto al punto di inizio. Può riconoscere un elemento del promotore chiamato **BRE**.
- **TFIIF** si lega alla Pol II e favorisce l'arrivo del Pol II sul promotore.
- **TFIIE**  contribuisce al reclutamento e alla regolazione di TFIIH, preparando le condizioni per l'apertura del DNA
- **TFIIH**  contribuiscono all'apertura del DNA, utilizzando ATP e fosforila il CTD della Pol II, favorendo il passaggio dall'inizio all'allungamento.

I fattori generali permettono di costruire l'apparato di base ma non sono sufficienti da soli a spiegare come la cellula scelga quali geni trascrivere.
Per questo esistono gli attivatori, proteine che si legano a specifiche regolatorie.

Per esempio, una sequenza regolatoria può trovarsi in una regione chiamata enhancer. L'enhancer è una regione di DNA che può aumentare la trascrizione di un gene bersaglio grazie al legame di proteine regolatrici.

Quando un attivatore si lega a un enhancer, può favorire l'attività trascrizionale del gene bersaglio.

I fattori di trascrizione specifici sono proteine che riconoscono specifiche sequenze regolatorie del DNA e modulano la trascrizione di determinati geni.

Un esempio di fattore di trascrizione specifico sono gli ormoni steroidei.


#### Ormoni steroidei 

Gli ormoni steroidei sono lipofili, quindi possono attraversare la membrana plasmatica.
Una volta entrati nella cellula, incontrano il loro recettore.
Il recettore è una proteina che ha la capacità di riconoscere specifiche sequenze di DNA.
Quando l'ormone si lega al recettore, il recettore cambia conformazione e può attivare la regolazione della trascrizione.
In assenza di ormone, il recettore è mantenuto inattivo dal legame con proteine **chaperone** (come **Hsp70**, **Hsp90**, **Hsp56**).
Il legame con l'ormone provoca un cambio conformazionale che causa il **distacco delle chaperone**. Il complesso ormone-recettore dimerizza e si trasloca nel nucleo

#### Estrogeni
Gli estrogeni, come l'estradiolo, hanno due recettori: ERα ed ERβ.
Quando l'estradiolo entra nella cellula e si lega a uno di questi recettori, il recettore può regolare la trascrizione di determinati geni. 
ERα è importante nei tessuti della mammella e dell'utero. La sua attivazione favorisce l'espressione di geni coinvolti nella crescita e nella proliferazione cellulare. La proliferazione è il processo attraverso cui una cellula si divide, generando nuove cellule.

ERβ, invece, può regolare un insieme parzialmente diverso di geni. In alcuni tessuti e contesti cellulari, la sua attività è associata a una riduzione della proliferazione e a un aumento dell'apoptosi.
L'apoptosi è la morte cellulare programmata, un processo controllato attraverso cui la cellula attiva meccanismi che portano alla propria eliminazione.
Un dominio è una regione di una proteina che svolge una funzione specifica.
Il recettore degli estrogeni possiede diverse regioni funzionali:
- **DBD - DNA-Binding Domain**
  È la regione che permette al recettore di riconoscere e legarsi a specifiche sequenze del DNA. Nel caso del recettore degli estrogeni, queste sequenze si chiamano ERE (Estrogen Response Elements).
- **LBD- Ligand-Binding Domain**
  È la regione che lega il ligando, cioè la molecola che si lega al recettore. In questo caso, il ligando è un estrogeno, come l'estradiolo. Il legame può modificare la conformazione del recettore, favorendo la sua attività regolatoria.
- **AF — Activation Function.** 
  Indica una funzione di attivazione della trascrizione. Queste regioni contribuiscono a reclutare proteine regolatrici che favoriscono o modulano la trascrizione.

Ci sono quattro modalità attraverso cui il recettore degli estrogeni può produrre effetti cellulari.


**1.  Genomica ligando-dipendente**
L'estradiolo entra nella cellula e si lega al recettore degli estrogeni. Il legame provoca un cambiamento conformazionale che favorisce l'attività del recettore. I recettori estrogenici formano generalmente un dimero, cioè un complesso costituito da due molecole recettoriali.

Il dimero si lega a specifiche sequenze del DNA chiamate **ERE** attraverso il dominio DBD. A questo punto, il recettore può reclutare proteine regolatrici che aumentano o riducono la trascrizione dei geni bersaglio.

**2) Ligando-indipendente**
Il recettore può essere attivato o modulato anche senza che l'estrogeno si leghi a esso.
La cellula possiede altre vie di segnalazione, per esempio quelle attivate da fattori di crescita come EGF e IGF. Questi fattori si legano ai propri recettori e attivano una serie di reazioni intracellulari, che possono coinvolgere enzimi chiamati chinasi.

Le chinasi sono enzimi che aggiungono gruppi fosfato alle proteine: questo processo si chiama fosforilazione e può modificarne l'attività.
Se il recettore estrogenico viene fosforilato in regioni appropriate, la sua attività trascrizionale può essere modificata anche in assenza dell'ormone.



**3) ERE-indipendente**
Qui l'estrogeno si lega al recettore, ma il recettore non deve necessariamente legarsi direttamente a un ERE per regolare la trascrizione.
Può interagire con altri fattori di trascrizione già legati al DNA, come AP-1 o Sp1. Questi fattori riconoscono proprie sequenze regolatorie e si legano al DNA; il recettore estrogenico può interagire con loro e modificarne l'attività.



**4) ERE-indipendente**
Il recettore degli estrogeni attiva risposte cellulari rapide, attivando cascate di chinasi o flussi ionici citoplasmatici **senza modificare direttamente l'espressione genica**


Le alterazioni nella funzionalità o nell'espressione dei recettori steroidei sono alla base di numerose patologie ambientali e oncologiche:
- **Tumori Ormono-Dipendenti**: Es. carcinoma della mammella ($\text{ER}^+$) o carcinoma della prostata (recettore degli androgeni).
- **Disordini Metabolici e Cardiovascolari**.


## 4.5 Inizio, elongazione e terminazione della trascrizione

Il processo di trascrizione del DNA si compone di tre fasi:
**1.  Fase di inizio**
Il processo quando i fattori di trascrizione riconoscono e legano il sito promotore, permettendo l'aggancio del RNA polimeras, la quale una volta riconosciuto il sito promotore iniziale la sintetizzazione di una catena di nucleotidi.

**2)  Fase di allungamento**
La RNA pol sintetizza un trascritto di RNA, inserendo i ribonucleotidi in direzione **5'-3'**

**3)  Fase di terminazione**
Specifiche sequenze di DNA segnalano la fine della regione da trascrivere. Si arresta la polimerizzazione e avviene il distacco dell'enzima e dell'RNA, il quale prende il nome di trascritto primario.

---

# 5. Maturazione degli RNA
Le **modificazioni post-trascrizionali** dell'RNA sono quattro processi fondamentali che si verificano **esclusivamente all'interno del nucleo degli eucarioti** sul trascritto primario (pre-mRNA) prima del suo esporto nel citoplasma.

#### 1. Capping
All'inizio del pre-mRNA, cioè 5',  viene aggiunto un particolare nucleotide modificato chiamato CAP, costituito da 7-metilguanosina.
Ha la funzione:
- proteggere l'RNA dalla degradazione
- favorire la sua esportazione dal nucleo
- permettere il corretto riconoscimento dell'mRNA durante l'inizio della traduzione 

#### 2. Poliadenilazione
All'altra estremità ( 3' ) viene aggiunta una sequenza di adenine chiamata **coda poli-A**.
La sequenza **AAUAAA viene riconosciuta**, poi il pre-mRNA viene **tagliato poco più a valle**, cioè **dopo** AAUAAA.

A quel punto, la **poli(A) polimerasi aggiunge la coda di poli-A all'estremità 3' appena creata dal taglio**.

#### 3. Splicing
Il pre-mRNA contiene sia esoni che introni.
Gli introni devono essere rimossi, mentre gli esoni devono essere uniti.
Questo processo viene svolto dallo spliceosoma, un complesso formato da RNA e proteine.


#### 4. Splicing alternativo
Durante l'unione la cellula può unire alcuni esoni ed escluderne altri. 


## 5.1 Spliceosoma e snRNA

Lo **spliceosoma** è il complesso che si occupa di fare lo **splicing**, cioè eliminare gli introni dal pre-mRNA e unire gli esoni.

Non è una struttura fissa già pronta: si **assembla sul pre-mRNA** quando deve svolgere il suo lavoro.

Gli elementi principali dello spliceosoma sono gli **snRNA** (_small nuclear RNA_), piccoli RNA presenti nel nucleo. Questi RNA si associano a delle proteine e insieme formano le **snRNP** (_small nuclear ribonucleoproteins_).

Esistono diversi tipi di piccoli RNA nucleari (snRNA):
- **U1**
  arriva per primo e riconosce il sito di splicing 5', cioè il punto in cui inizia l'introne
  
- **U2** 
  riconosce invece il **branch point**, una particolare regione dell'introne che contiene un'**adenina** importante. Questa adenina parteciperà direttamente alla prima reazione chimica dello splicing.
  
- **U4**
  inizialmente è legato a **U6** e lo tiene temporaneamente inattivo. Quando lo spliceosoma è assemblato correttamente, U4 si allontana e permette a U6 di diventare attivo.
  
- **U6**
  insieme a **U2**, forma il principale **centro catalitico** dello spliceosoma, cioè la parte che permette che avvengano le reazioni chimiche dello splicing.
  
- **U5**
  ha soprattutto il compito di mantenere correttamente **allineate le estremità dei due esoni**, così che possano essere unite.


---

# 6 Ribosomi 

I **ribozimi** sono molecole di RNA dotate di **attività catalitica** autonoma, capaci di accelerare reazioni biochimiche senza l'intervento di enzimi proteici.

L'RNA può svolgere due funzioni importanti:
- può conservare o trasmettere informazione
- catalizzare reazioni chimiche

Solitamente il catalizzatore è un'enzima (proteina), quindi come fa i ribosomi ad esserlo ?
L'RNA possiede il gruppo **2'-OH** sul ribosio, che può partecipare ad alcune reazioni chimiche e tramite il ripiegamento permette di avvicinare gruppi chimici vicino nello spazio , creando un sito attivo.

*Esempi*  :
- **RNasi P** contiene una parte di RNA che riesce a tagliare un'estremità del tRNA durante la sua maturazione. Quindi l'RNA stesso svolge la funzione catalitica, aiutato da ioni Mg²⁺.
- **ribozimi hammerhead** sono RNA capaci di **tagliare RNA**. Il loro stesso gruppo **2'-OH** partecipa alla reazione e permette il taglio del legame fosfodiestere.
- **ribosoma** quando una cellula produce una proteina, il ribosoma deve unire gli amminoacidi attraverso il **legame peptidico**. Questa reazione viene catalizzata dall'**rRNA della subunità maggiore**, non dalle proteine ribosomali.
- **riboswitch** è una parte di RNA che **riconosce una piccola molecola** e, quando la lega, cambia forma. Questo cambiamento permette di **regolare l'espressione di un gene**, per esempio la trascrizione o la traduzione.


---

# 7. Editing del RNA

L'editing è un processo **post-trascrizionale** attraverso il quale la sequenza di un mRNA viene modificata dopo che l'mRNA è stato prodotto, senza modificare il DNA da cui era stato trascritto.
L'**editing A-to-I** è la conversione di una **adenosina (A)** in **inosina (I)**. Questa reazione è catalizzata dagli enzimi della famiglia **ADAR**, cioè _Adenosine Deaminase Acting on RNA_. L'inosina ha una caratteristica importante: durante la lettura dell'RNA viene interpretata dalla macchina cellulare in modo simile alla **guanina (G)**. Di conseguenza, una modifica A → I può cambiare il significato di un codone e quindi modificare la proteina prodotta.
Questo tipo di editing è particolarmente importante nel **sistema nervoso**, dove può contribuire a regolare proteine come alcuni **recettori e canali ionici**. In questo modo la cellula può modificare le caratteristiche delle proteine senza dover modificare il DNA.

L'editing **C-to-U** è la conversione di una **citidina/citosina in uridina (C → U)**. L'esempio classico è il gene dell'**apolipoproteina B, APOB**.

Il gene APOB è lo stesso sia nel fegato sia nell'intestino. La differenza nasce da ciò che succede al suo **mRNA**.

Nel **fegato**, in quel punto non avviene l'editing. Il codone rimane CAA.
CAA codifica per **glutammina**, quindi il ribosoma continua la traduzione. Viene prodotta la forma completa dell'apolipoproteina B, chiamata **ApoB100**, lunga **4536 amminoacidi**. ApoB100 è associata alle **VLDL** e alle **LDL**.
Nell'**intestino**, invece, una specifica **citidina deaminasi** modifica una C dell'mRNA trasformandola in U. Di conseguenza **CAA → UAA**
**UAA è un codone di STOP**.
Quando il ribosoma arriva a UAA, non inserisce un altro amminoacido, ma **termina la traduzione**. Per questo viene prodotta una versione molto più corta della proteina, chiamata **ApoB48**, di circa **2152 amminoacidi**. ApoB48 è importante per la formazione dei **chilomicroni**, che trasportano soprattutto i lipidi introdotti con la dieta.

L'editing dell'RNA ha anche un'importanza patologica e terapeutica. Alterazioni dei sistemi di editing sono state associate a diverse condizioni, comprese alcune **patologie neurologiche e tumorali**. Sono inoltre state sviluppate strategie sperimentali di **editing dell'RNA**, come **REPAIR** e **LEAPER**, con l'obiettivo di modificare un trascritto RNA senza modificare permanentemente il DNA. Il vantaggio concettuale è proprio questo: si interviene sull'**RNA**, quindi l'effetto può essere più transitorio rispetto a una modifica permanente del genoma.

---
# 8 Regolazione della stabilità del messaggero

La **stabilità dell'mRNA** indica quanto a lungo una molecola di mRNA rimane presente nella cellula prima di essere degradata. Questo è importante perché un mRNA presente nel citoplasma può essere utilizzato dai ribosomi per produrre una proteina. Quindi, se la cellula **mantiene a lungo un mRNA**, può produrre più proteina; se invece lo **degrada rapidamente**, la produzione di quella proteina diminuisce.

Per questo si parla di **emivita o half-life** dell'mRNA: è il tempo necessario affinché la quantità di quella molecola si riduca della metà. La cellula può quindi regolare la quantità di proteina prodotta anche semplicemente decidendo **quanto a lungo far sopravvivere l'mRNA**.

Per capire come viene degradato un mRNA, bisogna ricordare che possiede due caratteristiche protettive: il **CAP al 5'** e la **coda poli-A al 3'**.

La degradazione può quindi iniziare dalla coda poli-A. Questo processo si chiama **deadenilazione**, cioè la progressiva rimozione delle adenine dalla coda poli-A presente all'estremità 3'.

La deadenilazione viene svolta da complessi come **CCR4-NOT** e **PAN2/PAN3**. Quando la coda poli-A viene accorciata, diminuisce il legame con le **PABP**, cioè le proteine che si associano alla coda poli-A e contribuiscono alla stabilità dell'mRNA. Di conseguenza, l'mRNA diventa più vulnerabile alla degradazione.

A questo punto può avvenire il **decapping**, cioè la rimozione del CAP presente all'estremità 5'. Il complesso che partecipa a questo processo comprende **DCP1 e DCP2**; in particolare, **DCP2** è l'enzima che rimuove il cap.

Una volta eliminato il CAP, l'estremità 5' dell'mRNA rimane esposta. A questo punto può intervenire **XRN1**, un'esonucleasi che degrada l'RNA procedendo nella direzione: **5' → 3'**

L'mRNA può essere degradato nella direzione opposta, cioè: **3' → 5'**
In questo caso interviene l'**esosoma**, che è un complesso multiproteico con attività esonucleasica. In generale, quindi, l'mRNA può essere degradato sia attraverso una via **5'→3'** sia attraverso una via **3'→5'**.

La cellula possiede però anche sistemi che permettono di **colpire messaggeri specifici**. Uno dei più importanti è l'**RNA interference**, o **RNAi**.

L'RNA interference è un meccanismo attraverso il quale piccoli RNA non codificanti possono riconoscere determinati mRNA e ridurne l'espressione. In altre parole, invece di degradare casualmente un mRNA, la cellula può utilizzare un piccolo RNA come una sorta di **guida per individuare esattamente quale mRNA deve essere silenziato**.

I due protagonisti principali sono **miRNA** e **siRNA**.

I **microRNA (miRNA)** sono piccoli RNA di circa **21-25 nucleotidi**. Non vengono prodotti direttamente già nella loro forma finale. Inizialmente vengono trascritti come molecole più lunghe chiamate **pri-miRNA**.

Nel **nucleo**, il pri-miRNA viene elaborato dall'enzima **Drosha**, che lo trasforma in un precursore più corto. Questo precursore viene poi portato nel **citoplasma**, dove interviene **Dicer**, che lo taglia ulteriormente producendo il piccolo RNA maturo.

Il miRNA maturo viene poi associato a un complesso proteico chiamato **RISC**, cioè _RNA-induced silencing complex_.

Il miRNA contenuto nel RISC permette al complesso di trovare un mRNA che possiede una sequenza complementare. Il bersaglio dei miRNA si trova frequentemente nella regione **3'UTR** dell'mRNA, cioè la regione non tradotta presente dopo la sequenza codificante.

Quando RISC trova il suo mRNA bersaglio, può ridurne l'espressione principalmente in due modi.

Se la complementarietà tra miRNA e mRNA è **molto elevata**, il bersaglio può essere tagliato e degradato. Questo meccanismo è particolarmente tipico di molti sistemi vegetali.

Negli animali, invece, è frequente una **complementarietà parziale**. In questo caso il miRNA non deve necessariamente tagliare direttamente l'mRNA: può **inibire la traduzione** e favorire anche la **deadenilazione**, quindi l'accorciamento della coda poli-A e la successiva degradazione dell'mRNA.


I **siRNA**, invece, sono _small interfering RNA_. Anche loro sono piccoli RNA e vengono caricati nel complesso **RISC**, ma generalmente possiedono una **complementarietà molto elevata o quasi perfetta** con il loro mRNA bersaglio.

I siRNA possono derivare da **RNA a doppio filamento (dsRNA)**, per esempio RNA di origine virale oppure RNA prodotti sperimentalmente o presenti in determinati contesti cellulari. **Dicer** taglia il dsRNA producendo piccoli RNA, tra cui i siRNA, che vengono poi caricati nel RISC.

Quando il siRNA trova l'mRNA complementare, il complesso può determinare il **taglio dell'mRNA**, che viene poi degradato.

La cellula può utilizzare la regolazione della stabilità degli mRNA per modificare rapidamente la produzione di proteine durante lo **stress**, il **differenziamento** e altri cambiamenti cellulari. L'RNA interference è inoltre importante nella **difesa antivirale**, perché RNA a doppio filamento possono essere riconosciuti e utilizzati per indirizzare il silenziamento di RNA estranei.

Alterazioni dei sistemi dei miRNA e della loro regolazione sono state associate anche a diverse patologie, tra cui tumori, malattie neurodegenerative e alterazioni della risposta immunitaria.

La logica generale da ricordare è quindi:

La cellula può controllare quanta proteina produce non solo regolando la trascrizione, ma anche decidendo quanto a lungo sopravvive l'mRNA.





---

# 9 Sintesi delle proteine

La **traduzione** è il processo con cui la cellula usa l'informazione contenuta nell'**mRNA** per costruire una **proteina**.

- **Negli Eucarioti**: Avviene principalmente nel **citoplasma**, ma si verifica anche all'interno di **mitocondri e cloroplasti** (dotati di un proprio apparato traduzionale di tipo procariotico).
    
- **Nei Procarioti**: Mancando un involucro nucleare, la trascrizione e la traduzione avvengono **contemporaneamente** nello stesso compartimento citoplasmatico.


Nella cellula si trovano tre diversi tipi di RNA con funzioni diverse:
- **mRNA** = porta l'informazione dal DNA al ribosoma;
- **tRNA** = porta gli amminoacidi al ribosoma;
- **rRNA** = costituisce una parte fondamentale del ribosoma

L'mRNA contiene infatti una sequenza di **codoni**, cioè gruppi di tre nucleotidi. Ogni codone specifica (riconosce) un determinato amminoacido, oppure indica che la traduzione deve terminare.
Il ribosoma legge questi codoni e costruisce la proteina.
Il ribosoma è formato da due parti chiamate subunità minore e maggiore, che lavorano insieme durante la traduzione.
La subunità minore ha il compito di posizionare e leggere correttamente i codone e di verificare l'appaiamento tra il codone del mRNA e l'anticodone del tRNA.
La subunità maggiore invece contiene il centro catalitico che permette la formazione dei legami peptidici.

Il ribosoma non riconosce direttamente tutti gli amminoacidi e non li porta da solo, di questo se ne occupa il **tRNA**.

Il tRNA ha il compimento di portare un amminoacido al ribosoma.
Il ribosoma deve sapere quale amminoacido mettere in quale posizione, per questo il tRNA possiede una regione chiamata anticodone. 
L'anticodone è una sequenza di tre nucleotidi che può riconoscere un determinato codone dell'mRNA attraverso l'appaiamento complementare delle basi.
Il tRNA oltre ad avere l'anticodone ha anche un amminoacido specifico del codone complementare del suo anticodone. 

La traduzione viene divisa in tre fasi :
1. inizio
2. allungamento
3. terminazione


#### **1.  Inizio**

Negli eucarioti, l'mRNA possiede all'estremità 5' una struttura chiamata **cap**.
Il cap aiuta il ribosoma a riconoscere e reclutare l'mRNA per iniziare la traduzione. 

La subunità minore del ribosoma si lega all'mRNA e vi scorre per individuare il codone di inizio AUG, che indica il punto in cui deve iniziare la traduzione.

AUG codifica l'amminoacido metionina.

Quando viene individuato AUG, arriva tRNA iniziatore che porta la metionina e possiede l'anticodone complementare ad AUG, UAC.
Quindi il tRNA iniziatore si appaia con AUG e successivamente si associa la subunità maggiore del ribosoma.

La subunità maggiore del ribosoma possiede tre siti di legame in cui passano i tRNA:
**A → sito amminoacidico**  
**P → sito peptidilico**  
**E → sito di uscita**

Normalmente un nuovo tRNA entrerà nel sito A, ma il tRNA iniziatore viene posizionato direttamente nel sito P perchè la traduzione deve iniziare con il primo amminoacido ( metionina ) già posizionato correttamente per poter formare il legame con il secondo amminoacido.
Il tRNA iniziatore si trova nel sito P portando la metionina.
Il sito A rimane così libero per accogliere il tRNA successivo, che porta il secondo amminoacido.

*Spiegazione*: "un codone riconosce un amminoacido"
>Quando diciamo che un codone specifica un determinato amminoacido, intendiamo che quel codone viene riconosciuto dall'anticodone complementare di un tRNA, che è già legato all'amminoacido corrispondente. In questo modo il tRNA fa da collegamento tra il codone dell'mRNA e l'amminoacido che deve essere inserito nella proteina.
![[Pasted image 20261008111728.png]]


#### **2.  Allungamento**

L'mRNA contiene una serie di codoni. Una volta letto il primo codone, deve leggere il secondo
Per leggere si intende il controllo dell'appaiamento fra codone e anticodone.

Per esempio il secondo codone è **GCU**. 
Il secondo codone dell'mRNA, GCU, viene posizionato nel sito A del ribosoma. Un tRNA carico del relativo amminoacido arriva nel sito A e, attraverso il proprio anticodone complementare, si appaia con il codone GCU. L'appaiamento corretto permette al tRNA di essere correttamente posizionato nel sito A.

Successivamente i due amminoacidi devono unirsi e questo lavoro viene fatto dal ribosoma attraverso la sua attività peptidil-transferasica.
Specificamente viene svolta dal rRNA del subunità maggiore del ribosoma.
Quando si forma il legame, l'amminoacido legato al tRNA situato nel sito P, viene trasferito nel tRNA presente nel sito A.
Quindi
```
All'inzio dell'allungamento:
Sito P           Sito A
tRNA-Met         tRNA-Ala

Al termina dell'allungamento
Sito P           Sito A
tRNA           tRNA-Met-Ala
```

Il tRNA del sito A porta ora il dipeptide, cioè una catena formata da due amminoacidi.

Successivamente avviene la **traslocazione**.
Il ribosoma si sposta nel terzo codone e durante questo spostamento avvengono anche altri spostamenti:
- tRNA situato in P $\rightarrow$ sito E $\rightarrow$ esce dal ribosoma
- tRNA situato in A $\rightarrow$ sito P 
- sito A rimane libero
![[Pasted image 20261008111800.png]]

#### **3.  Terminazione**

La fase dell'allungamento continua fino a che non arriva un codone di stop.
I codoni di stop sono codoni che non specificano nessun amminoacido.
Ci sono due codoni di stop
- UGA
- UAA
Quando arriva uno dei due codoni di STOP nel sito A, arriva un fattore di rilascio.
Il fattore di rilascio riconosce il codone di stop e si lega al ribosoma.
Il fattore di rilascio provoca anche il distacco della catena polipeptidica del tRNA, la proteina appena sintetizzata viene rilasciata dal ribosoma.
Al termine avviene quindi:
- catena polipeptidica rilasciata
- tRNA liberato 
- le due subunità del ribosoma si separano
- l'mRNA viene liberato
![[Pasted image 20261008111828.png]]

Al termine della traduzione, la proteina sintetizzata non è detto che sia già funzionale. 
La cellula può modificare chimicamente questa catena. Queste modifiche possono essere:
- **Proteolisi** 
  Viene rimossa una parte della catena attraverso un taglio
- **Glicosilazione**
  Viene aggiunta zuccheri e la proteina prende il nome di *glicoproteina*. Hanno diversi scopi come riconoscimento cellulare, ripiegamento, stabilità o traffico della proteina.
- **Fosforilazione**
  Viene aggiunto un gruppo fosfato, processo catalizzato dagli enzimi chinasi. Può modificare la  conformazione e l'attività della proteina.


## 9.1    mRNA - rRNA  - tRNA

Per fare la traduzione, la cellula ha bisogno principalmente di mRNA, ribosomi, tRNA, amminoacidi e di diverse proteine chiamate fattori di traduzione.

\----------------------------------------------------
Quando un RNA viene trascritto, non è sempre pronto per svolgere la sua funzione. Può essere inizialmente prodotto come precursore che dopo diverse modifiche diventa RNA maturo o funzionale.
\---------------------------------------------------


$\boxed{\text{ mRNA}}$
L'**mRNA** contiene l'informazione genetica necessaria per costruire la proteina.

Questa informazione è organizzata in **codoni**, cioè triplette di nucleotidi. Il ribosoma legge questi codoni uno dopo l'altro e, attraverso i tRNA, determina quale amminoacido deve essere aggiunto alla catena polipeptidica.

Nei *procarioti* non avviene nessun processo di maturazione, per via della **traduzione co-trascrizionale**. Mentra si sta trascrivendo l'mRNA, è possibile iniziare già la sua traduzione.
Negli *eucarioti* RNA polimerasi II sintetizza pre-mRNA. 
Il pre-mRNA subisce tre modifiche per trasformarlo in mRNA maturo:
- capping al 5'
- splicing
- scissione della coda


$\boxed{\text{ Ribosoma / rRNA }}$
Il **ribosoma** è la struttura che realizza concretamente la traduzione.
È formato da **RNA ribosomiale (rRNA) e proteine**, per questo viene definito un complesso **ribonucleoproteico**.

Negli eucarioti è costituito da due subunità:
- **subunità minore 40S**
- **subunità maggiore 60S**

Quando si associano formano il ribosoma completo **80S**.
La subunità maggiore contiene 3 siti: sito A - sito P - sito E.

La stessa molecola di mRNA può essere tradotta contemporaneamente da più ribosomi che prendono il nome di **poliribosoma**.
Permette quindi più produzioni di una stessa proteina.

**Produzione**
Nei *procarioti* il precursore viene modificato attraverso:
- metilazione : aggiunta di gruppi metile
- scissione: tagli sul precursore

Negli eucarioti, la produzione degli rRNA avviene principalmente attraverso **due vie**.

La prima riguarda il grande **precursore 45S**. Questo viene trascritto nel **nucleolo** dall'**RNA polimerasi I**. Il 45S non è ancora costituito da rRNA maturi: è un unico grande RNA che deve essere modificato e tagliato.

Dopo la trascrizione, il precursore subisce **modificazioni chimiche**, come la metilazione e la pseudouridilazione, e successivamente viene sottoposto a specifici **tagli**. Da questo processo si ottengono tre rRNA maturi:
- **18S**, che entrerà nella subunità minore **40S**;
- **5.8S** e **28S**, che entreranno nella subunità maggiore **60S**.

La seconda via riguarda il **5S rRNA**. Questo è diverso dagli altri tre perché **non deriva dal precursore 45S**. Viene trascritto separatamente dall'**RNA polimerasi III**, nel nucleoplasma, cioè nella parte del nucleo al di fuori del nucleolo. Successivamente viene incorporato nella **subunità maggiore 60S**.

Le proteine ribosomiali, invece, vengono sintetizzate nel **citoplasma** e poi importate nel nucleo. Nel nucleolo, dove avviene gran parte della biogenesi dei ribosomi, si associano agli rRNA e contribuiscono alla formazione delle due subunità.

Le due subunità vengono poi **esportate separatamente nel citosol**.


$\boxed{\text{ tRNA }}$
Il **tRNA** è la molecola che fa da collegamento tra l'informazione contenuta nell'mRNA e l'amminoacido che deve essere inserito nella proteina.
Il tRNA è costituito da una parte un anticodone e dall'altra un amminoacido.
L'amminoacido è stato caricato dall'**amminoacil-tRNA sintetasi**.
All'estremità 3' del tRNA si trova la sequenza `3'-CCA-OH`
L'amminoacido si lega all'ultimo nucleotide, precisamente all'adenosina terminale, formando un legame estere.

Il tRNA possiede diverse regioni strutturali che contribuiscono al suo corretto riconoscimento e funzionamento.
Il **braccio D** prende il nome dalla presenza di **diidrouridina** e contribuisce alla struttura tridimensionale del tRNA e al riconoscimento da parte delle amminoacil-tRNA sintetasi.
Il **braccio TψC** contiene **timidina, pseudouridina e citidina** e contribuisce alle interazioni del tRNA con il ribosoma e con altri componenti della traduzione.
Esiste inoltre un **braccio/cappio variabile**, la cui dimensione può variare tra diversi tRNA.

**Produzione**
Nei procarioti il tRNA viene sottoposto a diversi processamenti per ottenere il tRNA funzionale:
- scissione al 5' e al 3'
- modificazioni delle basi
- aggiunta della CCA (dove viene legato l'amminoacido)
- splicing ( opzionale )

Negli eucarioti il pre-tRNA viene trascritto dalla RNA polimerasi III. 
Per ottenerlo funzionale deve subire modifiche:
- tagli alle estremità 5' e 3'
- modifiche chimiche di alcune basi
- aggiunta della CCA 
- splicing quando il tRNA contiene un introne

I tagli alle estremità 5' e 3' avvengono se sono presenti una sequenza aggiuntiva chiamata rispettivamente **leader** e **trailer** e tale operazione viene svolto dall'enzima (ribozima) RNasi P.
E' necessario aggiungere CCA alla fine ( se mancante ) perchè è con esso con cui si lega l'amminoacido.

Quando il tRNA è maturo, la sua struttura secondaria viene rappresentata come un trifoglio con:
- braccio accettore che lega l'amminoacido
- braccio anticodonico risconosce il codone
- bracci D e T$\Psi$C  che garantiscono che il tRNA sia caricato con l'amminoacido giusto e che il tRNA si sistemi correttamente sul ribosoma.


$\boxed{\text{ Fattori di traduzione }}$
I **fattori di traduzione** sono proteine che aiutano il corretto svolgimento della traduzione.

Non sono il ribosoma e non costituiscono la catena polipeptidica: **assistono il processo**.

Si distinguono in base alla fase in cui intervengono:
- **fattori di inizio** → aiutano a formare correttamente il complesso di inizio;
- **fattori di allungamento** → aiutano l'ingresso e il corretto posizionamento dei tRNA e i movimenti del ribosoma durante l'allungamento;
- **fattori di terminazione/rilascio** → intervengono quando compare un codone di stop e permettono il rilascio della catena polipeptidica.


$\boxed{\text{ Amminoacil-tRNA sintetasi }}$

L'amminoacil-tRNA sintetasi è un enzima che risconosce uno specifico tRNA e lo collega al suo specifico amminoacido.
Il risultato è un amminoacil-tRNA, cioè un tRNA a cui è stato legato il suo amminoacido. 
Questo processo avviene prima che il tRNA entri nel ribosoma. 

Le amminoacil-tRNA sintetasi sono specifiche: ogni sintetasi riconosce un determinato amminoacido e i tRNA corrispondenti. 

Deve quindi riconoscere due cose:

**1.  L'amminoacido corretto**
Riconosce le caratteristiche chimiche dell'amminoacido, compreso il suo gruppo laterale R.
(Gli amminoacidi differiscono per il gruppo R)

**2.  Il tRNA corretto**
L'enzima riconosce le caratteristiche strutturali del tRNA come sequenze e la sua struttura 3D.

L'amminoacil-tRNA sintetasi si occupa di legare il tRNA al suo amminoacido.
Questa operazione avviene in due reazioni consecutive:

**1)  Attivazione dell'amminoacido**
- l'amminoacido reagisce con ATP per rendere l'amminoacido reattivo, cioè pronto per essere trasferito sul tRNA
- Dalla reazione dell'amminoacido si forma un intermedio chiamato **amminoacil-AMP** e viene liberato **PPi** (*pirofosfato*)

**2)  Trasferimento dell'amminoacido sul tRNA**
- l'amminoacido viene trasferito sul tRNA
- viene poi legato all'estremità 3' del tRNA sulla sequenza CAA
- Da queste operazioni si ottengono un amminoacil-tRNA

Tra il tRNA e l'amminoacido si forma un legame estere ad alta energia. Questa alta energia viene usata per formare il legame peptidico tra gli amminoacidi durante la sintesi proteica.

Se durante l'operazione di legame fra l'amminoacido e il tRNA venisse legato l'amminoacido errato, esiste un meccanismo di editing ( controllo e correzione ) nel amminoacil-tRNA sintetasi.
Se si accorge che ha caricato l'amminoacido sbagliato, può idrolizzare il legame e rimuove l'amminoacido errato. Ciò avviene prima che il tRNA venga utilizzato nella traduzione


---

# 10   Ribosomi

I ribosomi sono un complesso **ribonucleoproteico**, in quanto è formato da due tipi di componenti :
- rRNA , cioè RNA ribosomiale
- proteine ribosomiali
Il ribosoma è la struttura cellulare che permette di trasformare l'informazione contenuta nell'mRNA in una catena polipeptidica.

Il ribosoma è costituito da due subunità: 
- **minore** 
  nei procarioti sono 30S e contiene rRNA 16S
  negli eucarioti sono 50S e contiene rRNA 18S
  
- **maggiore**
  nei procarioti sono 50S e contiene rRNA 23S e 5S
  negli eucarioti sono 60S e contiene rRNA 28S, 5.8S e 5S

In totale
- eucarioti: 80S
- procarioti: 70S

>S indica lo Svedberg cioè il coefficiente di sedementazione. 
>Indica quanto velocemente una particella sedimenta durante un processo di centrifugazione.


#### *Come si formano i ribosomi eucariotici?* 

Negli eucarioti il processo avviene nel nucleolo.
La RNA polimerasi I trascrive un precursore di rRNA chiamato **45S**.
Il precursore subisce poi delle modifiche, portando alla creazione di 18S, 5.8S e 28S, che costituiranno le subunità ribosomiali.
Però manca 5S, esso infatti viene prodotto dal RNA polimerasi III.
Queste 4 rRNA vengono poi modificati attraverso metilazioni, pseudouridilazioni.
Nel frattempo, le proteine ribosomiali vengono sintetizzate nel citoplasma e importate nel nucleo attraverso i pori nucleari.
Nel nucleolo le proteine ribosomiali si associano agli rRNA maturi e contribuiscono all'assemblaggio delle due subunità ribosomiali.

Le subunità ribosomiali vengono quindi esportate separatamente dal nucleo al citoplasma attraverso i pori nucleari. 
Nel citoplasma, durante l'inizio della traduzione, le due subunità si associano sull'mRNA, formando il ribosoma completo.

Il ribosoma contiene 3 siti: sito A - sito P - sito E.

***Ribosoma come catalizzatore***
Il ribosoma ha anche una funzione di catalizzatore, specialmente l'rRNA della subunità maggiore, infatti catalizza la formazione del legame peptidico.
Negli eucarioti è coinvolto soprattutto l'rRNA 28S, nei procarioti l'rRNA 23S.
Per questo il ribosoma viene definito anche ribozima.


Un ribosoma può trovarsi libero nel citosol o può essere temporaneamente associato alla membrana del reticolo endoplasmatica rugoso (RER).
La cellula deve capire dove deve essere mandata la proteina che sta venendo costruita.
Alcune proteine che devono essere mandate fuori dalla cellula, inserite nella membrana o inviate al sistema endomembranoso hanno al loro interno una sequenza di amminoacidi chiamata **sequenza segnale**.

Durante la traduzione del mRNA, se tra i primi amminoacidi compare la sequenza segnale, essa viene riconosciuta da una struttura chiamata **SRP** ( *Signal Recognition Particle* ).

La SRP si lega alla sequenza segnale e al complesso formato da ribosoma + mRNA + proteina.

La SRP permette di indirizzare questo complesso verso la membrana del reticolo endoplasmatico rugoso (RER).

Il complesso viene portato sulla membrana del RER, il ribosoma si associa a un traslocone, cioè un canale proteico presente nella membrana del reticolo endoplasmatico. 

La sintesi continua quindi nel reticolo endoplasmatico.

I **ribosomi liberi** producono principalmente proteine destinate a rimanere nel citosol o importate successivamente in organelli della cellula come nucleo o mitocondri.

Un **polisoma** è un insieme di ribosomi che traducono contemporaneamente lo stesso mRNA. Ogni ribosoma produce una propria copia della stessa proteina.

I **microsomi** sono strutture che si ottengono artificialmente in laboratorio quando le cellule vengono sottoposte a procedure di frazionamento cellulare.
Quando il reticolo endoplasmatico viene frammentato,  i suoi frammenti possono richiudersi formando piccole vescicole chiamate **microsomi**.
Se il reticolo è rugoso, possono conservare i ribosomi sulla loro superficie e vengono chiamati microsomi rugosi.


---

# 11  Codice gentico: codoni e anticodoni

Il codice genetico è l'insieme delle regole che stabiliscono la corrispondenza tra i codoni e gli amminoacidi che verranno inseriti nella proteina.

Nel RNA ci sono 4 basi: `A - U - C - G`
Ogni codone contiene 3 nucleotidi. Per ogni posizione $x_1, x_2, x_3$ si possono scegliere 4 basi quindi $4^3=64$.

Esistono quindi 64 codoni di cui 3 codoni STOP.
Si può pensare che quindi esistono 61 codoni corrispondenti a 61 amminoacidi ma esistono solo **20 amminoacidi**.

Il codice è degenerato, ridondante o universale.
- **degenerato**: Più codoni possono specificare lo stesso amminoacido 
- **ridondante** un codone non può specificare più amminoacidi.
- **universale** la corrispondenza tra codoni e amminoacidi è universale tra gli organismi tranne nei genomi mitocondriali
- **continuità** il codice viene letto in modo sequenziale e continuo

Esistono codoni speciali come:
 **AUG** specifica la metionina e codone di inizio
**UAA - UAG - UGA** codoni di STOP

Nei codoni esiste un fenomeno chiamato wobble.
Durante l'appaiamento tra il codone e l'anticodone, le prime due basi del codone devono appaiarsi in maniera molto preciso, mentre la terza base è più flessibile.
Per esempio se la terza base è una *guanina* ( G ) non deve necessariamente appaiarsi con una *citosina* ( C ) ma può appaiarsi anche con *uracile* ( U ) in certe determinate condizioni.
Quindi per questo un anticodone può legarsi a più codoni, quindi un amminoacido può essere riconosciuto da più codoni.

---
# 12 Le regioni non tradotte del mRNA

Durante la sintesi proteica i codoni del mRNA vengono tradotti in amminoacidi, ma non tutti i codoni vengono tradotti.
![[Pasted image 20261009100517.png]]
La zona proteine normalmente viene chiamata CDS ovvero Coding Sequence ed è la regione che contiene l'informazione utilizzata per determinare la sequenza degli amminoacidi. E' costituito dal codone di inizio e poi termina con codone di stop.

Prima del codone di inizio si trova **5' UTR** e dopo il codone di stop si trova **3' UTR**.
UTR significa *untranslated* cioè zona non tradotta e sono zone che non vengono utilizzati per aggiungere amminoacidi alla proteina.

Hanno lo scopo principale di contenere sempre informazioni, ma che servono ad aiutare la cellula a regolare quanto, quando e per quanto tempo una proteina deve essere prodotta.

#### 5' UTR
Regola l'efficienza dell'inizio della traduzione.
Quando la subunità minore del ribosoma viene reclutata nel mRNA, inizia a cerca AUG, il codone di inizio.  Prima di AUG troviamo 5' UTR.
Per iniziare la traduzione non basta la presenza di AUG, cioè appena si trova AUG si inizia la traduzione ma viene influenzato anche da una sequenza di nucleotidi chiamato **sequenza di Kozak**. 
La sequenza di Kozak viene spesso rappresentato come `gccRccAUGG`, dove R è purina cioè può essere adenina (A) o guanina (G).
La sequenza consenso permette di valutare se il contesto nucleotidico che circonda il codone AUG è favorevole o meno all'inizio della traduzione.
Se è favorevole, il ribosoma ha maggiori probabilità di iniziare la traduzione in quel punto di AUG, altrimenti il ribosoma oltrepassa quel AUG e potrebbe iniziare nel AUG successivo.

Quando avviene il secondo caso ovvero il ribosoma continua a scansionare alla ricerca di un nuovo AUG avviene il *leaking scanning*.
Se per esempio due ribosomi iniziano la traduzione in due punti di AUG differenti perchè è avvenuto il secondo caso, potrebbero produrre la stessa proteina ma destinati in compartimenti diversi, in quanto potrebbe avere una porzione iniziale diversa chiamata **estremità N-terminale** che serve a determinare la destinazione della stessa proteina.

Da ricordare che l'estremità N-terminale viene sintetizzato insieme alla proteina e fa parte della proteina. E' costituito dai amminoacidi della proteina.

Nei batteri quindi nei mRNA batterici sono presenti delle regioni iniziali che favoriscono il posizionamento del ribosoma vicino al codone di inizio chiamato **Shine-Dalgarno**.
Il shine Dalgarno si appaia con una regione complementare dell'rRNA 16S della subunità 60S.
Molti mRNA batterici sono policistronici, cioè contengono informazioni per produrre più proteine, per questo hanno diversi siti di inizio della traduzione.


#### 3' UTR

La 3' UTR aiuta la cellula a controllare la produzione della proteina.

Può regolare quanto lungo l'mRNA rimane nella cellula.
Un mRNA prima o poi verrà degradato e la 3' UTR contiene sequenze che possono essere riconosciute da proteine capaci di favorire oppure contrastare la degradazione dell'mRNA. Se viene degradato in poco tempo allora ciò limita la produzione delle proteine.

La 3' UTR contiene sequenze che possono essere riconosciute da proteine regolatrici e da piccoli RNA chiamati **microRNA ( miRNA)**.
I microRNA aiutano a regolare l'espressione dei geni.
Quando un microRNA riconosce una specifica sequenza del 3' UTR, si associa a un complesso di proteine chiamato RISC.
RISC può ridurre la produzione della proteina in due modi:
1. può ostacolare la traduzione dell'mRNA
2. può favorire la degradazione dell'mRNA
Quindi i microRNA può contribuire  a ridurre la quantità di proteine prodotte.

La 3' UTR contiene sequenze riconosciute da proteine che trasportano o trattengono l'mRNA in determinate zone della cellula.
E' utile in quanto se dall'mRNA viene prodotta una proteina che deve essere spostata in un determinato compartimento, l'mRNA viene spostato in quella zona e tradotto lì.


#### Coda poli-A

![[Pasted image 20261009105148.png]]

Dopo la regione 3' UTR si trova la coda poli-A formata da molte adenine.
La coda poli-A è legata da proteine come la PABP (*Poly(A)- Binding Protein* ) che servono a proteggere l'mRNA dalla degradazione e a favorire una traduzione efficiente. 

#### Nonsense-Mediated mRNA Decay ( NMD )

Normalmente durante la traduzione, il ribosoma si ferma appena legge il codone di stop, ma può capitare che una mutazione introduca un codone di stop prima della produzione completa della proteina.

La cellula possiede sistemi di controllo che possono riconoscere molti di questi mRNA e degradarli, evitando la produzione di proteine incomplete ( alcune volte dannose ).

La sintesi delle proteine avviene in due fasi:
- trascrizione
- traduzione
Durante la trascrizione si ha un pre-mRNA costituito da esoni e introni. 
Durante lo splicing, gli introni vengono eliminati e gli esoni uniti.
Nelle giunzioni tra esoni, la cellula deposita un complesso proteico chiamato **EJC** ( *Exon Junction Complex* ).
Gli EJC forniscono informazioni sul fatto che l'mRNA abbia subito correttamente lo splicing.

Quando il ribosoma scorre lungo l'mRNA (durante la traduzione ), rimuove gli EJC che incontra.

> [!info] Significato terminologia
> - *a monte* $\rightarrow$ prima del punto di riferimento
> - *a valle*  $\rightarrow$ dopo il punto di riferimento.
>
>![[Pasted image 20261009112423.png]]

In una condizione normale quando arriva al codone di stop, gli EJC a monte sono già stati rimossi.
Però se fosse presente un codone di stop prematuro, la traduzione si interrompe troppo presto e gli EJC a valle rimangono sull'mRNA.
Questi EJC possono contribuire a segnalare che la terminazione è avvenuta in una posiziona anomala.
La cellula attiva il sistema NMD che porta alla degradazione dell'mRNA.


#### Ricodifica traduzionale: il caso della selenocisteina

Normalmente, UGA è uno dei tre codoni di stop.
In alcuni mRNA però potrebbe essere interpretato come segnale per inserire la selenocisteina, un amminoacido contenente il selenio.
Però non basta la presenza di UGA, per inserire la selenocisteina, serve anche una struttura dell'RNA chiamata SECIS che si trova nel 3' UTR, insieme a fattori di traduzione e un tRNA caricato con slenocisteina.

Questo è un esempio con una regione non tradotta UTR possa influenzare la traduzione di una regione codificante.


---

# 13.   I fattori di inizio, allungamento e di terminazione nella traduzione
![[Pasted image 20261009121539.png]]


#### Inizio della traduzione

Il processo di traduzione inizia con il subunità minore 40S. 
Ad essa si associano diverse proteine chiamate **fattori di inizio eucariotici** ( *eIF* ).

Tra di essi troviamo *eIF2* che porta il tRNA iniziatore ( $tRNA_i^{\text{Met}}$ ).
eIF2 è legato a una molecola di *GTP* ( fornisce energia ).
L'associazione tra subunità minore e *eIF* porta alla formazione del complesso pre-iniziale 43S.

L'mRNA eucariotico maturo possiede un cap. Il cap viene riconosciuto da una proteina chiamata **eIF4E**, un fattore di inizio eucariotico.
eIF4E fa parte di un complesso proteico **eIF4F** insieme ad altri tre proteine:
- eIF4E che riconosce il cap
- eIF4G funziona da piattaforma e favorisce le interazioni tra diversi componenti dell'inizio
- eIF4A utilizza ATP per svolgere alcune strutture secondarie dell'mRNA, facilitando il lavoro del complesso di inizio

La cellula deve mettere in contatto il complesso 43S con l'mRNA per farlo interviene il eIF4G che può interagire con l'mRNA attraverso un altro complesso di proteina eIF4E che si trova insieme a lui nel eIF4F, e può interagire con il complesso 43S tramite un fattore di inizio trascrizione che si trova nel 43S ovvero eIF3.

Una volta che il complesso 43S è stato reclutato sull'mRNA vicino al cap, la subunità 40S può cominciare a scorrere lungo l'mRNA.
Questo processo si chiama scansione.
Durante la scansione, il complesso deve riconoscere il codone AUG e il tRNA iniziatore che era già nel complesso 43 si appaia al codone AUG attraverso il proprio anticodone.
Quando AUG viene riconosciuti correttamente, il complesso cambia configurazione.
Il GTP legato a eLF2 viene idrolizzato diventando GDP e fosfato inorganico, diversi eIF si staccano e la subunità maggiore 60S può associarsi alla subunità minore, formando il complesso 80S.
Il tRNA con metionina si trova nel sito P e il ribosoma è pronto per iniziare l'allungamento della proteina.

**Nei procarioti**
L'mRNA contine il Shine-Dalgo (una sequenza) che si appaia con una regione complementare dell'rRNA 16S (fa parte della subunità ribosomiale 30S).
L'appaiamento aiuta  a posizionare correttamente il ribosoma vicino al codone di inizio.


#### Allungamento
Negli eucarioti il fattore eEF1A legato a GTP accompagna il tRNA caricato verso il sito A.

Il ribosoma verifica se l'appaiamento tra codone e anticodone è sufficientemente corretto. 
Se è corretto favoriscono l'idrolisi del GTP e l'accettazione del tRNA nel sito A, altrimenti il tRNA viene respinto.

Il legame peptidico che si forma quando la catena polipeptidica situata nel sito P si trasferisce e si unisce nel sito A, viene catalizzata dal subunità maggiore, soprattutto 28S.
Questa attività catalitica viene chiamata **attività peptidil-transderasica**.

Dopo la formazione del legame peptidico, il ribosoma deve spostarsi al codone successivo dell'mRNA. Questo movimento è chiamato **traslocazione**.
Il fattore eEF2 utilizzando GTP, favorisce questo spostamento.

La traslocazione avviene finchè il ribosoma incontra un codone di stop.

#### Terminazione

I codoni di stop sono UAA, UAG e UGA.
Quando uno stop entra nel sito A, il ribosoma non può proseguire l'allungamento come al solito. Intervengono quindi i fattori di rilascio, che riconoscono il codone di stop e permettono di liberare la catena proteica.
Negli eucarioti, il fattore eRF1 riconosce i codoni di stop e si inserisce nel sito A.

eRF1 collabora con eRF3 legato a GTP, che favorisce una terminazione efficiente. Il processo porta all'idrolisi del legame che unisce la catena polipeptidica al tRNA nel sito P. La proteina appena sintetizzata viene così rilasciata.

Dopo il rilascio, il complesso ribosomiale deve essere smontato per poter essere riutilizzato. Negli eucarioti, il fattore ABCE1 contribuisce al riciclo del ribosoma, favorendo la separazione delle sue subunità e il recupero dei componenti.

# Controllo degli errori e qualità dell'mRNA

La cellula deve controllare non soltanto che la traduzione proceda correttamente, ma anche che gli mRNA utilizzati siano adatti a essere tradotti.

Nonsense-mediated decay (NMD): riconosce molti mRNA che contengono codoni di stop prematuri, come abbiamo visto parlando degli EJC. In questo modo può impedire la produzione di proteine incomplete.

No-go decay (NGD): interviene quando il ribosoma si blocca durante la traduzione, per esempio perché incontra una struttura difficile da superare o un problema nella sequenza dell'mRNA. Il sistema può favorire il recupero dei ribosomi bloccati e la degradazione dell'mRNA problematico.

Nonstop decay (NSD): riguarda gli mRNA che non possiedono un codone di stop funzionale. Il ribosoma può quindi arrivare alla fine dell'mRNA senza ricevere il normale segnale di terminazione. Il sistema contribuisce a gestire il ribosoma bloccato e a degradare l'mRNA anomalo.


### Regolazione della traduzione durante lo stress

La cellula non traduce sempre tutti gli mRNA alla stessa velocità. In condizioni di stress, come alcune situazioni di carenza di nutrienti o di stress del reticolo endoplasmatico, può ridurre la sintesi proteica generale per risparmiare risorse e adattarsi.

Un meccanismo importante coinvolge la fosforilazione di eIF2α, cioè l'aggiunta di un gruppo fosfato alla subunità alfa del fattore di inizio eIF2.

Normalmente, eIF2-GTP contribuisce a portare il tRNA iniziatore alla subunità piccola del ribosoma. Dopo l'inizio della traduzione, eIF2 deve essere riportato nella forma legata a GTP per essere riutilizzato. La fosforilazione di eIF2α inibisce il fattore eIF2B, necessario per questo riciclo. Di conseguenza, diminuisce la disponibilità di eIF2-GTP e si riduce l'inizio della traduzione di molti mRNA.

Tuttavia, non tutti gli mRNA vengono regolati allo stesso modo. Alcuni, tra cui quello che codifica per ATF4, possono essere tradotti più efficientemente in queste condizioni grazie a caratteristiche particolari della loro 5′ UTR.

ATF4 è una proteina che regola l'espressione di geni coinvolti nella risposta allo stress. La cellula, quindi, riduce la produzione proteica generale ma favorisce la sintesi di alcune proteine che la aiutano ad affrontare la situazione.

Questo è un esempio importante di regolazione: lo stress non spegne necessariamente tutta la traduzione, ma può cambiare quali proteine vengono prodotte.


---

# 14.  La maturazione delle proteine


## 14. 1 L'importanza del corretto ripiegamento delle proteine

Durante la traduzione si forma la catena polipeptidica, una sequenza di amminoacidi collegati tra loro da legami peptidici.
Durante la sintesi si forma la proteina assumendo una struttura primaria, quindi generalmente non è ancora pronta a svolgere la sua funzione biologica.
![[Pasted image 20261010160920.png]]
Questa struttura deve assumere una forma tridimensionale, la struttura primaria si piega in modi diversi.
Nelle proteine, il modo in cui la catena si ripiega determina quali parti entrano in contatto, quali interazioni si formano e quale forma assume la molecola. Questo processo si chiama il ***folding proteico***.

Il ***folding proteico*** è il ripiegamento della catena polipeptidica fino al raggiungimento di una conformazione 3D adatta alla sua funzione.

Il ripiegamento è utile perchè per esempio un enzima (una proteina) deve possedere una regione chiamata *sito attivo*. Se tale sito attivo non ha la conformazione corretta, l'enzima potrebbe perdere la sua attività.


Un biochimico **Christian Anfinsen** tramite i suoi esperimenti ha scoperto che la sequenza amminoacidica contiene l'informazione necessaria per determinare la struttura tridimensionale della proteina.
Ogni amminoacido possiede caratteristiche chimiche proprie. Alcuni sono idrofobici, cioè interagiscono poco con l'acqua, altri sono polari o carichi quindi possono interagire con l'acqua o con altre proteine.

La sequenza, attraverso le proprietà chimiche degli amminoacidi, determina quali conformazioni sono più favorevoli.

La proteina non si ripiega da solo ma molto spesso viene aiutato da un **chaperone**.
Il chaperone aiuta la proteina a raggiungere la conformazione corretta o impediscono che si ripieghi male.


La cellula è un ambiente prevalentemente acquoso, quindi influenza la conformazione delle proteien essendo che alcune amminoacidi sono idrofobi o idrofili.
Gli amminoacidi idrofobici tendono a disporsi lontano dall'acqua, quindi quando la catena si ripiega, molti di questi amminoacidi finiscono all'interno della proteina.
Gli amminoacidi idrofili rimangono invece esposti sulla superficie.
Questo processo viene chiamato **collasso idrofobico**.

Per stabilizzare la struttura finale intervengono anche altri legami oltre al collasso idrofobico :
- **legami a idrogeno** contribuisce a stabilizzare le strutture secondarie della proteina
- **interazioni elettrostatiche** 
- **forze di van der Waals**
- **interazioni idrofobiche** favoriscono la disposizione dei gruppi idrofobici lontano dall'acqua


Quando la catena comincia a ripiegarsi, alcune sue regioni possono organizzarsi in strutture regolari chiamate strutture secondarie.

*Strutture secondarie*  $\rightarrow$ alcuni tratti del filo si ripiegano formando forme regolari come l'$\alpha\text{- elica }$ e il $\text{foglietto-}\beta$ 

L'$\alpha\text{- elica }$ è una regione della catena avvolta a spirale. 
Il $\text{foglietto-}\beta$ è formato da segmenti della catena disposti uno accanto all'altro formando un foglio pieghettato come l'armonica.
Queste forme sono stabilizzate da legami a idrogeno tra i gruppi dello scheletro della catena polipeptidica.
![[Pasted image 20261010164507.png|200]] ![[Pasted image 20261010164700.png|50]]
La loro formazione contribuisce al ripiegamento complessivo.

#### Paradosso di Levinthal
Una proteina può assumere diverse conformazioni, per trovare quello giusto non deve provare tutte le possibili conformazioni.
La forma della proteina viene influenzata dalle interazioni chimiche che rendono alcune disposizioni più favorevoli di altre. 

Il folding, di conseguenza, segue **vie preferenziali**. Il processo avviene in passaggi intermedi  che restringono le possibili conformazioni. Durante il processo, si formano prima alcune strutture locali, come l’α-elica e il foglietto β. Queste strutture possono poi entrare in contatto tra loro, favorendo il ripiegamento dell'intera proteina.

Si dice che il processo è cooperativo perché la formazione di alcune interazioni facilita la formazione di altre, e gerarchico perché le strutture locali contribuiscono alla formazione della struttura tridimensionale complessiva.

Il folding avviene gradualmente, non necessariamente in un unico passaggio.

#### Molten globule

Durante il ripiegamento, la proteina può assumere una forma intermedia chiamata ***molten globule***. È già compatta e presenta alcune strutture secondarie, come α-eliche e foglietti β, ma non ha ancora raggiunto la disposizione tridimensionale definitiva.

Questi intermedi sono tappe normali del folding. Tuttavia, se il ripiegamento non procede correttamente, alcune regioni della proteina possono rimanere esposte e favorire l'aggregazione, cioè l'unione di più proteine tra loro.

#### Modifiche temperatura e pH: dentaurazione
La struttura della proteina dipende dalle interazioni che si formano tra le sue diverse regioni. Se cambiano le condizioni ambientali, queste interazioni possono essere alterate.

La temperatura, per esempio, influenza il movimento degli atomi e delle molecole. Temperature elevate possono destabilizzare la struttura nativa e portare alla denaturazione, cioè alla perdita della conformazione tridimensionale corretta.

Il pH misura quanto una soluzione è acida o basica. Se cambia, alcuni gruppi chimici degli amminoacidi possono acquistare o perdere protoni, modificando la loro carica elettrica. Di conseguenza, possono cambiare le interazioni elettrostatiche che contribuiscono alla stabilità della proteina.

Anche la forza ionica, cioè l'effetto complessivo degli ioni presenti nella soluzione, può influenzare le interazioni tra gruppi carichi. Infine, gli agenti denaturanti, come l'urea ad alte concentrazioni, possono interferire con le interazioni che mantengono la proteina ripiegata.

La denaturazione non comporta necessariamente la rottura dei legami peptidici: la sequenza primaria può rimanere intatta anche quando la struttura tridimensionale viene persa.

In alcuni casi, se si ripristinano le condizioni adatte, la proteina può ripiegarsi nuovamente. Questo fenomeno si chiama rinaturazione e mostra che l'informazione necessaria al ripiegamento può essere contenuta nella sequenza amminoacidica. Non tutte le proteine, però, riescono a rinaturare spontaneamente: durante la denaturazione possono aggregarsi o subire cambiamenti che impediscono il ritorno alla forma corretta.

#### Folding errato
Una proteina ripiegata male può esporre sulla superficie regioni idrofobiche che normalmente dovrebbero essere nascoste all'interno. Queste regioni possono interagire con regioni idrofobiche di altre proteine.

Se molte proteine stabiliscono queste interazioni tra loro, possono formare aggregati, cioè gruppi di proteine associate in maniera anomala. Alcuni aggregati sono poco solubili e possono accumularsi nella cellula; altri possono interferire con le normali funzioni cellulari ed essere tossici.

L'accumulo di proteine mal ripiegate è coinvolto in diverse malattie. Un esempio è la malattia di Alzheimer, nella quale si osservano aggregati proteici caratteristici.

#### Folding cotraduzionale
La catena polipeptidica emerge progressivamente dal ribosoma.
Quando una parte della catena è già uscita, può cominciare a formare interazioni e ad assumere una struttura locale, anche se il ribosoma non ha ancora finito di sintetizzare la proteina.

Questo fenomeno si chiama folding cotraduzionale: il ripiegamento comincia mentre la traduzione è ancora in corso.
Le regioni appena sintetizzate devono ripiegarsi in modo compatibile con quelle che emergeranno successivamente.
In questo processo possono intervenire le chaperon molecolari, proteine che aiutano altre proteine a ripiegarsi correttamente.
Non costruiscono la struttura finale ma aiutano piuttosto a evitare interazioni inappropriate e a favorire il raggiungimento della conformazione funzionale.

#### Ubiquitina- proteasoma
Le chaperon non riescono a correggere tutti gli errori. Per questo la cellula possiede anche sistemi di controllo della qualità delle proteine.

Se una proteina non raggiunge una conformazione corretta, può essere riconosciuta e indirizzata verso la degradazione, cioè la sua demolizione in componenti più piccoli.

Un sistema importante è la via ubiquitina-proteasoma.

L'ubiquitina è una piccola proteina che può essere legata ad altre proteine come segnale. Quando una proteina viene riconosciuta come destinata alla degradazione, può essere marcata con ubiquitina. Il proteasoma è un complesso molecolare che riconosce molte proteine marcate in questo modo e le degrada in frammenti peptidici.

In questo modo la cellula limita l'accumulo di proteine difettose, che altrimenti potrebbero aggregarsi o interferire con altri processi.

Non tutte le proteine mal ripiegate vengono necessariamente eliminate dal proteasoma.


## 14.2 Proteine Chaperon

Durante la produzione di proteine, esse possono ripiegarsi male o attaccarsi ad altre proteine formando aggregati.

Le chaperon sono proteine che aiutano altre proteine a ripiegarsi correttamente e impediscono che si aggreghino.

Esistono diversi tipi di chaperon:

**1.  Small Heat Shock Proteins (sHsp)**
Sono piccole chaperon che intervengono soprattutto quando la cellula è sottoposta a stress, come temperature elevate.
Quando una proteina comincia a perdere la sua forma, può esporre regioni idrofobiche che normalmente dovrebbe rimanere nascoste.
Le sHsp si legano a queste proteine e impediscono che si attacchino tra loro.
Si chiama *holdasi* perchè le trattengono temporaneamente in uno stato recuperabile. Non consumano ATP per svolgere questa funzione.

**2.  Famiglia Hsp70**
Queste chaperon aiutano le proteine a raggiungere una conformazione corretta. Si legano a regioni della catena polipeptidica che potrebbero causare aggregazione e utilizzano l'energia dell'ATP per regolare il legame e il rilascio della proteina.
Favoriscono il ripiegamento corretto.

**3.  CIpB**
Alcune proteine si possono aggregarsi tra loro.
CIpB è una disaggregasi, utilizza energia per separare le proteine dagli aggregati, rendendole nuovamente accessibili ad altri sistemi di chaperon, che possono aiutarle a ripiegarsi.

**4.  Hsp33  e Hsp31**
Sono chaperone coinvolte nella risposta a condizioni di stress, soprattutto quando le proteine rischiano di perdere la loro conformazione.
Hsp33 viene attivata in condizioni di stress ossidativo, alcune modificazioni chimiche della proteina ne cambiano la struttura, permettendole di proteggere altre proteine dall'aggregazione.

**5.  Chaperonine**
Le chaperonine, come GroEL e GroES nei batteri, formano una struttura simile a una gabbia. Una proteina che deve ripiegarsi viene temporaneamente racchiusa al suo interno, dove può organizzarsi senza entrare in contatto con altre proteine che potrebbero causarne l'aggregazione.



Le chaperone oltre al folding hanno anche altre funzioni:
- **protezione dall'apoptosi**:
  possono interferire con passaggi che portano alla morte cellulare programmata.
  *Esempio*: Hsp27 e αB-cristallina
  
- **trasparenza del cristallino**:
  aiutano ad impedire l'aggregazione delle proteine del cristallino
  *Esempio*: αB-cristallina
  
- **chaperonopatie**:
  sono patologie associate a difetti delle chaperon o dei sistemi di controllo del ripiegamento proteico.
  Possono derivare da mutazioni genetiche o da alterazioni che compromettono la loro funzione.


## 14.3  Gli errori di ripiegamento

Se il ripiegamento delle proteine è scorretto, possono esserci alcuni amminoacidi idrofobici esposti all'acqua. 
Queste proteine possono attaccarsi tra loro, formando degli aggregati.
Alcuni aggregati sono costituiti da strutture allungate chiamate **fibrille amiloidi**, dove le proteine assumono una particolare organizzazione ricca di foglietti beta.
Gli aggregati possono interferire con altre attività cellulari.

Il danno può avvenire in diversi modi.
Alcuni aggregati piccolo chiamati **oligomeri** possono interferire con le *membrane cellulari*, alterando il funzionamento delle strutture che regolano gli scambi con l'ambiente.


Le proteine aggregate  possono intrappolare altre proteine, impedendo loro di svolgere la propria funzione. La cellula deve spendere risorse per cercare di eliminare il materiale anomalo. 
Se l'accumulo diventa eccessivo, i sistemi di controllo possono non riuscire più a gestirlo.

L'**URP** *Unfolded Protein Response* è la risposta alle proteine non correttamente ripiegate.
Molte proteine vengono sintetizzate nel reticolo endoplasmatico, se molte proteine mal ripiegate si accumulano troppe proteine, la cellula attiva la URP.
La URP cerca di ristabilire l'equilibrio riducendo temporaneamente la produzione di nuove proteine, aumentando la capacità di ripiegamento e favorendo l'eliminazione di quelle difettose.
Se il problema persiste e il danno diventa troppo grande, la cellula può attivare l'apoptosi. 

Il mal ripiegamento viene chiamato ***misfolding***.

Il misfolding può causare diverse malattie:
- **Alzheimer**
  depositi extracellulari di beta-amiloide e accumuli intracellulari della proteina *tau alterata*.
  
- **Parkinson**
  accumulo di alfa-sinucleina
  
- **Sclerosi laterale amiotrofica ( SLA )**
  
- **Corea di Huntington**
  un espansione di triplette CAG nel gene HTT che produce proteina huntingtina con una sequenza lunga di glutammine, che favorisce alterazioni e aggregazione.
  
- **Amiloidosi**
  formazione di fibrille amiloidi che si depositano nei tessuti.

La cellula per difendersi utilizza meccanismi come chaperon, proteasoma, autofagia.

---
---
# 15. Regolazione dell'attività biologica delle proteine

Le proteine non devono rimanere nella cellula per sempre, quindi avviene la **degradazione proteica**.
La degradazione proteica è il processo attraverso cui una proteina viene demolita in frammenti più piccoli, fino ad ottenere peptidi e successivamente amminoacidi.
$$\boxed{\text{ Proteine} \rightarrow \text{peptidi} \rightarrow \text{amminoacidi } }$$
Gli amminoacidi possono essere riutilizzati per sintetizzare nuove proteine oppure essere utilizzati nel metabolismo.

La degradazione proteica serve per rinnovare le proteine cellulare quindi eliminare e sintetizzare nuove proteine.

La cellula utilizza due sistemi per smaltire le proteine.

##### 1.  **Sistema ubiquitina-proteasoma**
Una proteina **ubiquitina** contrassegna le proteine da eliminare. Il sistema riconosce queste proteine da eliminare.
Elimina *singole* proteine
L'ubiquitina è una piccola proteina formata da 76 amminoacidi. Si lega alla proteina da degradare, rappresenta un indicatore che quella proteina deve essere riconosciuta dal sistema.
La cellula utilizzare tre enzimi (`E1  E2  E3` ), che accelerano una reazione chimica, per applicare l'ubiquitina alla proteina.
- **E1** è l'enzima ***attivante*** ed utilizza energia derivata dall'ATP per attivare l'ubiquitina. rendendola pronta per essere trasferita.
- **E2** è l'enzima ***coniugante*** e riceve l'ubiquitina attivata e la trasporta nella fase successiva della reazione.
- **E3** è l'***ubiquitina ligasi*** e riconosce la proteina bersaglio e favorisce il trasferimento dell'ubiquitina su di essa
Alla prima ubiquitina che si è attaccata alla proteina bersaglio, si attaccano altre ubiquitine attraverso **K48** formando una **catena di poliubiquitina**.
L'ubiquitina possiede alcuni amminoacidi chiamati lisine, una di queste lisina si trova nell'amminoacido 48. Quando due ubiquitine si legano, il gruppo amminico della lisina 48 del primo ubiquitina forma un legame con il gruppo carbossilico terminale della seconda ubiquitina.
Una volta che la proteina è stata contrassegnata con la catena di ubiquitina, può essere riconosciuta dal **proteasoma 26S**, un grande complesso molecolare che la degrada.
Il **proteasoma 26S** è formato da due componenti principali:
- il core catalitico 20S
- una o due particelle regolatrici 19S

**Processo**
**1.**   La particella 19S riconosce la proteina contrassegnata con ubiquitina
**2.**   Le ubiquitine vengono rimosse per essere riutilizzate.
**3.**   La particella 19S utilizza poi l'energia dell'ATP per srotolare la proteina affinché possa entrare nel core 20S
**4.**   All'interno del core 20S si trovano **proteasi** (enzimi) che tagliano la catena polipeptidica in frammenti più piccoli.
**5.**  Questi frammenti vengono degradati in amminoacidi.

Il core 20S è formato da quattro anelli sovrapposti:
- due anelli esterni di tipo $\alpha$
- due anelli interni di tipo $\beta$ che possiedono *attività proteolitica*, cioè sono capaci di tagliare i legami peptidici.
![[Pasted image 20261011101333.png|300]]


##### 2. **Autofagia**
L'autofagia permette di portare materiale cellulare (es. aggregati proteici) in compartimenti contenenti enzimi digestivi, chiamati ***lisomi***. 
Elimina *aggregati di proteine* o *materiali cellulari grandi*.

### UBL

L'**UBL** sono proteina simili all'ubiquitina che si legano a proteina bersaglio per modificarne il comportamento.
L'UBL si dividono in diversi tipi:  
- **SUMO**
  modifica le proteine influenzandone la posizione nel nucleo, l'attività e la regolazione della trascrizione.
  
- **NEDD8**
  modifica le proteine chiamate *culline* e regola l'attività di sistemi coinvolti nel controllo del ciclo cellulare
  
- **ISG15**
  partecipa alla risposta antivirale e viene prodotta in quantità maggiori in risposta agli interferoni che sono molecole coinvolte nella risposta immunitaria
  
- **FAT10**
  indirizza alcune proteine verso la degradazione proteasomica

