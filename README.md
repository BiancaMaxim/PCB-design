# PCB-design
Cerințe: se realizează schema electrică și proiectul de cablaj conform specificațiilor cerute

1. Capture:

a) Schema electrică a circuitului prezentat se va realiza utilizând pachetul de programe Orcad 9.2

b) Se va realiza un bloc ierarhic corespunzător blocului de comandă (microcontroler). Toate celelalte circuite vor fi pe nivelul superior.

c) Pentru realizarea schemei electrice sunt utilizate simbolurile din librăriile sistemului de proiectare, cu excepția:
    - În locul celor trei optocuploare se vor folosi două simboluri multi-part;
    - Pentru stabilizatoarele de tensiune (LM78L05) din schema electrică se va crea un simbol single-part (UA78L05-SOT89).

d) după finalizarea editării schemei electrice, se va verifica corectitudinea legăturilor electrice.

e) se va genera lista de materiale.
    
2. Layout:
      
    a) Pentru conectorul de alimentare se va crea o amprentă de cablaj THD
    
    b) Pentru microcontroller-ul ATTiny 2313 se va crea o amprentă de cablaj, SMD
    
    c) Pentru driverul MAX 485, se va crea o amprentă de cablaj, SMD
    
    e) Forma și dimensiunea plachetei electronice: dreptunghiulară, 170 x 120 (Lxl) mm.
    
    f) Conectorii vor fi plasați întotdeauna la marginea plachetei. Modul de amplasare trebuie să respecte: blocul funcțional din care face parte, poziția în raport de acesta și ușurarea procedurii de rutare (trasee cât mai scurte și mai drepte).
    
    g) Placa are 4 găuri de prindere, in fiecare dintre cele 4 colțuri ale plachetei, potrivite pentru șuruburi M4.
    
    h) Rutarea plachetei – 4 straturi electrice: TOP, INNER1 (ground), INNER2 (alimentare),BOT (Spațieri 0,127 mm).
    
    i) Traseele de alimentare VCC si VCCA se vor dimensiona astfel încât să poată conduce un curent de 1A pentru o supraîncălzire admisă de maxim 20°C, ţinând cont că
grosimea foliei de cupru este de 18 μm.

    j) Planul de inscripționare (silkscreen) este orientat conform poziție plachetei.
    
    k) Componentele THD vor fi amplasate exclusiv pe TOP. Pentru componentele SMD se va alege varianta optimă pentru o rutare facilă.
    
    l) Pe planul Silkscreen asociat stratului electric TOP va fi inscripționat simbolul (+Vin) poziționat lângă pinul (+Vali) şi simbolul (GND) poziționat lingă pinul (GND_SIGNAL) aferenți conectorului de alimentare.
    
    m) Pe planul Silkscreen asociat stratului electric TOP va fi inscripționat numele studentului cu caractere de înălțime 0.75 mm și grosime de 0.2 mm.
    
    n) Pentru finalizarea proiectării se vor genera fișierele Gerber necesare realizării practice a schemei electrice.
