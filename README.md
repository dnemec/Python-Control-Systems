# Analiza LTI sustava uz pomoć Pythona

Kao pomoć u analizi stabilnosti LTI sustava može poslužiti Python sa Sympy, Python Control Systems Library i Matplotlib knjižnicama.  

### Anaconda

Anaconda je Python distribucija namjenjena inžinjerima, znanstvenicima, fizičarima, matematičarima i statističarima.
U svom paketu dolazi sa više Python alata i knjižnica za simboličku i numeričku matematiku te grafičke prikaze.
Alati koji se koriste za automatiku i analizu LTI sustava su Spyder, Jupyter Notebook te knjižnice Sympy, Numpy te Matplotlib.
Također je moguće instalirati i ostale Python knjižnice, recimo Python Control Systems Library.

### Jupyter Notebook

Jupyter Notebook je interaktivna bilježnica s ugrađenim Python interpreterom te mogućnošću uređivanja teksta s Markdown jezikom.  
Jupyter Notebook je aplikacija koja se vrti u web pregledniku, npr. Chrome, Firefox. Moguće je instalirati ju na server ili lokalno, u ovom slučaju koristimo lokalnu inačicu.
Ovo omogućava jednostavno i estetski uredno vođenje bilježaka te rješavanja zadataka u Python interpreteru.  
Kod i tekst se unose u blokovima te se isto tako procesiraju u blokovima, blokove je moguće jednostavno i brzo kopirati s jednog mjesta na drugo no treba imati na umu da se kod procesira u interpreteru te je vrijeme izvršavanja svakog bloka bitno, kao i u standardnom interpreteru moramo paziti kojim redosljedom se naredbe izvršavaju.  
Uz pomoć Sympy knjižnice moguće je rezultate prikazivati u LaTeX formatu.

### Postupak analize

U ovom radu obraditi ću:  
* Metode manupulacije funkcija Sympy funkcijama.
* Rješavanje sustava jednadžbi za dobivanje prijenosne funkcije.
* Bodeov dijagram.
* Fazno i amplitudno osiguranje.
* Položaj polova i nula u Re-Im koordinatnom sustavu.
* Numeričko računanje odziva sustava na standardne funkcije.
* Analitičko utvrđivanje odziva sustava na standardne funkcije.
* Routhov kriterij stabilnosti.
* Područja stabilnosti sustava.
  
Sam postupak analize biti će pojašnjen u koracima.
