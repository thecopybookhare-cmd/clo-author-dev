# Master Data — EV Chile Essay
**Ultima actualizacion:** 2026-05-04
**Estado:** Investigacion COMPLETA — listo para escribir

---

## CAP 2 — Definicion y tipos de EV

- BEV (Battery Electric Vehicle): propulsion 100% electrica, 0 emisiones tubo de escape — Ministerio de Energia (2022)
- PHEV (Plug-in Hybrid Electric Vehicle): motor electrico + ICE, enchufable — ANAC definicion operacional
- HEV (Hybrid Electric Vehicle): no enchufable, se recarga frenando — ANAC
- MHEV (Mild Hybrid): microhibrido de apoyo, no es enchufable — ANAC
- FCEV: pila de hidrogeno, excluido del ensayo por escala — Ministerio de Energia (2022)
- Ley 21.505 aplica solo a BEV y FCEV; PHEV excluidos expresamente del beneficio — BCN, Ley 21.505

---

## CAP 3 — Situacion actual Chile

### Ventas EV (serie temporal Statista + ANAC)

| Anio | Total EV (BEV+PHEV) | BEV | PHEV | Total autos nuevos | Market share EV |
|------|---------------------|-----|------|--------------------|-----------------|
| 2019 | 294 | 159 | 135 | 260,683 | 0.1% |
| 2020 | 857 | 719 | 138 | 194,128 | 0.4% |
| 2021 | 1,837 | 1,512 | 325 | 304,045 | 0.6% |
| 2022 | 2,287 | 1,673 | 614 | 313,589 | 0.7% |
| 2023 | 906 | 404 | 502 | 218,642 | 0.4% |
| 2024 | 6,206 | 4,236–4,507 | 1,970 | ~184,545–209,154 | ~3.0% |
| Ene-Nov 2025 | 7,561 enchufables | 4,717 BEV | 2,844 PHEV | — | ~3.5% proy. |

Fuentes: Statista Market Insights (CSV, abril 2026); ANAC informe diciembre 2024; Estrategia ene 2026.

Nota metodologica: la "caida" de 2022 a 2023 es una diferencia de categorias (2022 = BEV+PHEV+HEV; 2024 = solo BEV). No es una caida real de ventas electricas puras.

- BEV participacion mercado: 0.59% (2023) → 2.2% (2025) — El Mercurio, sep 2025
- Ventas electrificadas totales Jan-Nov 2025: 31,208 unidades (+92.5%) — Estrategia, ene 2026
- SUV concentra 49.5% de ventas enchufables en 2025 — ANAC
- 40% de los modelos BEV 2025 cuestan menos de $35M CLP — ANAC
- Chile 2do en el mundo en buses electricos (despues de China): 55% de la flota Santiago — El Mostrador, ene 2026; C40 Cities (2023)
- Santiago: >4,000 buses electricos; ahorro USD 258 millones/anio — La Tercera, mar 2026

### Mix flota vehicular

- Flota total motorizada: 6,592,807 unidades al cierre 2024 (crecimiento 2.9% anual) — NotebookLM / INE
- BEV en flota: ~1% — Statista survey 2024
- Gasolina: 80%, Diesel: 15%, HEV no enchufable: 2%, BEV: 1% — Statista 2024
- Autos nuevos vs usados en 2023: 319,568 nuevos / 963,363 transferencias usados; ratio 3:1 — Autofact/ANAC

### Distribucion parque por antiguedad

| Tramo | % estimado | Unidades aprox. |
|-------|-----------|-----------------|
| 0-5 anios | 27.3% | ~1,785,000 |
| 6-10 anios | 26.0% | ~1,701,000 |
| 11-15 anios | 19.4% | ~1,268,000 |
| +15 anios | 27.3% | ~1,785,000 |

Fuente: estimacion derivada de ventas acumuladas ANAC + permisos circulacion INE 2023. No es tabulacion directa INE. NotebookLM2, 2026-05-04.
- Antiguedad promedio flota: 9.4 anios (ANAC) / 9.8 anios (El Mercurio, sep 2024)
- RM tiene antiguedad promedio menor (7.6 anios) vs Arica y Parinacota (13.4 anios) — ANAC
- Tasa de retiro anual ICE: 250,000–350,000 vehiculos/anio — declaraciones industria automotriz / BCN/ANAC — NotebookLM2

### Infraestructura de carga

- Total acumulado al cierre 2023: 439 puntos carga publica / 1,214 conectores — MobilityPortal / SEC
- Nuevos instalados en 2024: 336 cargadores publicos (+7% vs 2023); 904 privados (+63%) — SEC / ANAC
- Total acumulado 2024: ~1,091 cargadores publicos publicos; 32,843 kW instalados; potencia promedio 30.7 kW — ANAC diciembre 2024
- Total acumulado Q1 2025: 1,668 cargadores (110 nuevos solo ene-feb 2025) — NotebookLM3
- RM concentra 77% de potencia instalada publica / 85% de los nuevos de 2024 — NotebookLM / informe SEC
- 216 de las 346 comunas sin ningun punto de carga publica — NotebookLM1
- 60% de las comunas de Chile sin un cargador publico — CMS / La Tercera, mar 2026
- 73% de usuarios EV carga en el hogar, de noche; 85% considera que hay pocos cargadores publicos — Encuesta Volvo/Cadem, sep 2025
- 1/3 de usuarios EV tuvo dificultades buscando cargador fuera de casa — Cadem 2025
- Copec Voltex: 2,359 puntos de carga totales; red continua de 2,200 km — Copec Reporte 2024

Chile vs. comparadores:
- Chile: ~0.062 cargadores/1,000 hab (2023) vs. Paises Bajos: 10.04/1,000 — brecha de 162x — MobilityPortal / gridX
- Chile es el 4to en LatAm por infraestructura absoluta (Brasil 3,800; Mexico 2,083; Colombia 480) — Martinez-Gomez & Espinoza (2024)

### Precios EV en Chile

| Segmento | Precio 2024–2025 (CLP) | USD equiv. |
|----------|------------------------|------------|
| Entry-level (BYD Seagull equiv.) | $11,990,000–$14,990,000 | ~USD 13,000–16,000 |
| SUV compacto (segmento dominante, 48.8% ventas) | $28,000,000–$34,000,000 | ~USD 30,000–36,000 |
| Premium / grande | $75,000,000+ | ~USD 80,000+ |
| Promedio ponderado total BEV+PHEV (sep 2024) | $44,200,000 | ~USD 47,000 |
| Auto convencional promedio nuevo | ~$25,000,000 | ~USD 27,000 |

Fuente: NotebookLM2 / ANAC diciembre 2024 / Autofact.
- El precio promedio BEV cayo 22% en 12 meses a sep 2024 — NotebookLM2
- Statista BEV promedio 2024: USD 64,900 — Statista CSV abril 2026 (nota: dato mas alto que el ANAC, diferencia metodologica)
- Precio mas barato 2026: Renault Kwid E-Tech $11,990,000 CLP con bonos — La Tercera / BioBio 2026

Costos operativos (ventaja EV):
- Carga completa EV: CLP $8,000–12,000 vs. gasolina: CLP $65,000–80,000 (~85% ahorro) — Factiva
- Mantencion EV: hasta 80% mas barata que ICE — Factiva
- Ahorro anual 25,000 km: $2.45 millones CLP — La Tercera, mayo 2025
- Mover un EV es USD 2,300/anio mas barato que gasolina en Chile (2026, contexto alza combustibles) — Olacde / El Mercurio, abr 2026

### Encuesta de barreras (Descifra, n=1,621, nov 2025)

- 56% de chilenos dispuesto a comprar EV o HEV — La Tercera, nov 2025
- Motivaciones pro-compra: ahorro combustible (49%), medio ambiente (29%)
- Barreras en quien no compraria: falta infraestructura carga (20%), autonomia limitada (19%), alto precio (18%), dudas bateria (17%)
- ABC1: barrera principal = falta de puntos de carga (49%); segmento bajo: barrera principal = precio (26%)
- 96% de los chilenos que manejan EV estan satisfechos — Factiva / Cadem, sep 2025
- Busquedas EV en Chileautos: +137% tras alza de combustibles (mar 2026) — El Mercurio, mar 2026

### Contexto del parque automotriz

- 80% de autos nuevos se compra con financiamiento — El Mercurio, sep 2024
- Tasa credito automotriz: 0.79%–1.65% mensual (9.9%–21.6% CAE) — Tasas.cl / Autofact
- Marcas chinas ya 3er/4to lugar en mercado: Chery ~8% share, BYD creciendo rapido — GlobalData / ANAC
- Importacion autos usados: 58,089 unidades en 2021 (+118% vs media 2015-2020); 60% de Japon; antiguedad promedio 11 anios — La Tercera / El Mercurio, ago-sep 2022
- Arancel EV no chinos: ~$1.8M CLP (EV) / $2.1M CLP (PHEV) por unidad (6% CIF); ICE entran sin arancel — El Mercurio, dic 2024
- Motivo: baterias representan ~30% del costo EV y vienen de paises distintos al de fabricacion, superando limite de 45% componentes para TLC

---

## CAP 4 — Politicas actuales Chile

### Marco regulatorio vigente

| Politica | Tipo | Estado | Beneficio |
|---------|------|--------|-----------|
| Ley 21.505 (2022) | C | Vigente | Exencion permiso circulacion BEV/FCEV: 100% anios 1-2; 75% anios 3-4; 50% anios 5-6; 25% anios 7-8; 0% desde 2031 |
| Impuesto verde Ley 20.936 / Ley 21.210 | C | Vigente | BEV = 0 impuesto verde (0 g CO2/km); ahorro vs ICE: CLP 150,000–200,000/anio |
| TLC Chile-China arancel 0% | A | Vigente | BEV fabricados 100% en China entran a 0% arancel (BYD, BAIC, Chery, MG/SAIC) |
| Ley 21.305 (2021) — Eficiencia Energetica | B | Vigente desde 2024 | Estandar rendimiento importadores: 18.8 km/lge (2024-2026); 22.8 (2027-2029); 28.9 (2030+). Multa: hasta 0.2 UF por cada 0.1 km/lge bajo estandar x nro ventas |
| Estrategia Nacional Electromovilidad (2022) | B | Meta sin enforcement | 100% ZEV ventas nuevas al 2035; sin mecanismo de enforcement por ley |
| Mi Taxi Electrico | C | Vigente | Subsidio ~$9.7M CLP por taxi (2026); bono chatarramiento $1.8M (solo 5 regiones extremas); credito BancoEstado tasa preferencial 0.82% mensual, plazo hasta 72 meses |
| BancoEstado Mundo Verde (particulares) | C | Vigente hasta abr 2026 | Tasa 0.89% mensual; plazo hasta 60 meses; financiamiento hasta 100%; gracia 90 dias |
| Scotiabank-Tesla | C | Vigente 2025 | Desde 0.77% para creditos >$30M CLP |
| Ley 21.442 (2022) — Copropiedad | Facilitador | Vigente | Derecho individual a instalar cargador en estacionamiento propio; no requiere asamblea; obligatorio notificar comite + proyecto tecnico SEC |

Fuentes clave: BCN leyes; SII Informe Gasto Tributario; NotebookLM1/2; Factiva.

### Efectos de la Ley 21.305 (Eficiencia Energetica)

- 88% de los 19 importadores mejoraron rendimiento de su flota desde la regulacion
- Solo 45% (2024) y 47% (2025) cumplieron el estandar completo
- Rendimiento promedio vehiculos nuevos: +7.3% entre 2023-2025; 58% de esa mejora explicada por EVs
- Oferta BEV: triplo de 44 a 128 modelos entre 2023-2024
- Precio promedio BEV+PHEV: cayo 17%, de $56.7M a $47M CLP
- Debate: CMS lo atribuye a la ley; ANAC dice es solo "garrote a ICE" — El Mercurio, sep 2025

### CORFO — programas EV

| Programa | Alcance documentado |
|----------|-------------------|
| Mi Taxi Electrico | 670 taxis en Antofagasta, Atacama, O'Higgins y Biobio |
| +Transporte Electrico | 30 colectivos en Antofagasta, Maule, Los Lagos |
| Subsidio EV privado masivo | NO EXISTIO. CORFO solo subsidio taxi/colectivo — confirmado por ausencia en Factiva |
| Presupuesto total CORFO 2022 | MM$604,274 (todas lineas); sin linea especifica "electromovilidad" — DIPRES/CORFO |

- La caida de ventas en 2023 NO fue por fin de subsidio CORFO privado (nunca existio a esa escala)
- Causa principal alza 2024: entrada marcas chinas con precios sub-USD 20,000 + TLC China arancel 0%
- CORFO credito verde BancoEstado activo bajo gobiernos Boric (2021) Y Kast (mar 2026) — continuidad bipartidista — ValorFuturo, mar 2026

### Propuestas ANAC pendientes (presentadas formalmente a Hacienda)

- Exencion total IVA 19% → proyeccion +25% ventas
- Eliminacion arancel 6% para todos los EVs → reduccion de hasta $2M CLP por unidad
- Derogacion impuesto al lujo para EVs
- "Calendario movil" 8 anios beneficio permiso circulacion (quien compre hoy recibe 8 anios, no limite 2031)
- Diego Mendoza (ANAC): "Lo que proponemos es un calendario movil, que quien compre un auto electrico hoy tenga ocho anos de beneficio" — ANAC/Mendoza, feb 2026

### Proyecto de ley en tramitacion (marzo 2026)

- Proyecto de ley "Medidas Energeticas y Electromovilidad", ingresado 24 mar 2026, urgencia "Discusion Inmediata"
- Ministra Ximena Rincon (Energia, gobierno Kast)
- Contenido: linea credito preferencial BancoEstado taxis electricos; deducciones especiales PYMES; revision base imponible IVA para VE de trabajo
- Decreto Arancelario (arancel 0% todos EVs, eliminar problema origen bateria): reingresado a Contraloria, abr 2026
- Ruta Energetica 2026-2030: base para ley miselanea energia que extenderia beneficios Ley 21.505 post-2031
- Hacienda: situacion fiscal "critica" — probable que exencion IVA aplique solo a VE de trabajo/flotas en el corto plazo, no particulares — NotebookLM2

---

## CAP 5 — Efectividad de politicas

### Efecto Ley 21.305 (B — regulacion oferta)

- Correlacion fuerte entre entrada en vigor de la ley (2024) y boom de ventas (+183% BEV)
- Evidencia directa: oferta triplo (44→128 modelos), precio cayo 17% — El Mercurio, sep 2025
- La meta 2035 actua como senal de mercado que modifica comportamiento de importadores incluso sin subsidio directo — Diego Mendoza (ANAC), feb 2026

### Efecto Ley 21.505 (C — permiso circulacion)

- Ahorro real: CLP 200,000–350,000/anio para BEV de USD 30,000 — legal_gaps_research.md
- Evidencia europea: los "ownership incentives" (permiso, peajes) NO son efectivos para aumentar adopcion; los incentivos de COMPRA son mas efectivos — Martins et al. (2024), DiD 30 paises europeos
- Falla de implementacion: >4,000 usuarios reportaron que municipalidades les cobraron ilegalmente — La Tercera, abr 2024
- Costo fiscal exencion permiso circulacion: ~$3,500M CLP anuales para parque de ~4,500 BEV nuevos 2024

### Costo fiscal exencion IVA 19% Chile (estimacion)

| Base calculo | Unidades | Perdida IVA (MM CLP) | USD |
|---|---|---|---|
| Real 2024 | 4,507 BEV | ~$31,807 | ~USD 33.4M |
| Conservador (+20%) | 5,408 | $38,165 | — |
| Moderado (+50%) | 6,761 | $47,712 | — |
| Agresivo (x2) | 9,014 | $63,613 | — |

Represent ~0.01% del PIB 2024 — "cifra manejable" — NotebookLM2 / SII Informe Gasto Tributario 2024-2030.

### Que funciona segun la evidencia academica

- Incentivos de COMPRA (no de tenencia): Purchase incentives sí aumentan BEV y PHEV — Martins et al. (2024)
- Infraestructura de carga: 28/28 estudios confirman efecto positivo (Hardman, 2019); es el predictor mas robusto en cross-national analysis (Sierzchula, 2014): R2 cae de 62.3% a 53.3% sin infraestructura
- Incentivos fiscales: +$1,000 de incentivo → +0.06% market share (Sierzchula, 2014, p=0.039)
- Para Chile/Santiago especificamente: 72% dispuesto a comprar EV con exencion IVA; politica preferida sobre devolucion de impuesto a la renta — Urrutia-Mosquera et al. (2021), n encuesta Santiago
- Subsidios sin foco regresan: benefician principalmente a ingresos altos — Sheldon (2022); MIT SPR (2021)
- Demanda electrica media-baja muy elastica: −2.1 (10% reduccion precio → 21% aumento adopcion) — Muehlegger & Rapson (2022), California EFMP

---

## CAP 6 — Politicas internacionales por tipo

### Tipo C — Demanda: subsidios e incentivos fiscales

#### Colombia (el comparador LatAm mas relevante)

Serie temporal market share Colombia:
| Anio | Market Share EV (BEV+PHEV) | Hito |
|---|---|---|
| 2018 | 1.2% | Inicio transicion |
| 2019 | 1.4% | Promulgacion Ley 1964 |
| 2020 | 1.6% | Pandemia |
| 2021 | 1.8% | Paridad con Chile actual |
| 2022 | 2.1% | — |
| 2023 | 3.7% | Diversificacion modelos |
| 2024 | 7.5% | Tercer mercado LatAm |
| 2025 | 7.5%+ | 19,724 BEV matriculados (+115%); total electrificados: 87,623 |

Fuente: ANDI/FENALCO/RUNT; Bloomberg Linea; NotebookLM1; Factiva.

Paquete tributario Colombia vigente:
| Instrumento | Ley/Norma | Beneficio |
|-------------|-----------|-----------|
| IVA reducido 5% (vs 19%) + arancel 0% + impuesto vehicular max 1% | Ley 1964 (2019) | Reduccion precio compra y tenencia |
| Deduccion 50% valor adquisicion renta | Ley 1715 (2014) | Diferible hasta 15 anios |
| Exencion Pico y Placa en Bogota, Cali, Medellin | Ley 1964 + local | Reduccion costo uso diario |
| SOAT: 10% descuento; revision tecnicomecanica 30% descuento | Ley 1964 | — |
| Descuento impuesto vehicular: 60% en Bogota (5 anios); 70% para taxis | Local | — |
| FOPAT (scrappage taxis) | Programa Min Transporte, 2025-2026 | Subsidio $34.5M–$42M CLP equiv. (escalona por antiguedad) + credito $92M equiv. (5 anios + gracia) |
| Devolucion IVA retroactiva si se cobro | Concepto DIAN 000673, ene 2026 | Recuperacion retroactiva |

Fuentes: Factiva (Factiva-20260504-1240), Technocio/Publimetro Colombia 2025, Bloomberg Linea dic 2025.

- Chile vs Colombia: 1.87% market share Chile vs 7.5% Colombia (2024) — atribuido explicitamente al paquete de incentivos — Factiva 2025
- Exencion arancelaria puede representar hasta 35% de rebaja en precio final del vehiculo — Factiva Colombia 2025
- Ensenanza clave: el beneficio tributario permanente es mas efectivo que medidas puntuales — gremios colombianos (Andemos, Aconautos) rechazaron "Dia sin IVA" por insuficiente; pidieron rebaja permanente — Factiva abr 2023

#### Noruega (caso mas avanzado, Tipo C puro)

Cronologia exacta del paquete noruego:
| Anio | Hito |
|---|---|
| 1990 | Exencion impuesto de compra e importacion |
| 1996 | Exencion impuesto anual circulacion |
| 1997 | Exencion peajes carreteras y tuneles |
| 2001 | Eliminacion total del IVA (25%) |
| 2005 | Acceso gratuito a carriles de bus |
| 2009 | Exencion cargos ferries publicos |
| 2015 | Exencion 25% IVA en leasing |
| 2017 | Cuota de mercado EV llega al 20% |
| 2019 | Cuota de mercado EV llega al 50% |
| 2023 | IVA del 25% sobre porcion del precio que exceda 500,000 NOK (~USD 50,000) |
| 2025 | 95.9% de ventas son electricas; meta 100% alcanzada |
| 2026 | Umbral IVA baja a 300,000 NOK |

Fuente: Norwegian EV Association; OECD; European AFOE; NotebookLM1.

- El paquete noruego NUNCA incluyo un programa nacional de scrappage — Noruega = paradigma Tipo C fiscal — data_exploration / research_addenda
- Costo anual exencion IVA Noruega: NOK 17.5 mil millones (~EUR 1.5 mil millones/anio) — GlobalVATCompliance; lit_supplement
- Fase de salida gradual sin colapso de mercado: 94% market share con umbral NOK 500k; mercado maduro = subsidio puede retirarse gradualmente — lit_supplement
- Bjerkan et al. (2016) survey 3,342 compradores: driver #1 = precio (VAT+impuesto registro); #2 = costo operativo; #3 = beneficios no financieros (carril bus, peajes)
- Impuesto de registro exencion = ahorro NOK 50,000–200,000+ por vehiculo — legal_gaps_research
- Estabilidad politica >20 anios = critica: 70% de expertos noruegos quieren continuar incentivos (Kester et al., 2018)
- Figenbaum (2022): una vez que EV supera ~20-25% en un municipio, la adopcion se autofinancia sin subsidio (critical mass)

#### Francia — Bonus-malus y prime a la conversion (Tipo C + scrappage)

- Bonus ecologique 2023: hasta EUR 7,000 (ingresos ≤EUR 14,089/parte); EUR 5,000 (ingresos ~EUR 30,000); EUR 3,000 (altos); condicion: vehiculo <EUR 47,000
- Prime a la conversion (scrappage): hasta EUR 5,000 adicionales; condicion: chatarrar diesel pre-2011 o gasolina pre-2006 y comprar EV/HEV
- Combinacion maxima: hasta EUR 12,000 bonus+prime
- Malus ecologique 2023: umbral 123 g CO2/km; maximo EUR 50,000 para >=226 g CO2/km
- Sistema casi fiscalmente neutro: el malus financia el bonus — Ministere Transition Ecologique; L'Argus
- Market share France 2022: BEV 13.3%; BEV+PHEV 20%; 2023: 16.8% BEV; 26.2% BEV+PHEV — Avere-France
- Peiseler et al. (2022): feebate (bonus-malus) es la politica mas prometedora para reducir emisiones Y con mas probabilidad de ser adoptada

#### Alemania — Umweltbonus (Tipo C con riesgo de cancelacion abrupta)

- Activo: 2016 – diciembre 2023 (cancelado abruptamente por fallo Tribunal Constitucional sobre presupuesto)
- Pico 2020-2023: hasta EUR 9,000 (gobierno EUR 6,000 + fabricante EUR 3,000)
- Total pagado 2016-2023: ~EUR 10 mil millones
- Nuevo programa 2026: EUR 3,000–6,000 focalizado en ingresos ≤EUR 80,000/anio; EUR 3 mil millones para ~800,000 vehiculos 2026-2029
- Leccion critica: cancelacion abrupta → caida de mercado inmediata. El diseño de la salida gradual importa — EAFO; Cardino; research_addenda

#### Nueva Zelanda — Clean Car Discount (experimento natural mundial)

- Subsidio BEV nuevos: NZD 7,015 (~USD 4,200); BEV usados importados: NZD 3,507
- Vigente: 1 abril 2022 – 31 diciembre 2023 (cancelado por gobierno entrante)
- Costo total programa: NZD 636 millones gastados
- Market share antes (2018): 2%; durante (pico 2023): 27%; despues (enero 2024): ~3.8%
- Caida de 27% a 4% en un mes = experimento natural mas claro del mundo sobre sensibilidad al subsidio EV — NZ Transport Agency; Newsroom NZ
- Clean Car Standard (regulacion de oferta para importadores): permanecio vigente aunque el subsidio fue eliminado
- Relevancia para Chile: NZ es importador puro sin produccion automotriz = misma estructura que Chile

#### EEUU — IRA §30D Tax Credit (Tipo C)

- Credito tributario personal: USD 7,500 para BEV nuevos; USD 4,000 para usados
- Condiciones de fabricacion local aplican (limite transferibilidad directa a Chile)
- Costo fiscal proyectado: USD 70–390 billones durante una decada — Bistline et al. (2023), Science
- Reduccion emisiones con IRA: 43–48% bajo niveles 2005 al 2035 (vs 32% sin IRA) — Bistline et al. (2023)

### Tipo B — Restriccion ICE / mandatos

#### Union Europea — Reglamento 2023/851 (ICE ban 2035)

- Vigente desde 19 mayo 2023; prohibicion efectiva de ventas ICE nuevas el 1 enero 2035
- Objetivos intermedios: -55% CO2 para 2030, -100% para 2035
- Clausula e-fuels (Art. 14a): ICE post-2035 solo con combustibles neutros en carbono (concesion a Alemania)
- Aplica a todos los fabricantes que vendan en el mercado europeo, incluidos importados
- Fuente primaria: EUR-Lex, CELEX:32023R0851

#### China — NEV Dual Credit Mandate (Tipo A + B)

- NEV credit targets: 28% (2024); 38% (2025)
- Meta 2030: 60% penetracion NEV toda la flota vendida (65% pasajeros, 30% comerciales) — NotebookLM1
- China 2024: 15.33 millones NEV vendidos (+25%); 60% ventas globales EV — IEA GEO 2024
- Subsidios directos: USD 28 mil millones acumulados 2009-2022; terminaron fin-2022; reemplazados por exencion impuesto de compra extendida a 2027 — ICCT (2023)
- Liu et al. (2021): en sector privado, infraestructura de carga y restricciones de placa son mas efectivas que subsidios directos

### Tipo A — Orientadas a oferta (aplicabilidad limitada en Chile)

- China NEV mandate: irreplicable en Chile (importador puro; WTO TBT aplica)
- Clean Car Standard NZ: SI aplicable a Chile — regulacion para importadores de vehiculos, neutra en origen, no requiere produccion local
- Ley de Eficiencia Energetica 21.305 (Chile): ES una politica Tipo A/B ya operativa para importadores (ver Cap 4)

### Infraestructura de carga en edificios (right to plug)

- Alemania — WEMoG (vigente desde 01.12.2020): cualquier propietario puede solicitar cargador como "medida privilegiada"; comunidad no puede negarlo
- Francia — Loi LOM (Ley 2019-1428, Art. 34): "droit a la prise" desde 2020; obligacion de inscribir en asamblea en plazo maximo; edificios nuevos >10 plazas deben precablear 20%
- Directiva EPBD UE (2024/1275/UE): edificios nuevos >3 plazas deben pre-cablearse para 100%; existentes >5 plazas deben tener 1 punto antes de 2027
- Chile — Ley 21.442 (2022): derecho individual de instalar cargador en estacionamiento propio, no requiere asamblea, pero NO tiene plazo maximo de objecion = comunidad puede dilatar indefinidamente — gap vs Austria/EEUU (60 dias) y Francia (6 meses) — Tankou et al. (2023) / NotebookLM5
- Costos retrofit instalacion cargador nivel 2: USD 4,100 promedio EEUU (Pierce & Bui, 2024); EUR 410–2,038 en Francia con subsidio estatal (Tankou et al., 2023)
- 71% no compraria EV sin carga en edificio residencial — Kuby et al. (2025), citado en NotebookLM5
- Dato Chile 2025: 70% de las cargas se realizaran en hogares y edificios — EntrepreNerd, jul 2025; La Tercera, may 2025

---

## CAP 7 — Adaptatividad Chile

### Cuadro comparativo (datos para las celdas)

| Politica internacional | Tipo | Evidencia de impacto | Factibilidad legal Chile | Restriccion principal | Sí/No/Con ajuste |
|------------------------|------|---------------------|-------------------------|----------------------|-----------------|
| Exencion IVA 19% (Noruega/Colombia) | C | NOR: 95.9% market share; COL: 7.5% (vs 1.87% Chile) | Requiere enmendar Art. 12 DL 825 por ley; iniciativa exclusiva Presidente | Hacienda: situacion fiscal "critica"; costo estimado ~$31,807 MM CLP/anio a ventas actuales | Sí, con reforma tributaria; priorizar EV de trabajo en corto plazo |
| Subsidio directo a la compra (SEPP NL / bonus Francia) | C | NL: ~25-35% market share antes de fin del programa; Francia: 26% BEV+PHEV | Via CORFO + Ley de Presupuestos; no requiere nueva ley tributaria | Sheldon (2022): regresivo sin focalizar; necesita tope de precio e ingreso | Sí — via mas rapida disponible; implementable anualmente via presupuesto |
| Credito tributario renta (§30D EEUU) | C | EEUU: IRA reduce emisiones 43-48% vs baseline | Nuevo articulo LIR Art. 55 quater; iniciativa exclusiva Ejecutivo | No existe credito por compra de bienes de consumo en Chile; necesita voluntad politica Ejecutivo | Si, factible legalmente; requiere nueva ley LIR |
| Bonus-malus feebate (Francia/Alemania) | C/B | Francia: 16.8% BEV 2023; feebate = politica con mayor probabilidad adopcion (Peiseler, 2022) | Reforma DL 3063 (Rentas Municipales) o nuevo capitulo tributario; Art. 19 N20 CPR admite diferenciacion por criterio ambiental | Requiere reforma tributaria; politicamente mas difícil; precedente: impuesto verde vehiculos Ley 20.936 | Sí, con reforma tributaria; mas sostenible fiscalmente que subsidio puro |
| Exencion arancel 6% para todos EV (no solo chinos) | C | Ahorro hasta $2.1M CLP/vehiculo; Factiva: importadores europeos/japoneses discriminados | Decreto arancelario; ya en Contraloria desde abr 2026 | Baterias de paises distintos a pais fabricacion superan limite TLC (45% componentes) | Sí — propuesta ANAC activa; vía mas rapida; decreto sin Congreso |
| NEV mandate cuota (China) | A | China: 60% NEV global, 30.2% market share 2023 | Ley ordinaria o norma emision DS bajo Ley 19.300 Art. 32; WTO-neutral si aplica a todos importadores igual | Chile importador puro sin produccion domestica; WTO Art. III:4 no aplica (no hay producto domestico) = factible si es neutral en origen | Sí — modelo Clean Car Standard NZ es la forma mas robusta |
| Prohibicion ventas ICE 2035 (UE/UK) | B | UE: -55% CO2 para 2030 como objetivo intermedio | DS bajo Ley 19.300 Art. 32 (norma cero emisiones, como Euro 6 en 2019 via DS 130/2019); o Ley Electromovilidad en Congreso | Anuncio en 2026 con vigencia 2035 = 9 anios lead time (comparable a UE); Art. 19 N21 CPR: OK con lead time suficiente | Sí, via regulatoria (decreto) o statutory (ley); anunciar ya para senal de mercado |
| Mandato flota publica | B | Santiago = 2da mayor flota e-buses del mundo; ahorro USD 258M/anio | DS 1363/2014 (Hacienda): enmienda decreto para adquisiciones estado 100% ZEV; sin Congreso | Ya parcialmente implementado para buses; extension a flota sedan/camionetas del Estado | Sí — vía mas rapida; implementable por decreto |
| Scrappage para vehiculos particulares (Francia/Colombia FOPAT) | C | NZ: caida 27% → 4% sin subsidio = subsidio es conditio sine qua non; Colombia FOPAT: $42M subsidio escalado por antiguedad del taxi | Via CORFO + Ley Presupuestos para taxi/colectivo; extension a particulares requeriria nueva linea presupuestaria | Chile solo tiene scrappage para taxis colectivos (Ley 20.378 / RTC) en 5 regiones extremas + $9.7M EV; no existe para particulares | Sí para taxi/colectivo (ampliar RTC); para particulares — propuesta nueva sin base legal actual |
| Right to plug / carga en edificios (Francia/Alemania) | Facilitador | 71% no compraria EV sin carga en edificio (Kuby, 2025); 70% de cargas seran residenciales | Ley 21.442 ya reconoce el derecho; falta plazo maximo de objecion (Austria/EEUU: 60 dias; Francia: 6 meses) | Chile tiene derecho pero sin limite temporal de objecion = comunidad puede dilatar; gap concreto | Sí — modificacion menor a Ley 21.442 para fijar plazo maximo de 60 dias (sin reforma tributaria) |
| Tarifa electrica preferencial para cargadores (facilitador infraestructura) | Facilitador | Cargo por demanda maxima encarece cargadores con baja utilizacion: CLP $5,914–$7,343 por kW/mes | CNE tiene facultad regulatoria; Resolucion Exenta N565/2023 fue primer paso; reforma hacia tarifa por kWh (bloque horario) pendiente | Actualmente: cargador con baja utilizacion paga como si operara 24/7 → inviable economicamente en mercado incipiente | Sí — cambio regulatorio CNE; no requiere ley |

### Viabilidad legal Chile — resumen ejecutivo

| Via | Instrumentos posibles | Velocidad | Requiere Congreso |
|-----|----------------------|-----------|-----------------|
| Decreto arancelario | Arancel 0% todos EV (ya en Contraloria) | Inmediato | No |
| Ley de Presupuestos CORFO | Subsidio directo, focalizado | Anual | No |
| Enmienda DS 1363 (flota publica) | Mandato ZEV compras estado | Inmediato | No |
| DS bajo Ley 19.300 Art. 32 | Norma cero emisiones 2035 | Meses | No |
| Reforma Ley 21.442 (plazo objecion cargadores) | Right to plug con limite temporal | Meses | Sí (menor) |
| Reforma DL 825 Art. 12 (IVA) | Exencion IVA | Lenta | Sí (iniciativa exclusiva Presidente) |
| Nuevo Art. 55 quater LIR | Credito tributario renta | Lenta | Sí (iniciativa exclusiva Presidente) |

### Costo fiscal exencion IVA Chile (estimacion)

- Base 2024 (4,507 BEV a $44.2M CLP promedio): perdida ~$31,807 MM CLP = ~USD 33.4M = ~0.01% del PIB
- "Una cifra manejable dentro del presupuesto nacional" — NotebookLM2 / SII Informe Gasto Tributario

### Marco regulatorio edificios (Ley 21.442 / right to plug)

- Art. 11: derecho individual a instalar cargador en estacionamiento propio; no requiere asamblea
- Protocolo: notificacion escrita al comite + proyecto tecnico SEC (Pliego RIC N15)
- Brecha vs Europa: Chile NO tiene plazo maximo de objecion del comite; Austria y EEUU: 60 dias; Francia: 6 meses
- Edificios nuevos: deben proveer canalizaciones para 100% de estacionamientos — Ley 21.442 / MINVU
- Instalacion Wallbox inteligente: CLP $800,000–$1,500,000 (costo privatamente, sin subsidio estatal actual) — NotebookLM2

---

## Citas clave para el argumento

Las 12 citas mas poderosas del ensayo, listas para citar en APA:

1. "We need public policies that allow citizens to access this technology in a tangible way. The 2035 goal will only be possible if we move from intention to action today." — Rodrigo Espinoza, Volvo Cars Chile, Congreso Futuro 2026 (El Mostrador, 30 enero 2026).

2. "Financial incentives are no longer the reasons for huge differences over countries — fiscal incentives, charger density, and income all have significantly positive effects on penetration of EVs." — Xue et al. (2021), Sustainability, panel 20 paises 2015-2019.

3. "Removing charging infrastructure from the model reduces its explanatory power by 9 percentage points [from 62.3% to 53.3%]." — Sierzchula et al. (2014), Energy Policy, OLS 30 paises.

4. "If subsidies had been discontinued in 2017, half of below-median-income new vehicle buyers would not have adopted a PEV." — Sheldon & Dua (2023), Energy Economics.

5. "72% of respondents in Santiago are willing to purchase an EV with a VAT exemption... the preferred policy is 'exemption from VAT and any tax on purchase' over an income tax rebate." — Urrutia-Mosquera et al. (2021), Case Studies on Transport Policy, encuesta Santiago, n suficiente.

6. "Un mandato de participacion de vehiculos de cero emisiones aplicado uniformemente a todos los importadores independientemente del pais de origen no viola el articulo III:4 del GATT 1994... Nueva Zelanda, pais importador puro sin produccion automotriz, implemento un estandar equivalente sin objeciones exitosas de ningun Miembro de la OMC." — legal_gaps_research.md (sintesis legal verificable).

7. "La exencion del IVA requeriria modificar el articulo 12 del Decreto Ley N 825... dicha modificacion requiere ley simple de iniciativa exclusiva del Presidente de la Republica conforme al articulo 65 inciso cuarto N 1 de la Constitucion Politica." — legal_gaps_research.md.

8. "Once EV market share passes critical mass (~20-25% in a municipality), adoption becomes self-reinforcing even if subsidies were removed." — Figenbaum (2022), Energy Economics.

9. "Chile's investment pattern is electric buses — not private EVs." — Arowolo & Perez (2026), Transportation Research Interdisciplinary Perspectives, 15-country comparative study.

10. "Chile should be leading electrification in South America but is falling behind." — titular Factiva (⚠️ verificar fuente exacta).

11. "En Colombia, un gran incentivo es que los electricos pueden circular todos los dias, mientras que los autos a combustion solo dia por medio." — Diego Mendoza, Secretario General ANAC, feb 2026.

12. "The introduction of a new Bonus-Malus Registration Scheme [is] among the most promising changes both in terms of potential to reduce emissions and likelihood of adoption." — Peiseler et al. (2022), Energy Policy.

---

## Gaps que siguen abiertos (no bloquean la escritura)

| Gap | Impacto en ensayo | Alternativa |
|-----|-----------------|-------------|
| Distribucion cargadores 16 regiones individuales | Bajo | Usar dato RM (332) + "77% de potencia instalada en RM" + "60% comunas sin cargador" |
| Presupuesto CORFO electromovilidad desglosado | Bajo | Citar unidades por programa (670 taxis, 30 colectivos) en lugar de monto total |
| Costo fiscal IVA Colombia aislado | Bajo | Usar comparacion cualitativa; cifra de ventas Colombia suficiente para argumento |
| Boletin especifico exencion IVA EV Chile en tramitacion | Bajo | Citar proyecto Rincon (mar 2026) con contenido sin numero de boletin; mencionar propuesta ANAC formal |
| Tasa retiro ICE anual exacta por anio | Bajo | Usar rango 250,000–350,000 vehiculos/anio con fuente industria |
