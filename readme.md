

# SnakeGame


## Descrierea proiectului:
SnakeGame este un simplu exemplu de implementare în C++ a jocurilor video. Acest joc constă în controlul a unui șarpe care se mișcă pe o suprafață (tablou) pentru a mânca cât mai multe mere. Obstacolele din joc sunt marginile tabloului și propria coada a șarpelui.


### Regulile jocului:
1. Mișcare - Șarpele se mișcă într-o anumită direcție și nu își o schimbă până nu este schimbată direcția din nou. Direcțiile sunt: sus, jos, stânga, dreapta;
2. Progresiunea - Lungimea șarpelui crește cu fiecare măr mâncat;
3. You Lose - Jocul se termină dacă șarpele se lovește de marginea tabloului sau de coada lui;
4. Scorul - Scorul este numărul de mere mâncate de șarpe până jocul nu este pierdut.
5. Tipuri de date noi: (nu prea am înțeles daca trebuie din fiecare fișier să descriu tipul de dată sau numai acelea unice, așa că am descris fiecare tip de dată din fiecare fișier și mai jos doar am descris ce face fiecare tip de date unic folosit...):

- struct Point (structura) este un punct în spațiu cu două coordonate x și y;
- class Apple (clasă) este un măr care are o poziție definită de Point;
- enum class Direction (enum) enumără direcțiile posibile ale șarpelui;
- class Snake (clasă) este protagonistul :) jocului ce este format din array de puncte. Sunt incluse metode de mișcare, mărimea șarpelui și interacțiunea cu merele;
- class Board (clasă) reprezintă tabloul de joc și definirea lățimii și înălțimii acestuia;
- class GameEngine (clasă) este acea parte a codului ce gestionează logica între mere tablou și șarpe;
- class Painter (clasă) desenează imagini și text pe ecran.



- struct - tip de date utilizat pentru a grupa mai multe variabile sub un singur nume care se vor numi respectiv membri și pot fi de diferite tipuri de date;
- clasa - combină datele și metodele într-o singură unitate. Clasa permite crearea de obiecte care conțin atât date cât și funcționalitate;
- enum - definirea unui set de constante numite.