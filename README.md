<!-- PROJECT LOGO -->
<br />
<p align="center">
    <a href="#Csharp-essentials">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
    </a>

<!-- Main -->
## Csharp Essentials



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#tasks">Tasks</a>
      <ul>
        <li><a href="#2020-03-05">2020-03-05</a></li>
      </ul>
    </li>   
  </ol>
</details>

<br />
<br />
<br />

<!-- Imperative -->
## Tasks


Csharp feladatok.


### 2020-03-05

* Készíts egy programot amely a megadott `emberek.txt` fájlt feldolgozza és a benne található emberek adatait egy `Ember` típusú listába menti.
<br/>
emberek.txt //Az emberek előtt *** karakterek jelentik az elkülőnítést (avagy "új ember kezdete" sort)
<pre><code>***
zoli
187
33
igen
***
bela
174
22
nem
***
peti
166
18
nem
***
fanni
161
22
igen
***
david
179
45
nem
***
peti
192
27
igen
</code></pre>
<br/>
Ember osztály felépítése // Konstruktorba kérjük be az adatokat, illetve hozzunk létre egy metódust amit ha meghívunk kiírja console -ra az adott ember adatait.
<pre><code>	
public class Ember
{
	public string Nev {get; set;}
	public int Magassag {get; set;}
	public int Eletkor {get; set;}
	public bool BudapestiLakos {get; set;}
	
	public Ember(string nev, int magassag, int eletkor, bool budapesti)
	{
		Nev = nev;
		Magassag= magassag;
		//stb...
	}
	
	public void Adatok()
	{
		//Kiiratas
	}
   
}
</code></pre>

<br/>

* Az adatok feldolgozása után kérjen be egy tetszőleges nevet a program és ammenyiben egy adott ember szerepel a listában, akkor írja ki az adatait

<br/><br/>Az adatok kiírása a következő formátumban legyen:
<pre><code>zoli --- 187cm --- 33 éves --- Budapesti lakos
</code></pre>

<br/>

* Abban az esetben, ha egy adott név alatt több ember is szerepel, akkor írja ki a program az összes ember adatait sorban.
<br/><br/>Az adatok kiírása a következő formátumban legyen:
<pre><code>peti --- 192cm --- 27 éves --- budapesti lakos
peti --- 166cm --- 18 éves --- nem budapesti lakos
</code></pre>

