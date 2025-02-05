# ReferatTW

Accesibilitate în site-uri. 
Care sunt tehnologiile cele mai bune și mai des folosite pentru a face site-urile accesibile pentru oameni cu probleme de vedere. 
Istoric și trend-uri noi.

Într-o lume în care tehnologia se află într-o continuă evoluție, accesibilitatea în site-uri nu este doar o chestiune de responsabilitate socială, ci și o cerință legală și o oportunitate de afaceri, aceasta reprezentând un pilon esențial al dezvoltării digitale moderne, având ca scop asigurarea accesului egal la informații și servicii online pentru toți utilizatorii, inclusiv pentru persoanele cu dizabilități. În această lucrare îmi propun să explorez tehnologiile și practicile utilizate pentru a face site-urile web accesibile, punând accent pe persoanele cu probleme de vedere, analizând tendințele actuale și impactul acestora pe piața muncii, și oferind exemple practice de implementare.

Am ales această temă datorită creșterii importanței accesibilității web în contextul global. Conform Organizației Mondiale a Sănătății, peste 2,2 miliarde de persoane în lume au o formă de deficiență de vedere, iar accesibilitatea web devine esențială pentru incluziunea lor digitală prin reglementări, precum Directiva UE 2016/2102 și Americans with Disabilities Act (ADA), care impun obligativitatea respectării standardelor de accesibilitate. În plus, accesibilitatea web aduce beneficii economice, cum ar fi creșterea audienței, îmbunătățirea experienței utilizatorilor și reducerea riscurilor de litigii.
Accesibilitatea web a devenit o preocupare importantă odată cu dezvoltarea internetului, fiind formalizată la sfârșitul anilor ’90 prin inițiativa Web Accessibility Initiative (WAI) lansată de Consorțiul World Wide Web (W3C). Un moment crucial în această evoluție a fost publicarea, în 1999, a primei versiuni a Web Content Accessibility Guidelines (WCAG 1.0), care a stabilit principii fundamentale pentru crearea de conținut web accesibil. Standardele au fost ulterior îmbunătățite prin versiunile WCAG 2.0 (2008) și WCAG 2.1 (2018), iar WCAG 3.0, aflat în dezvoltare, promite să fie mai flexibil și mai adaptabil la tehnologiile emergente.
Pe lângă aceste inițiative internaționale, mai multe reglementări legislative au contribuit la promovarea accesibilității web. În Statele Unite, Section 508 din Legea Reabilitării(ADA) impune standarde stricte pentru site-urile guvernamentale, asigurând accesul persoanelor cu dizabilități la informațiile online. Iar în Uniunea Europeană, Directiva 2016/2102 a introdus obligația ca instituțiile publice să respecte standardele WCAG, consolidând astfel un cadru legal care încurajează incluziunea digitală. Aceste reglementări au avut un impact semnificativ asupra conștientizării și implementării principiilor de accesibilitate, contribuind la crearea unui mediu online mai echitabil pentru toți utilizatorii.
Accesibilitatea web se bazează pe patru principii esențiale, reunite sub acronimul POUR: Perceptibilitate, Operabilitate, Înțeles și Robusteză. Aceste principii garantează că informațiile și funcționalitățile unui site sunt accesibile unui spectru larg de utilizatori, inclusiv celor cu dizabilități. Printre tehnologiile esențiale utilizate în accesibilitate se numără HTML semantic, ARIA (Accessible Rich Internet Applications), utilizarea contrastului ridicat și a navigării prin tastatură.
În primul rând, perceptibilitatea presupune ca informațiile să fie prezentate într-un mod accesibil tuturor utilizatorilor, fie prin text alternativ pentru imagini, fie prin adaptarea conținutului pentru cititoarele de ecran. Operabilitatea asigură că interfața unui site poate fi navigată prin diverse metode, inclusiv tastatură sau ecrane tactile, oferind astfel accesibilitate și persoanelor cu dificultăți motorii. Un site trebuie să fie și ușor de înțeles, atât din punct de vedere al conținutului, cât și al funcționalităților, pentru a permite utilizatorilor să interacționeze eficient. În cele din urmă, robustez-ul asigură compatibilitatea conținutului web cu diferite dispozitive și tehnologii asistive, garantând o experiență de utilizare optimă.
Pentru a respecta aceste principii, dezvoltatorii web dispun de multiple tehnologii și instrumente menite să îmbunătățească accesibilitatea. Utilizarea unui HTML5 semantic corect, prin etichete precum <head>,<nav>,<main>,<footer>, contribuie la o structură clară și ușor de interpretat de către cititoarele de ecran. De asemenea, ARIA (Accessible Rich Internet Applications) furnizează atribute speciale care îmbunătățesc accesibilitatea elementelor interactive. Un alt aspect esențial este contrastul ridicat, care facilitează lizibilitatea textului pentru persoanele cu deficiențe de vedere. Totodată, suportul pentru navigarea prin tastatură este crucial pentru utilizatorii care nu pot folosi un mouse. În procesul de optimizare a accesibilității, dezvoltatorii pot folosi diverse instrumente de testare, cum ar fi Lighthouse (Google) și axe DevTools, pentru a verifica conformitatea cu standardele WCAG.
Exemple de implementare
1. HTML semantic și text alternativ pentru imagini:

2. Navigare prin tastatură:

3. Contrast ridicat utilizând CSS:

4. Utilizarea ARIA pentru elemente interactive:

5. Testarea accesibilității cu Lighthouse: Lighthouse este un instrument Google care permite auditarea accesibilității unui site web, oferind recomandări detaliate pentru îmbunătățirea conformității cu WCAG.

Comparație cu alte tehnologii
WCAG vs ARIA - WCAG se bazează pe etichete HTML standard, în timp ce ARIA permite identificatori personalizați pentru elementele interactive.


HTML5 semantic vs Bootstrap Accessibility - HTML5 semantic oferă o structură clară și îmbunătățește accesibilitatea implicit, în timp ce Bootstrap necesită configurare suplimentară pentru a fi accesibil.


Contrast ridicat vs Mod normal - Contrastul ridicat îmbunătățește lizibilitatea pentru utilizatorii cu deficiențe de vedere.

Comparație cu Alte Tehnologii

Tehnologie
Avantaje
Dezavantaje
WCAG
Standard global, aplicabil universal
Necesită implementare strictă
ARIA
Îmbunătățește accesibilitatea interfețelor dinamice
Complexitate în implementare
Bootstrap Accessibility
Componente predefinite accesibile
Dependență de framework
HTML5 Semantic
Îmbunătățește structura și accesibilitatea
Necesită cunoștințe avansate de dezvoltare

Nu în ultimul rând, accesibilitatea web a devenit un criteriu esențial în recrutarea dezvoltatorilor. Conform Google Trends, interesul pentru accesibilitate web a crescut semnificativ în ultimii cinci ani. Pe platforme precum LinkedIn și Indeed, numărul de locuri de muncă care solicită competențe în accesibilitate a crescut cu peste 50%. De asemenea, pachete precum axe-core și eslint-plugin-jsx-a11y sunt din ce în ce mai utilizate în proiectele open-source.
Coduri implementate pe https://github.com/ralucamog/ReferatTW.git

Bibliogafrie

Chisholm, Wendy, Gregg Vanderheiden, și Ian Jacobs. Web Content Accessibility Guidelines 1.0. W3C, 1999.
Deque Systems. axe DevTools.https://www.deque.com/axe/devtools/.
Google. Google Trends - Accesibilitate Web. https://trends.google.com.
Google Developers. Lighthouse.https://developers.google.com/web/tools/lighthouse.
Krug, Steve. Don’t Make Me Think: A Common Sense Approach to Web Usability. New Riders, 2014.
Mozilla Developer Network. ARIA.
https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA.
Paciello, Michael. Web Accessibility for People with Disabilities. CRC Press, 2000.
Slatin, John, și Sharron Rush. Maximum Accessibility: Making Your Web Site More Usable for Everyone. Addison-Wesley, 2002.
World Wide Web Consortium (W3C). Web Content Accessibility Guidelines (WCAG). https://www.w3.org/WAI/standards-guidelines/wcag/.

