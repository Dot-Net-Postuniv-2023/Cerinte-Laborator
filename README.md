# Cerinte Laborator

## Pentru saptamana 6:
#### 17.06.2023

1. Adaugati un model `User` cu campurile `Username`, `Password`, `IsConfirmed` si alte `3` campuri optionale. Parola trebuie sa fie hashed.
2. Implementati register si login folosind `JWT` in endpoint-urile: `/api/token/register`, `api/token/confirm/<username>`, `api/token/login`.
3. Asociati fiecare `Activity` cu un `User`.

----

## Pentru saptamana 5:
#### 10.06.2023

1. Adaugati inca un model in aplicatie: `SubActivity`: `Description`, `Numar ore`, `Dificultate`. Rulati migrarile necesare si creati functionalitatile CRUD pe controller / controllere.
2. Implementati pe Frontend CRUD folosind Reactive Forms. Vor exista pagini separate pentru: afisare activitati, adaugare activitate, detalii activitate, editare activitate. Subactivitatile sa apara in pagina de Details pentru o activitate. Pagina de afisare activitati sa afiseze numarul total de ore ca suma a orelor subactivitatilor.
3. In formularul de Adaugare activitate sa pot adauga, fara refresh, oricate subactivitati vreau. Ar trebui sa existe campuri pentru atributele unei subactivitati si butoane care genereaza si sterg dinamic campurile formularului pentru subactivitati. Vezi finalul cursului 4 si codul aferent pentru exemple.

----

## Pentru saptamana 4:
#### 03.06.2023

- Adaugati SQL Server aplicatiei de backend.
- Adaugati stilizare aplicatiei de frontend (folosind Bulma, Bootstrap, Angular Material sau ceva similar), pentru toate componentele.

----

## Pentru saptamana 3:
#### 27.05.2023

Implementati o aplicatie Angular care va suporta operatiile de pana acum comunicand cu serverul de .NET REST API.

---- 

## Pentru saptamana 2:
#### 20.05.2023

Scrieti o aplicatie .NET REST API pentru time tracking. Vor fi suportate functionalitatile:

1. Adaugarea unei activitati: `Nume`, `Descriere`, `Data`, `Numar ore`.
2. Show all, Detalii, Edit, Delete activitati (`CRUD`).
3. Filtrare activitati dupa `Data` si dupa `Numar ore`.
