# Receptų forumas

## Aprašymas
Šioje platformoje naudotojai galės kurti įvarius teminius blokus, juose rašyti įrašus ir dalintis savo mėgstamais receptais, komentuoti juos.
Taikomosios srities objektai: Tema -> Įrašas -> Komentaras;

---
## Funkcionalumas (funkciniai reikalavimai)

* Sistemoje veikianti naudotojų autentifikacija ir trys naudotojų lygiai: svečias, narys (registruotas naudotojas) ir administratorius.
* Sistemos svečias gali peržiūrėti sistemos tematikas, įrašus (receptus), skaityti komentarus tačiau kurti, redaguoti ar šalinti negalės.
* Registruotas naudotojas, kaip ir svečias, turi galimybę peržiūrėti sistemos įrašus ir atlikti turinio valdymo (CRUD) operacijas savo kurtam turiniui.
* Administratorius turi visas teises susijusias su turinio redagavimu ir kitų sistemos naudotojų paskyrų administravimu.
* Paieška ir filtrai. Naudotojai gali ieškoti receptų (įrašų) pagal raktažodžius.
* Naudotojai turi galimybę vertinti kitų naudotojų įrašus pagal žvaigždučių sistema (nuo 1 iki 5).

---
Naudojamos technologijos:
- **Frontend**: Kažkas
- **Backend**: .NET (ASP.NET Core)
- **Duomenų bazė**: PostgreSQL