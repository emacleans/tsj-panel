# Informe del orquestador — 18/10 05:12

Pausado: no · máx. simultáneas: 4 · pausa por límite hasta: -
Reglas de lectura: «total por confirmar» = aún no se midieron todas las salas de la gestión (sin % ni ETA); ETA con «~» y rango; «viejo» = dato de hace más de 10 min.

## Gestiones

| Gestión | Estado | Salas medidas | Documentos | % | ETA | Equipo | Dato |
|---|---|---|---|---|---|---|---|
| 2013 | Compilada completa | 11 de 11 | 5263 / 5271 | 99.8 % | - | IPE02 (Mac Mini casa) | hace 2 min |
| 2014 | Compilada completa | 13 de 13 | 4571 / 4584 | 99.7 % | - | IPE02 (Mac Mini casa) | hace 2 min |
| 2015 | Compilada completa | 7 de 7 | 4296 / 4298 | 100.0 % | - | iMac-Sala (iMac de la sala) | hace 2 min |
| 2016 | Compilada completa | 5 de 5 | 4043 / 4051 | 99.8 % | - | MM-Ali (Mac Mini Alicia) | hace 3 min |
| 2012 | Compilada completa | 8 de 8 | 3207 / 3211 | 99.9 % | - | IPE02 (Mac Mini casa) | hace 2 min |
| 2011 | Compilada completa | 6 de 6 | 1568 / 1572 | 99.7 % | - | IPE01 (Mac Mini oficina) | hace 2 min |
| 2010 | Compilada completa | 6 de 6 | 2944 / 2947 | 99.9 % | - | IPE01 (Mac Mini oficina) | hace 2 min |
| 2009 | Compilada completa | 7 de 7 | 2245 / 2255 | 99.6 % | - | MM-Sofi (Mac Mini Sofía) | hace 2 min |
| 2008 | Compilada completa | 6 de 6 | 2333 / 2340 | 99.7 % | - | IPE01 (Mac Mini oficina) | hace 2 min |
| 2007 | Compilada completa | 6 de 6 | 3319 / 3331 | 99.6 % | - | iMac-Sala (iMac de la sala) | hace 2 min |
| 2006 | Compilada completa | 6 de 6 | 3008 / 3009 | 100.0 % | - | IPE01 (Mac Mini oficina) | hace 2 min |
| 2005 | Compilada completa | 7 de 7 | 2179 / 2182 | 99.9 % | - | MM-Ali (Mac Mini Alicia) | hace 3 min |
| 2004 | Compilada completa | 6 de 6 | 1743 / 1747 | 99.8 % | - | IPE01 (Mac Mini oficina) | hace 2 min |
| 2003 | Compilada completa | 4 de 4 | 1377 / 1379 | 99.9 % | - | IPE01 (Mac Mini oficina) | hace 2 min |
| 2002 | Compilada completa | 5 de 5 | 1318 / 1323 | 99.6 % | - | IPE01 (Mac Mini oficina) | hace 2 min |
| 2001 | Compilada completa | 3 de 3 | 419 / 423 | 99.1 % | - | MM-Ali (Mac Mini Alicia) | hace 3 min |

## Equipos

| Equipo | Estado | Trabajo | Salud | Dato |
|---|---|---|---|---|
| IPE01 (Mac Mini oficina) | en línea | libre | - | hace 2 min |
| IPE02 (Mac Mini casa) | en línea | libre | - | hace 2 min |
| MM-Ali (Mac Mini Alicia) | DESCONECTADO | libre | - | hace 3 min |
| MM-Sofi (Mac Mini Sofía) | en línea | libre | - | hace 2 min |
| MacBook Air | DESCONECTADO | libre | - | hace 2 h (viejo) |
| iMac-Sala (iMac de la sala) | en línea | libre | - | hace 2 min |
| iMac-VJ1 (iMac 21,5 pulgadas 2017) | en línea | libre | - | hace 2 min |
| iMac-VJ2 (iMac 21,5 pulgadas 2017) | en línea | libre | - | hace 2 min |

## Incidencias abiertas

- ninguna

## Últimas acciones del orquestador

- 18/10 04:23 · director: tcp:ipe02 terminó «conc_2_2013»
- 18/10 04:24 · director: tcp:ipe02 lanza «conc_2_2016» (tcp_conciliar {'base': '2'})
- 18/10 04:28 · director: tcp:ipe02 terminó «conc_2_2016»
- 18/10 04:29 · director: tcp:ipe02 lanza «conc_2_2018» (tcp_conciliar {'base': '2'})
- 18/10 04:34 · director: tcp:ipe02 terminó «conc_2_2018»
- 18/10 04:35 · director: tcp:ipe02 lanza «conc_2_2022» (tcp_conciliar {'base': '2'})
- 18/10 04:39 · director: tcp:ipe02 terminó «conc_2_2022»
- 18/10 04:40 · director: tcp:ipe02 lanza «conc_2_2026» (tcp_conciliar {'base': '2'})
- 18/10 04:45 · director: tcp:ipe02 terminó «conc_2_2026»
- 18/10 04:46 · director: tcp:ipe02 lanza «pautas_ipe02» (tcp_aplicar_pautas {})
- 18/10 04:51 · director: tcp:ipe02 terminó «pautas_ipe02»
- 18/10 05:06 · director: gaceta:ipe02 terminó «p_sent2»
- 18/10 05:11 · orden de Claude 2026-10-18-ok-p_dep8: paso del director aprobado: p_dep8
- 18/10 05:11 · director: gaceta:ipe02 lanza «c_dep8» (gaceta_iniciar {'seccion': 'dep_8', 'modo': 'completo'})
- 18/10 05:11 · director: gaceta:imac-vj1 lanza «c_dep1» (gaceta_iniciar {'seccion': 'dep_1', 'modo': 'completo'})
