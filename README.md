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

* Készíts egy programot amely egy megadott `emberek.txt` fájlt feldolgozza és a benne található emberek adatait egy `Ember` típusú listába menti.
<br/>
emberek.txt
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
</code></pre>
<br/>
Ember osztály felépítése
<pre><code>public class Ember
			
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
* Az adatok feldolgozása után kérjen be egy tetszőleges nevet a program és ammenyiben egy adott ember szerepel a listában, akkor írja ki az adatait
* Abban az esetben, ha egy adott név alatt több ember is szerepel, akkor írja ki a program az összes ember adatait sorban.
<pre><code>kubectl get pod --show-labels</code></pre>

* List pods with specific label
<pre><code>kubectl get pod -owide --selector=$label</code></pre>
