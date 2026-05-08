title: Arbete med python-klient för lantmäteriet påbörjat
date: 2026-05-01
modified:
author: Anders Nord
category: Projekt
tags: python, smhi, väder, data, klimat, ifk
data:
status: published

**IFK har under flera år arbetat för att tillgängliggöra översvämningsanalyser för
allmänheten, sedan MSB 2020 påpekade att en överväldigande majoritet av Sveriges
kommuner saknar handlingsplan för skyfall. Eftersom risken för skyfall ökar kraftigt
i ett varmare klimat är detta mycket allvarligt, vilket vi sett exempel på, såväl
2024 då E45 översvämmades i Lilla Edet som 2025 då inlandsbanan i västernorrland
regnade bort. En nyckel för att kunna genomföra översvämningsanalys är högupplöst
kartdata med höjd- och marktypsinformation, och den datan hanteras i Sverige av
Lantmäteriet. IFK har genom Mladen Gibanicas arbete nu access till den mest högupplösta
kartdatan och har påbörjat utvecklingen av ett paket för att läsa in datan i python.**

– Jag har byggt en kod som fungerar för oss internt, säger Mladen, som till vardags
arbetar som dataanalytiker på en konsultfirma i Göteborg, men innan vi släpper
detta till allmänheten behöver vi se till att kunna traversera APIt och tillgängliggöra
all den data som lantmäteriet har, inte bara höjddatan. Vi behöver också ordna
med tester och dokumentation för att säkerställa att vi kan underhålla koden över
tid.

<div class="post-image-center">
    <img alt="Översvämningsanalys av Trollhättan."
    src="data/trollhättan.png" />
    <em>Exempel på översvämningsanalys: E45 vid passage genom Trollhättan. Beräkningsunderlaget
    kommer från lantmäteriets data, men för grafisk representation används data
    från OpenStreetMap.</em>
</div>

För översvämningsanalysarbetet är koden i alla händelser funktionell; Christoffer
Strömberg har implementerat öppet tillgängliga modeller på den data som genereras
och är väldigt nöjd med resultatet:

– Jag fick läsa på en del om kartprojektioner för att få de olika kartverktygen
att passa ihop, men att få tag på datan utgjorde inga problem, säger Christoffer
med ett brett leende.

Programkoden ligger tillgänglig på föreningens GitHub och precis som all annan
kod som skrivs i föreningen är den gratis och öppen för alla att använda och modifiera,
men på grund av den begränsade statusen har ännu ingen första release gjorts, vilket
innebär att paketet måste installeras direkt från GitHub.

Om du är intresserad av att hjälpa till och utveckla koden
är du mer än välkommen att [gå med i föreningen](mailto:info@ingenjorsarbeteforklimatet.se).

<a href="https://github.com/Ingenjorsarbete-For-Klimatet/ifk-lantmateriet" target="_blank">
Ingenjörsarbete För Klimatets GitHub</a>.

(c) Ingenjörsarbete för Klimatet. För återpublicering kontakta ansvarig utgivare
Anders Nord [anders.nord@ingenjorsarbeteforklimatet.se](mailto:anders.nord@ingenjorsarbeteforklimatet.se).
