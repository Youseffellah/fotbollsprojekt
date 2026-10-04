# ⚽ Fotbollsprojekt – VM Slutspel 2026

## Mål
Analysera VM-matcher och deras resultat från slutspelet 2026. Projektet simulerar hur en AI-utvecklare hanterar data: skapar, sparar, läser och analyserar.

## Metod
1. Skapa klasser (VMMatch och SlutspelsMatch)
2. Skapa 8 matcher från slutspelet
3. Spara matcherna i JSON-format
4. Läsa tillbaka matcherna
5. Analysera statistik (mål, medelvärde, max/min)
6. Visualisera resultatet med matplotlib

## Resultat
- Antal matcher: 8
- Totala mål: 28
- Medel mål per match: 3.5
- Max mål: 10
- Min mål: 1
- Oavgjorda: 0

## Analys
Projektet visar hur OOP (klasser och arv) kan användas för att organisera data. Genom att använda en barnklass (SlutspelsMatch) kan vi lägga till specifik funktionalitet utan att skriva om koden. Detta speglar hur svenska AI-bolag som Einride och Kry hanterar tusentals datapunkter.

## Reflektion
Det svåraste var att förstå hur `super().__init__()` fungerar och varför `self` behövs. Jag löste det genom att testa steg för steg. Nästa gång skulle jag lägga till ett riktigt API-anrop istället för hårdkodad data.

## Certifikat
Relevanta certifikat för AI-utvecklare:
- **AWS Certified Machine Learning** – molnbaserad AI
- **Microsoft Azure AI Engineer** – AI-lösningar i Azure
- **Databricks Certified Associate Developer** – stordata och Spark

## Branschkoppling
Projektet liknar hur svenska AI-bolag arbetar:
- **Einride** – hanterar sensordata från lastbilar
- **Kry** – analyserar patientdata
- **Volvo** – testar självkörning

Alla använder Python, klasser och datahantering – precis som detta projekt.

## GitHub
https://github.com/Youseffellah/fotbollsprojekt

## Installation
1. Klona repot
2. Öppna `fotbollsprojekt.ipynb` i VS Code
3. Kör alla celler