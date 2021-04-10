# SolverProject_Template
Projekt, das rein als Basis zur Angabe dient.

Angabe befindet sich auf dem Elearn, aber hier in "unformatierter Form":
_________________________________________________________________________

Laden Sie sich das Unity-Projekt herunter und stellen Sie sicher, dass es nach dem Download einwandfrei starten lässt. 
Das Projekt befindet sich auf Github: [URL] 

Im Projekt ist ein sogenanntes “Target” enthalten, MRTK und Project Settings sind bereits eingestellt. 

1) 

Implementieren Sie einen DirectionalIndicator-Solver, der in Richtung des “Target” zeigt. (Im Optimalfall wird hierzu ein Pfeil als Indicator benutzt) 
Hierbei sind folgende Forderungen gegeben: 

    Der Indicator soll sichtbar bleiben, bis auf eine Distanz von 0,2 Meter 

    Von der direkten Sicht (View) soll er 0,1 Meter entfernt sein 

    Er soll seine fixe Skalierung haben (diese darf selbst gewählt werden) 

2) 

Implementieren Sie ein GameObject, das die verbleibende Entfernung zum GameObject angibt (Vorschlag: TMP) – es soll ein RadialView verwendet werden um die Distanz konstant im Sichtfeld des Users zu behalten. 

    Es soll der Ausgangswinkel zu keiner Zeit abgeändert werden 

    Der Text soll Minimal 2 Meter entfernt sein, und Maximal 3 Meter 

    Der Text soll sich in eine Ecke orintieren (Rechts/Links Oben/Unten) 

    Hint: Verwende “Additional Offset” des SolverHandler  

 

Falls das implementieren der Entfernungsanzeige nicht funktioniert, soll ein beliebiger Text angezeigt werden. (Fokus soll nicht aufs Skript gelegt werden, sondern auf die korrekte Verwendung des Solvers) 
