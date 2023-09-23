PyCon CZ 2023 workshop
=======================

Vo workshope sa venujeme knižnici PyParsing. PyParsing je Python knižnica poskytujúca sadu tried, funkcií a metód vhodných na vytvorenie syntaktického analyzátora.

**Na aké use casy je PyParsing vhodný**
Keď potrebujeme parsovať (viac-menej) štruktúrovaný komplikovaný text
1. parsovanie z textových súborov, pdf, kníh,...
2. extrahovanie dát z webových stránok
3. komplexné full textové vyhľadávanie
4. čítanie dát z tabuliek
5. čítanie komplikovaných log súborov
6. čítanie dát z komplikovaných zanorených API štruktúr
7. natural language processing
8. mnoho iného

Link na prezentáciu k workshopu nájdete [tu]([https://pypi.python.org/pypi/pip](https://docs.google.com/presentation/d/1WuzfjkAyBjFRDnjpOQumO5MN0eT4K8OTwZ_ZR7mZMEQ/edit?usp=sharing)).


V prvom kroku si nainštalujeme virtuálne prostredie, v ktorom budeme našu aplikáciu vyvíjať a spúštať. Virtuálne prostredie slúži k oddeleniu rôznych inštalácií balíčkov, verzií Pythonu na jednom počítači. Taktiež ak sa niečo v projekte pokazí, ktorý je vytvorený v rámci daného virtuálneho prostedia, neohrozí to ďalšie projekty na počítači.

Úlohy:

1. Otvor si príkazový riadok (terminál - Mac OS, Linux)

2. Zvoľ si adresár, v ktorom budeš mať vytvorený projekt a následne pracovať.

3. Naviguj sa do adresára

4. Vytvor novú složku a vstúp do novo-vytvorej zložky

5. Vytvor virtuálne prostredie. Príkazy pre vytvorenie virtuálneho prostredia sa líšia podľa operačného systému:

Windows:

<pre><code>> py 3 -m venv venv </code></pre>

Linux/Mac OS:

<pre><code>$ python3 -m venv venv </code></pre>

Po vytvorení virtuálneho prostredia je potrebné ho **spustiť.** . Spustenie virtuálneho prostredia sa taktiež líši podľa operačného systému:

Windows:

<pre><code>>\venv\Scripts\activate</code></pre>

Linux/Mac OS:

<pre><code>$ source /venv/bin/activate </code></pre>

Po spustení by malo ukázať pred <code> > </code> alebo <code>$</code> slovo <code>(venv)</code>.

<pre><code>(venv) MacBook-Pro:pyconworkshop svetlanamargetova$ </code></pre>

## Inštalácia potrebných knižníc

Na inštaláciu budeme využívať [pip](https://pypi.python.org/pypi/pip). 


### Inštalácia PyParsing

[PyParsing]([http://pandas.pydata.org/](https://pypi.org/project/pyparsing/)) je knižnica umožňujúca napísať nám gramatiku, lexikálne parse v Pythone.

<pre><code>$ pip install pyparsing</code></pre>

