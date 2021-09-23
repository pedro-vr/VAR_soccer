# VAR_soccer

Dentro de este documento se encuentran las siguientes tablas:

1. pl_ot: Tabla que mide los overturns generados por el VAR por cada equipo de la PL dentro de las temporadas 19/20 y 20/21. Dentro de esta tabla se consideran las siguientes variables:

  a. ns (net score): Marcador neto sobre decisiones del VAR efectuadas sobre el equipo correspondiente, es la resta entre el total de decisiones del VAR a favor del equipo en cuestión (df) y el total de decisiones del VAR en contra del equipo en cuestión (da), por lo tanto, la fórmula es df - da. Si esta variable tiene un valor positivo (>0) significa que el equipo en cuestión tuvo en total más decisiones del VAR a favor que en contra; si esta variable tiene un valor negativo (<0) significa que el equipo en cuestión tuvo en total más decisiones del VAR en contra que a favor; y, finalmente, si esta variables igual a cero entonces significa que el equipo en cuestión tuvo el mismo número de decisiones del VAR a favor y en contra.
  
  b. df (decisions for): Número total de decisiones del VAR a favor del equipo en cuestión
  
  c. da (decisions against): Número total de decisiones del VAR en contra del equipo en cuestión
  
  d. ovrt (overturns): Número total de intervenciones del VAR sobre el equipo en cuestión, es la suma entre las decisiones a favor del equipo en cuestión (df) y las decisiones en contra del equipo en cuestión (da)
  e. lgf (leading goals for): Número total de goles de ventaja a favor sobre el equipo contrario
  f. dgf (disallowed goals for): Número total de goles anulados a favor del equipo en cuestión
  g. lga (leading goals against): Número total de goles de ventaja en contra con respecto el equipo contrario
  h. dga (disallowed goals against): Número total de goles anulados en contra del equipo en cuestión
  i. ngs (net goal score): Número neto en goles del equipo en cuestión tomando en cuenta los goles anulados a favor (dgf), los goles de ventaja a favor (lgf), los goles anulados en contra (dga) y los goles de ventaja en contra (lga). Esta variable se calcula de la siguiente manera: (lgf + dga) - (dgf + lga)
  j. sdf (subjective decisions for): Número total de decisiones subjetivas del VAR a favor del equipo en cuestión
  k. sda (subjective decisions against): Número total de decisiones subjetivas del VAR en contra del equipo en cuestión
  l. nsc (net subjective score): Marcador neto del partido sobre las decisiones subjetivas hechas por el VAR sobre el equipo en cuestión, es la resta entre el número total de decisiones netas a favor (sdf) y el número total de decisiuones subjetivas en contra del equipo en cuestión (sda)
  
2. pl_matches: 


