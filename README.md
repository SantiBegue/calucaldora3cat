# calucaldora3cat 
Calculadora entregues


---

### Calculadora de Planificació de Projectes amb Fites i Festius

Aquesta eina interactiva és una calculadora de dates de projecte dissenyada per ajudar a determinar la data d'inici necessària d'un projecte, tenint en compte una data d'entrega final i fites intermèdies amb durades específiques. La calculadora exclou automàticament els caps de setmana i els dies festius de Barcelona, i permet afegir festius personalitzats per a una major precisió.

#### Funcionalitats Clau:

* **Càlcul de Dates d'Inici:** Calcula la data d'inici del projecte i de les seves fases clau (Revisió QA, Validació de Producte) retrocedint des de la data d'entrega final.
* **Fites Predefinides:**
    * **Revisió QA:** 5 dies laborables.
    * **Validació de Producte:** 3 dies laborables.
* **Exclusió de Dies No Laborables:**
    * Els caps de setmana (dissabtes i diumenges) s'exclouen automàticament.
    * S'inclou una llista predefinida de **dies festius de Barcelona** (anuals).
    * Permet afegir **dies festius personalitzats** mitjançant una àrea de text (format `YYYY-MM-DD`, un per línia).
* **Visualització del Calendari:** Mostra una vista de calendari interactiva que abasta tots els mesos del projecte, destacant:
    * Dies laborables per fase (Desenvolupament, Revisió QA, Validació de Producte) amb colors diferents.
    * Caps de setmana.
    * Dies festius.
    * Dates d'inici de cada fita i la data d'entrega final.

#### Com Utilitzar-la:

1.  **Selecciona la Data d'Entrega:** Tria la data límit final del projecte al camp "Data d'entrega (últim dia de treball)".
2.  **Afegeix Festius (Opcional):** Si hi ha festius addicionals que no estan a la llista predefinida o si vols incloure festius d'anys futurs, introdueix-los a l'àrea de text "Dies festius addicionals" (un per línia, format `YYYY-MM-DD`).
3.  **Calcula:** Fes clic al botó "Calcular Dates d'Inici".
4.  **Revisa els Resultats:** La calculadora mostrarà les dates d'inici calculades per a cada fita i una vista detallada del calendari amb la planificació visual.

#### Notes Importants:

* La llista de dies festius de Barcelona està predefinida en el codi i **s'ha d'actualitzar manualment** cada any per garantir la precisió dels càlculs.
* Aquesta calculadora és una eina de planificació i no té en compte factors com la disponibilitat de recursos, dependències externes o possibles retards inesperats.

---
