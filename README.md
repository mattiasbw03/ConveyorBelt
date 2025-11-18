Conveyor Belt Capacity Check
Formål
Formålet med programmet er at afgøre, om et transportbånd med et givent antal motorer kan bære den samlede vægt af pakker, uden at overskride motorernes maksimale kapacitet.
 Hver motor kan bære op til 5,6 kg.
Programmet spørger derfor brugeren om:
Hvor mange motorer der bruges.
: Hvor mange kilo pakkerne samlet vejer.
: Herefter beregner programmet, om vægten pr. motor er for høj.

Forklaring
motor_capacity er en konstant, der angiver hvor meget vægt én motor kan klare (5,6 kg).

Brugeren indtaster antal motorer og samlet vægt.

Programmet sammenligner herefter den samlede vægt (kg) med motorernes samlede kapacitet (num_motor * motor_capacity).

Hvis vægten er større eller lig med kapaciteten, skriver programmet:
 → “Bæltet kan ikke køre”.

Ellers skriver det:
 → “Bæltet kan godt køre”.
