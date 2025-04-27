# 📚 Consultes MongoDB - Restaurants Nova York

## Descripció
Tenim una col·lecció d'objectes **Restaurant** de la ciutat de **Nova York**.  
Necessitem resoldre diverses consultes de bases de dades MongoDB...

Aquest projecte inclou pràctica amb:
- Cerca simple i avançada
- Ús de filtres, projeccions i ordenacions
- Expressions regulars
- Operadors d'agrupació i condicions compostes

---

## 📋 Reptes de consultes

- Mostrar tots els documents de la col·lecció Restaurants.
- Mostrar el `restaurant_id`, `name`, `borough` i `cuisine` per a tots els documents.
- Mostrar el `restaurant_id`, `name`, `borough` i `cuisine` sense el camp `_id`.
- Mostrar el `restaurant_id`, `name`, `borough` i `zipcode`, sense el camp `_id`.
- Mostrar tots els restaurants ubicats al **Bronx**.
- Mostrar els **primers 5** restaurants del Bronx.
- Mostrar els **següents 5** restaurants després de saltar els primers 5 del Bronx.
- Trobar restaurants amb **score** superior a 90.
- Trobar restaurants amb **score** entre 80 i 100.
- Trobar restaurants amb **latitud** menor que -95.754168.
- Trobar restaurants que **no** són de cuina 'American', amb **qualificació > 70** i **longitud < -65.754168**.
- Trobar restaurants **sense usar $and**, amb cuina diferent d'American, score > 70 i longitud < -65.754168.
- Trobar restaurants que **no** siguin de Brooklyn, amb **grau "A"**, ordenats per `cuisine` descendent.
- Trobar restaurants on el nom **comenci amb** "Wil".
- Trobar restaurants on el nom **acabi amb** "ces".
- Trobar restaurants amb "Reg" en **qualsevol part** del nom.
- Trobar restaurants del Bronx que preparin **cuina americana o xinesa**.
- Trobar restaurants de **Staten Island, Queens, Bronx o Brooklyn**.
- Trobar restaurants **fora** de Staten Island, Queens, Bronx i Brooklyn.
- Trobar restaurants amb marcador **menor o igual a 10**.
- Trobar restaurants que **preparin peix**, **excepte** 'American' i 'Chinees', o que **el nom comenci amb** 'Wil'.
- Trobar restaurants amb grau **"A"** i score **11** el **11 d'agost de 2014**.
- Trobar restaurants on el **segon** element de `grades` tingui grau "A" i score 9 el **11 d'agost de 2014**.
- Trobar restaurants on el **segon** element de `address.coord` sigui entre **42 i 52**.
- Ordenar restaurants per **nom ascendent**.
- Ordenar restaurants per **nom descendent**.
- Ordenar per **cuisine ascendent** i **borough descendent**.
