# Inventario de Investigación — EV Chile Essay
**Fecha:** 2026-05-04
**Elaborado por:** Research Agent (síntesis de 11 archivos de investigación)
**Archivos base:** research_spec, profesor_feedback, data_exploration, lit_review, lit_supplement, research_addenda, legal_gaps, factiva_findings (4 rondas)

---

## Resumen ejecutivo

El repositorio de investigación está muy bien desarrollado en datos de mercado (Cap 3), literatura comparada de políticas internacionales (Cap 6), y marco legal chileno (Cap 7). Los capítulos más débiles en evidencia son Cap 2 (definición técnica — delegado a literatura general), Cap 4 (políticas actuales — CORFO aún sin cifras precisas), y Cap 5 (efectividad — sin contrafactual cuantitativo). El Cap 7 tiene cobertura excelente en la dimensión legal pero le falta el cuadro de adaptatividad completo con datos de costo fiscal de las medidas propuestas para Chile.

---

## Cap 1 — Introducción y pregunta de investigación (~600 palabras)

### ✅ Cubierto

| Elemento | Dato/fuente |
|----------|-------------|
| Pregunta de investigación aprobada por tutor | "¿Qué políticas públicas pueden ayudar a Chile a propulsar la adopción masiva de EVs en el segmento privado?" (professor_feedback.md) |
| Motivación empírica: brecha adopción | Chile 1,87% mercado 2024 vs. Colombia 7,5%, Costa Rica 15%, Uruguay 13% (Factiva-05-04b) |
| Motivación empírica: meta 2035 | 100% ZEV nuevas ventas al 2035 (Estrategia Nacional Electromovilidad 2022) |
| Contraste buses/privado | Santiago #2 mundial en buses eléctricos (55% flota), privados en 1,87% (El Mostrador ene 2026) |
| Posición Chile en LatAm | 4to en infraestructura de carga total (Martínez-Gómez & Espinoza 2024) |
| Marco analítico de 3 barreras | B1 (parque viejo), B2 (infraestructura concentrada + tarifa demanda), B3 (crédito caro/escaso) |
| Argumento leapfrogging | Ember 2024, Gallagher 2022 — ventaja Chile: renovables 68% + TLC China |
| Disposición a comprar | 56% chilenos compraría EV/HEV (encuesta Descifra n=1.621, La Tercera nov 2025) |

### ❌ Falta

- Ningún dato crítico falta para la introducción; todos los elementos ancla están disponibles.

### ⚠️ Parcialmente cubierto

- La frase "Chile debería liderar la electrificación en Sudamérica, pero se está quedando rezagado" aparece en Factiva pero sin autor/fecha verificada. Hay alternativas equivalentes con cita completa (Rodrigo Espinoza, Volvo Cars Chile, Congreso Futuro 2026).

---

## Cap 2 — ¿Qué es un vehículo eléctrico? Definición y tipos (~400 palabras)

### ✅ Cubierto

| Elemento | Dato/fuente |
|----------|-------------|
| Taxonomía BEV/PHEV/HEV/MHEV/FCEV | Usada consistentemente en ANAC, Statista, lit review — categorías claras |
| Diferenciación legal chilena BEV vs. PHEV | Ley 21.505: exime solo BEV/FCEV, excluye PHEV — legal_gaps.md §2.4 |
| Dato de serie temporal por categoría 2024–2025 | ANAC Diciembre 2024 + Estrategia/Ene 2026 — desagregado en lit_supplement y factiva_22 |
| Referencia técnica a autonomía, conectores | Martínez-Gómez & Espinoza 2024 (tipos de conector en Chile: CCS, CHAdeMO, Type2, GB/T) |

### ❌ Falta

- No hay fuente académica específica que defina y clasifique los tipos de EV para propósitos de política pública (se usa terminología de la industria, no académica). Esto es un gap menor — no afecta el argumento pero debilita la precisión conceptual del capítulo.
- No hay definición de "adopción masiva" — el ensayo usa la meta del 100% en 2035 como proxy, pero no hay cifra umbral ("masiva" = ¿20%? ¿50%?) citada desde algún autor.

### ⚠️ Parcialmente cubierto

- La distinción entre adopción en stock (flota total) vs. flujo (ventas nuevas) existe en los datos pero no está articulada como marco conceptual del capítulo. Falta 1 oración definitoria que ancle la diferencia para lectores no especializados.

---

## Cap 3 — Adopción y situación actual en Chile: proyecciones, enablers, impedimentos (~1.500 palabras)

### ✅ Cubierto (sólido)

| Elemento | Dato/fuente |
|----------|-------------|
| Serie ventas BEV+PHEV 2019–2024 | Tabla completa: 294 → 6.206 unidades (Statista CSV + ANAC dic 2024) |
| Boom 2024: +183,8% BEV | ANAC Diciembre 2024; explicado por Ley 21.305 + marcas chinas |
| Datos 2025 ene–nov | 4.717 BEV (+27–34%), 31.208 electrificados totales (+92,5%) (Estrategia ene 2026) |
| Market share 2024 | ~1,87% (Factiva-05-04b) o ~3% (Statista) — RECONCILAR (ver nota abajo) |
| Flota total y composición | 6,12M vehículos 2022 (INE), 80% gasolina, 1% BEV (Statista survey 2024) |
| Edad promedio flota | 9,4 años nacional, 7,6 años RM, 13,4 años Arica y Parinacota (ANAC 2023) |
| Ventas usados vs. nuevos | 963.363 transferencias usados vs. 319.568 nuevas (ratio 3:1, Autofact 2023) |
| Importación autos usados | 58.089 unidades en 2021 (+118%), edad promedio 11 años, 60% japoneses (La Tercera/El Mercurio sep 2022) |
| Precio BEV Chile | USD 64.900 BEV promedio 2024 (Statista); entrada ~$11,99M CLP (Renault Kwid, Factiva); caída 17% promedio 2023→2025 (El Mercurio sep 2025) |
| Número de modelos BEV | 44 modelos 2023 → 128 modelos 2024 (El Mercurio sep 2025, Ley 21.305 efecto) |
| Ahorro operacional EV | $2 millones CLP/año vs. gasolina en contexto 2026 (El Mercurio abr 2026, Olacde) |
| 96% satisfacción dueños EV | Volvo/Cadem, septiembre 2025 (Factiva-24) |
| Infraestructura de carga | 396 estaciones públicas (definición SEC/estaciones físicas); ~1.200 conectores totales 2024 (lit_supplement) |
| Distribución geográfica cargadores | 60% de comunas sin cargador público (CMS, La Tercera mar 2026); RM >75% del total |
| Densidad comparativa | Chile ~0,062 por 1.000 hab vs. Netherlands 10,04 → brecha 162x (calculado en data_exploration) |
| 70% carga en hogar | Volvo/Cadem (Factiva-24); 85% considera insuficiente la red pública |
| Tarifa de demanda como barrera | Enerlink CEO (BioBio, abr 2026): vicious cycle con baja utilización → triple costo kWh |
| Crédito automotriz tasa | 0,79–1,65% mensual (9,9–21,6% CAE anual), down payment 20–30% (Tasas.cl / Autofact) |
| 80% de autos comprados con crédito | El Mercurio sep 2024 (gerente BYD Auto Chile) |
| Penetración LatAm comparada | LatAm ~4% promedio 2024 (IEA GEO 2025); Chile subperforma la región |
| Chile #2 buses eléctricos | 4.400+ buses, 55% flota Santiago (C40 Cities 2023, El Mostrador ene 2026) |
| Barreras declaradas por consumidores | Precio (18%), infraestructura (20%), autonomía (19%), batería (17%) — encuesta Descifra n=1.621, diferenciadas por NSE |
| Posición en LatAm | 4to en cargadores (Martínez-Gómez & Espinoza 2024: Brasil 3.800 > México 2.083 > Costa Rica/Colombia > Chile 1.032) |
| Arancel diferencial actual | EV no chinos pagan 6% (avg $1,8M CLP por unidad); chinos a 0% bajo TLC. EVs = 40% de recaudación arancelaria automotriz (El Mercurio dic 2024) |

### ❌ Falta

| Gap | Por qué es necesario | Archivo donde debería estar |
|-----|---------------------|---------------------------|
| Penetración EV por región (no solo RM) | El argumento de concentración geográfica necesita datos de ventas/matriculaciones por región, no solo de cargadores | INE Registro Civil o ANAC por región |
| Distribución ingreso quintiles (CASEN) | Para cuantificar el gap de acceso en quintiles 1–3 frente al precio mínimo de EV | CASEN 2022 (datos de ingreso por quintil); pendiente desde data_exploration |
| Tasa de retiro del parque ICE (ICE retirement rate) | Para modelar cuánto tiempo tarda la renovación del stock incluso si ventas nuevas = 100% EV | INE Permisos de Circulación (bajas anuales) |
| Distribución de edad del parque por cohorte | "9,4 años promedio" no dice cuántos vehículos tienen >15 años | INE Parque de Vehículos por año de fabricación |

### ⚠️ Parcialmente cubierto

- **Reconciliación de cifra market share 2024:** Statista dice ~3%, Factiva/El Mostrador dice 1,5–1,87%, ANAC Diciembre 2024 dice 2,2–3,5% para BEV+PHEV. La discrepancia es por definiciones (solo BEV, BEV+PHEV, solo ventas nuevas). Hay que fijar UNA cifra con definición explícita y citar la fuente. El 1,87% de Factiva-05-04b (fuente: Bloomberg Línea comparativa) y el 2,8–3% de ANAC (incluyendo PHEV) son las dos cifras más citables.
- **Tasa del crédito BancoEstado para EV (particulares):** Existe el producto pero sin tasa concreta para personas naturales. Solo confirmada para taxis/colectivos.

---

## Cap 4 — Políticas públicas actuales en Chile (~1.000 palabras)

### ✅ Cubierto

| Política | Elemento cubierto | Fuente |
|---------|------------------|--------|
| Ley 21.505 (2022) | Texto completo, alcance (solo BEV/FCEV, excluye PHEV), exención permiso circulación, cronograma (100%→75%→50%→0% en 2031), costo municipal, sin evaluación ex-post | legal_gaps §2.4 + Factiva múltiples |
| Estrategia Nacional Electromovilidad (2022) | Meta 100% ZEV al 2035, documento oficial | Ministerio Energía (lit_review) |
| Ley 21.305 (Eficiencia Energética, 2021) | Vigente para vehículos desde 2024; 88% importadores mejoraron rendimiento; 45–47% cumple estándar; triplicó modelos BEV; cayó precio 17% | El Mercurio sep 2025 (Factiva-22) |
| Impuesto verde (Ley 20.936/21.210) | BEV pagan 0 (vs CLP 150–200K/año para ICE); ventaja competitiva CLP 350–550K/año combinada con Ley 21.505 | legal_gaps §P5 |
| TLC Chile-China, arancel 0% BEV chinos | BYD, SAIC, Chery entran a 0%; EVs no chinos pagan 6%; explica ventaja precio chino | legal_gaps §P6 + El Mercurio dic 2024 |
| Programa "Mi Taxi Eléctrico" / "Mi Colectivo Eléctrico" | Subsidio CLP ~$13M + crédito BancoEstado + cargador domiciliario 100% financiado; en operación desde 2021; expandido a regiones (Antofagasta 2024, O'Higgins 2023) | Factiva-24 (Chócale, Norte y Energía) |
| "Renueva Tu Colectivo" (Ley 20.378, desde 2009) | Montos 2026: EV $9.7M CLP + bono chatarrización $1.8M (solo 5 regiones extremas); aplica solo taxis colectivos | Factiva-05-04b (Diario Oficial) |
| Programa buses RED Santiago | 4.400+ buses eléctricos; base legal Ley 20.378 + contratos concesión MTT; CORFO avales; sin nueva legislación | legal_gaps §P7 |
| BancoEstado crédito verde | Línea activa desde 2021; confirmada continuidad bajo gobierno Kast (mar 2026); solo para transporte remunerado (taxis/colectivos), no particulares | Factiva-05-04 |
| Propuesta ANAC "calendario móvil" | 8 años de beneficio permiso circulación (móvil, no fecha fija al 2031) | Factiva-22 §A5 + Factiva-24 §B2 |
| Acuerdo Público-Privado Electromovilidad 2025 | Agencia Sostenibilidad Energética — compromisos renovados | lit_review (Agencia SE 2025) |
| Reforma fiscal verde (Hacienda, evaluación) | Ministro Marcel confirmó evaluación extensión en reforma fiscal verde, antes del fin del gobierno | El Mercurio mar 2025 (Factiva-24) |

### ❌ Falta

| Gap | Por qué es necesario | Fuente potencial |
|-----|---------------------|------------------|
| Presupuesto ejecutado del programa Mi Taxi Eléctrico (monto total gastado) | Para dimensionar el nivel de inversión pública y comparar con Colombia/Francia | DIPRES Ley de Presupuestos; CORFO informes anuales |
| Número total de créditos BancoEstado entregados para EVs | Para evaluar cobertura real del programa; actualmente solo se saben lotes parciales (50, 175, 59 unidades) | BancoEstado memoria anual o nota de prensa específica |
| Tasa concreta del crédito BancoEstado para EV | La tasa "preferencial" nunca fue cuantificada en ningún artículo Factiva | Producto BancoEstado o Reglamento Operativo CORFO |
| Evaluación ex-post Ley 21.505 (DIPRES) | Sin contrafactual, el debate entre CMS y ANAC (correlación vs. causalidad) no se puede zanjar | DIPRES informe de evaluación; BCN historial legislativo |
| Texto completo Ley de Eficiencia Energética (Ley 21.305) + reglamento vehículos | Para confirmar que los estándares son Tipo B vinculantes, no solo metas indicativas | BCN: https://www.bcn.cl/leychile/navegar?idNorma=1157988 |

### ⚠️ Parcialmente cubierto

- CORFO como entidad: sus roles en electromovilidad están documentados (taxis, buses, avales), pero **no existe ningún artículo Factiva ni fuente primaria que confirme un programa CORFO de subsidio a VE privado masivo para el público general**. El único hallazgo (Santelices, La Tercera abr 2025) confirma que "algo ha estado hasta ahora fuera de la política pública, excepto en el caso de los taxis y colectivos". Esto es un hallazgo en sí mismo para el Cap 4/5.

---

## Cap 5 — Respuesta a esas políticas: ¿han favorecido la adopción? (~1.000 palabras)

### ✅ Cubierto

| Elemento | Dato/fuente |
|----------|-------------|
| Boom 2024 atribuido a Ley 21.305 (debate CMS vs ANAC) | CMS: "correlación muy fuerte"; ANAC: "solo un garrote a la combustión" — El Mercurio sep 2025 |
| Caída 2023 explicada (906 BEV) | Fin del subsidio CORFO a privados + supply chain; reconstruido como hipótesis en legal_gaps §P1 |
| Efecto Ley 21.505 (cuantificado) | Solo CLP 200–350K/año/vehículo; modesto vs. precio; falla de implementación municipal documentada (La Tercera abr 2024) |
| Efecto Ley 21.305 (cuantificado) | 88% de importadores mejoraron rendimiento; modelos triplicados 44→128; precio bajó 17% (El Mercurio sep 2025) |
| Meta 2035 como señal de mercado (efecto Tipo B) | ANAC: "Gracias a esa meta y a la Ley de Eficiencia Energética, las marcas están apostando fuerte" (Diego Mendoza feb 2026) |
| Ownership incentives no son efectivos | Martins et al. 2024 (DiD 30 países): incentivos de posesión (permiso circulación, peajes) no aumentan adopción. Solo incentivos de COMPRA funcionan |
| Prematuridad de retirar subsidios | NZ caso extremo (27% → 4% en un mes) — research_addenda §GAP8 |
| Efecto de instabilidad incentivos | Denmark VAT phase-out collapse — Kester et al. 2018; Yao et al. 2024 (China subsidy removal) |
| 96% satisfacción dueños | Demand-side pull exists; supply/price/credit = binding constraint |

### ❌ Falta

| Gap | Por qué es necesario | Fuente potencial |
|-----|---------------------|------------------|
| Contrafactual de la Ley 21.505 | Sin datos de ventas EV antes/después de feb 2022 (mes de promulgación) con suficiente granularidad mensual, no se puede estimar el efecto causal | ANAC boletines mensuales 2021–2023 (descargar serie) |
| Presupuesto y uptake del programa "Mi Taxi Eléctrico" (total acumulado) | Para establecer si el crédito BancoEstado tuvo impacto a escala | BancoEstado / DIPRES |
| Ventas EV por mes 2023 (para mostrar que la caída es gradual, no un shock) | Hace la narrativa de "fin de subsidio" más convincente | ANAC boletines mensuales |

### ⚠️ Parcialmente cubierto

- La causalidad de la Ley 21.305 sobre el boom 2024 es sugerida por temporalidad pero no establecida. El debate CMS vs. ANAC existe en Factiva pero ninguna fuente tiene el contrafactual econométrico. El ensayo debe presentar esto como evidencia observacional con caveats explícitos.
- El efecto del TLC Chile-China sobre precios BEV es implícito (marcas chinas entran a 0%) pero no hay cuantificación directa del counterfactual "¿cuánto costaría el Renault Kwid con arancel del 6%?" — ese cálculo se puede hacer con los datos disponibles (precio × 6% = ~$900K CLP).

---

## Cap 6 — Políticas internacionales exitosas por TIPO (~2.000 palabras)

### Tipo A — Orientadas a productores (mandatos NEV/ZEV, estándares flota)

#### ✅ Cubierto

| País/Política | Elemento cubierto | Fuente |
|--------------|------------------|--------|
| China NEV Dual Credit System | Descripción técnica completa (cuotas 10%→38%); costo total subsidios USD 28B 2009–2022; 30.2% market share 2023 | ICCT 2023 + Hao 2014 + lit_review |
| Nueva Zelanda Clean Car Standard | Estándar CO₂ promedio importadores; permanece vigente aunque subsidio fue eliminado | research_addenda §GAP8 |
| UE Regulation 2023/851 (ICE ban 2035) | Texto oficial, metas -55% CO₂ 2030 / 0% 2035; cláusula e-fuels Art. 14a | research_addenda §GAP2 |
| California ZEV mandate | Mencionado en spec como referencia; no desarrollado en detalle |
| Ley 21.305 Chile como Tipo B | Chile tiene su propia política Tipo B ya en efecto (Factiva-22) |

#### ❌ Falta

| Gap | Por qué es necesario | Fuente potencial |
|-----|---------------------|------------------|
| Cifras de cumplimiento del NEV mandate en China por año | Para mostrar que el mandato "funciona" (share actual vs. cuota mandatada) | ICCT China tracker 2024; DieselNet |
| Efecto UE ban 2035 en ventas anticipadas (lead-up effect) | Para ilustrar que anunciar la meta mueve el mercado antes de su entrada en vigor | EAFO datos 2022–2024 |

### Tipo B — Restricción ICE / feebate

#### ✅ Cubierto

| País/Política | Elemento cubierto | Fuente |
|--------------|------------------|--------|
| France Bonus-Malus Écologique | Descripción completa: bonus hasta €7.000 (focalizado por ingreso), malus hasta €50.000 para >226g CO₂/km, casi neutralidad fiscal | research_addenda §GAP7 |
| France Prime à la Conversion | Scrappage hasta €5.000 (acumulable con bonus); condición: chatarrar diesel pre-2011 o gasolina pre-2006 | research_addenda §GAP7 |
| France cifras de mercado | 13.3% market share BEV 2022; ~16.8% 2023 (lit_supplement) |
| Germany Umweltprämie | 2016–2023; hasta €9.000 pico COVID; cancelación abrupta dic 2023; total €10B pagados | research_addenda §GAP3 |
| Germany cancelación y caída | Caída post-cancelación → recuperación; nuevo programa 2026 focalizado ingresos ≤€80K | research_addenda §GAP3 |
| New Zealand feebate (Clean Car Discount) | Caso extremo: 2%→27% con subsidio → 4% al mes de quitarlo (NZD $636M gastados) | research_addenda §GAP8 |
| Peiseler et al. 2022 | Bonus-Malus como "most promising" según stakeholders europeos | lit_supplement |
| Ramji et al. 2024 | 13 elementos de diseño de un feebate efectivo; "leapfrogging" mencionado | lit_supplement |

#### ❌ Falta

| Gap | Por qué es necesario | Fuente potencial |
|-----|---------------------|------------------|
| Resultado cuantificado del feebate francés en reducción de emisiones | Para completar el argumento de "efectividad" no solo de adopción EV sino de impacto ambiental | ADEME France informes anuales; Avere-France |
| Comparación recaudación malus vs. gasto bonus en Francia por año | Para el argumento de "neutralidad fiscal aproximada" con datos reales | Ministère de la Transition Écologique presupuesto verde |

### Tipo C — Orientadas a demanda (subsidios, créditos, exenciones)

#### ✅ Cubierto (MUY SÓLIDO)

| País/Política | Elemento cubierto | Fuente |
|--------------|------------------|--------|
| Noruega: VAT + reg tax exemption | Mecanismo completo; VAT 25%→0%; impuesto registro equivale a ~50% precio ICE; cronograma de salida gradual 2022–2027; 94% market share ene 2026 con subsidio reduciéndose | OECD 2021 + Bjerkan 2016 + Figenbaum 2022 + Pfaffenbichler 2024 + lit_supplement |
| Noruega: no scrappage (CORRECCIÓN) | Confirmado: Noruega NUNCA tuvo scrappage; su éxito es Tipo C fiscal puro | research_addenda §Corrección 1 |
| Noruega: non-financial incentives | Bus lane, toll, ferry, parking (Hardman 2019: 28/28 estudios infraestructura positiva) | lit_review |
| Noruega: phase-out gradual sostenible | NOK 17.5B/año costo; 94% share a pesar de reducción | lit_supplement §DATOS NORWAY 2025–27 |
| Noruega: sin subsidio = 100% market power (Jan 2025) | Confirmado por Yang et al. 2023 + Pfaffenbichler 2024 |
| EEUU IRA §30D | $7.500 USD por BEV nuevo; $4.000 usado; reducción emisiones 43–48% proyectada; costo fiscal $70–390B/década | research_addenda §GAP1 + Bistline 2023 |
| Netherlands SEPP | Subsidio €2.950–4.000 (2020–2024); tope precio €45.000; agotado frecuentemente; terminó dic 2024 | research_addenda §GAP5 |
| Netherlands: demand-led charging rollout | "Derecho a cargador" (250m de domicilio); 10.04 charge points/1.000 hab; 1:5 charger-to-EV ratio | Wolbertus 2018 + Guidehouse 2021 + data_exploration |
| Colombia Ley 2099 (2021) | IVA 5% (vs 19% general); arancel 0%; impuesto vehicular máx 1%; deducción 50% renta; SOAT 10% descuento; Pico y Placa exención | research_addenda §GAP4 + Factiva-05-04b |
| Colombia FOPAT (2025) | Scrappage taxis: subsidio $34.5M–$42M CLP equiv. + crédito $92M/vehículo, 5 años; fondo total $14.800M | Factiva-05-04b |
| Colombia cifras de adopción | 2025: 19.724 BEV nuevos (+115%); 87.623 electrificados total; 7.5% penetración parque nuevo; Medellín 10.6% | Factiva-05-04b (Bloomberg Línea / El Colombiano) |
| Colombia: IVA permanente > puntual | Gremios colombianos confirman que IVA permanente es más efectivo que "Día sin IVA" | Factiva-05-04b (Technocio/Petro DAY sin IVA) |
| China subsidios directos | USD 28B total 2009–2022; cancelados dic 2022; post-subsidio: mandato + exención impuesto compra | Hao 2014 + ICCT 2023 |
| Singapore EV Early Adopter Incentive | SGD 45.000 rebate; COE reduction; demand rush documentado antes de reducción | Factiva-22 (Singapore Ministry of Transport sep 2025) |
| Sheldon 2022 + Sheldon & Dua 2023 | Subsidios regresivos sin focalización; pero necesarios para ingresos medios-bajos | lit_supplement |
| Urrutia-Mosquera et al. 2021 (Santiago) | 72% dispuesto con exención IVA; 76% con exención IVA para híbrido; política preferida: exención IVA > devolución renta | lit_supplement |
| Muehlegger & Rapson 2022 | Elasticidad precio EV ingresos medios: -2.1; pass-through 73–85% | lit_review |
| Martins et al. 2024 (30 países DiD) | Purchase incentives sí funcionan; ownership incentives (permiso, peaje) NO aumentan adopción | lit_supplement |
| Xue et al. 2021 (20 países panel) | Tax reduction + charger density + income → significativamente positivos; no suficientes solos | lit_supplement |

#### ❌ Falta

| Gap | Por qué es necesario | Fuente potencial |
|-----|---------------------|------------------|
| Costo fiscal de la exención IVA Noruega por año (en NOK) como % PIB | Para comparar con el esfuerzo fiscal que Chile tendría que hacer | Statsbudsjettet Norway (presupuesto) — ya se sabe NOK 17.5B/año anual (lit_supplement), falta % PIB |
| China: ventas EV post-cancelación subsidio (2023) | Para mostrar que el mandato sostuvo el mercado sin subsidio | ICCT 2023 tiene el dato (30.2% en 2023) — YA EXISTE |
| Efecto del crédito tributario §30D EEUU en ventas EV por segmento de ingreso | Para el argumento de que EEUU es efectivo pero regresivo | CBO o EIA datos 2023–2024 |

### ⚠️ Parcialmente cubierto en Cap 6

- **Singapore:** Está mencionado como caso relevante (importador puro, alta densidad, COE mechanism) pero solo hay un artículo Factiva de sep 2025 sobre el efecto anticipación. Falta descripción completa del EEAI y su efecto cuantificado en market share.
- **Korea:** Mencionado en Hardman 2019 como caso de incentivos no financieros (IVA, scrappage) pero no hay desarrollo propio en ningún archivo. No es crítico dado que Colombia + NZ cubren el espacio comparado.

---

## Cap 7 — ¿Pueden estas políticas aplicarse en Chile? Análisis de adaptatividad (~2.000 palabras)

Este es el capítulo más valioso del ensayo. La cobertura es la más trabajada.

### ✅ Cubierto (EXCELENTE)

| Elemento | Detalle cubierto | Fuente |
|----------|-----------------|--------|
| Marco Tipo A en Chile | NEV mandate compatible con WTO si neutral en origen; NZ Clean Car Standard como modelo | legal_gaps §3.1 |
| Marco Tipo B en Chile | Norma emisión 0 vía Ley 19.300 Art. 32 (sin Congreso); Ley de Tránsito como alternativa; Art. 19 N°21 CPR no bloquea con 9 años lead time | legal_gaps §3.2 |
| Exención IVA (análogo Noruega) | Requiere enmendar Art. 12 DL 825; factible con base ambiental (Art. 19 N°8 CPR); STC roles 280, 1234, 2488, 4317 | legal_gaps §2.1 |
| Crédito tributario (análogo §30D EEUU) | Nuevo art. 55 quáter DL 824; iniciativa exclusiva del Ejecutivo (Art. 65 CPR) | legal_gaps §2.2 |
| Subsidio directo (análogo France prime) | Vía Ley de Presupuestos + CORFO (más rápida, no requiere ley tributaria) | legal_gaps §2.3 |
| Mandato flota pública | Enmienda DS 1363/2014 sin Congreso; Ley 19.886 criterios ambientales en licitaciones | legal_gaps §3.3 |
| Tabla de viabilidad legal integrada (7 políticas) | Tipo A/B/C × vía legal × WTO × Constitución × factibilidad | legal_gaps §3.4 |
| Citas legales redactadas | Párrafos listos para citar en Cap 7 (IVA, WTO, Art 19 N°21) | legal_gaps §3.5 |
| Colombia como comparador LatAm directo | Mismo IVA (19%), mismo perfil importador, Ley 1715→1964→2099; penetración 7.5% vs Chile 1.87% | Factiva-05-04b (síntesis completa) |
| Argumento de no-regresividad | Subsidios regresivos si no focalizados (Sheldon 2022, MIT SPR 2021, Santelices La Tercera abr 2025) → diseño con tope de precio e ingreso | lit_supplement + Factiva-22 |
| Argumento de exit strategy | NZ (abrupto → colapso) vs. Noruega (gradual → 94% al reducir subsidio) | research_addenda |
| Chile como importador puro | WTO/TLC limita Tipo A de producción; no limita Tipo B/C | research_spec §Tipo A |
| Argumento scrappage particular | Ankney & Leard 2025 + UNEP 2020 + IEA 2020; Chile solo tiene RTC (taxis) | lit_review + Factiva-05-04b |
| RTC Chile vs FOPAT Colombia | RTC: $9.7M CLP + $1.8M bono (5 regiones extremas, solo taxis colectivos). FOPAT: $34.5M–$42M + crédito $92M (taxis, nacional) — brecha cuantificada | Factiva-05-04b |
| Ley de Copropiedad como barrera | 60–70% de carga es residencial; edificios = obstáculo; modificar ley de copropiedad = política de bajo costo | Factiva-22 §A6 + Factiva-24 §B2 |
| Tarifa eléctrica flexible | Tarifas en horarios de baja demanda aprovechan vertimientos; propuesta CMS (La Tercera mar 2026) | Factiva-22 §A6 |
| Efecto umbral (Figenbaum 2022) | Noruega: ~20–25% market share → autosustentable sin subsidio → urgencia de cruzar umbral en Chile | lit_review |

### ❌ Falta (CRÍTICO para el cuadro de adaptatividad)

| Gap | Por qué es necesario | Fuente potencial |
|-----|---------------------|------------------|
| Estimación costo fiscal de exención IVA 19% en Chile (en MM USD o % PIB) | El cuadro de adaptatividad requiere "factores económicos" para cada política; sin el costo fiscal de la exención IVA no se puede completar la celda | Cálculo propio: ventas proyectadas × precio promedio × 19%. Inputs disponibles (ventas 2025 ~11.000 unidades, precio ~USD 30.000 promedio). Costo bruto ~USD 63M/año a escala 2025; estimable. |
| Estimación costo fiscal de crédito tributario tipo §30D en Chile (escenario al 5%, al 10% de mercado) | Mismo argumento que arriba para el crédito tributario | Calculable con datos existentes |
| Tasa de los autos usados japoneses como % del parque total (no solo flujo) | Para cuantificar el stock de vehículos >15 años contaminantes que un scrappage atacaría | INE Permisos de Circulación con año de fabricación |
| Marco legal para scrappage de vehículos PARTICULARES en Chile | Actualmente solo existe el RTC (taxis). Para proponer scrappage particular, se necesita la base legal (¿Ley de Tránsito? ¿nueva ley?) | BCN — no identificado en ningún archivo |
| Postura fiscal del Gobierno Kast sobre exención IVA | El gobierno Boric evaluó reforma fiscal verde (Marcel, mar 2025). El gobierno Kast (desde mar 2026) ¿tiene postura pública? | Prensa 2026 post-inauguración — hay artículo ANAC abr 2026 pero sin postura Kast sobre IVA específicamente |

### ⚠️ Parcialmente cubierto en Cap 7

- El **cuadro comparativo de adaptatividad** (el entregable central) tiene toda la materia prima disponible (dimensión legal cubierta, dimensión económica parcialmente cubierta), pero **aún no ha sido redactado como tabla final**. Está implícito en research_spec §Entregable Central y en legal_gaps §3.4, pero no existe como tabla completa con todos los factores económicos llenados.
- **Tarifa de demanda como barrera B2:** Identificada en Factiva-22 (Enerlink CEO, BioBio abr 2026) como "triple kWh cost para estaciones con baja utilización", pero **no hay datos cuantitativos de cuánto cobra la CNE/distribuidoras por este concepto ni hay propuesta de política específica documentada**. El gap existe pero es un detalle técnico regulatorio, no un vacío estructural del argumento.

---

## Conclusión (~500 palabras)

### ✅ Cubierto

- La conclusión puede construirse directamente de los materiales del Cap 7 + las barreras del Cap 3.
- Colombia como modelo de transferencia más directo: IVA 5% permanente + arancel 0% + scrappage tipo FOPAT sectorial → 7,5% penetración.
- Argumento de gradualidad (Noruega) vs. colapso abrupto (NZ) = principio de diseño para Chile.
- Figenbaum 2022: umbral autosustentable; urgencia de política ahora.

### ❌ Falta

- Ningún gap crítico para la conclusión que no esté cubierto por lo anterior.

---

## Huecos Críticos para NotebookLM

Los siguientes son los únicos datos que: (1) son necesarios para que el argumento no cojee, (2) no están cubiertos por ningún archivo existente, y (3) son recuperables de documentos técnicos, informes de gobierno o papers.

---

### HC-1 — Distribución de edad del parque vehicular chileno por cohorte (año de fabricación)

**Por qué cojea sin esto:** El argumento del Cap 3 y Cap 7 sobre "parque viejo" se apoya en una edad promedio (9,4 años) que no dice cuántos vehículos tienen >15 años. Sin la distribución por cohorte, no se puede cuantificar el target del scrappage propuesto (¿cuántos autos habría que retirar?).

**Dónde encontrarlo:** INE — Informe Anual del Parque de Vehículos en Circulación (publicado anualmente). URL verificada: https://www.ine.gob.cl (Transporte > Parque de Vehículos). El informe incluye tabla de distribución por año de fabricación o antigüedad del vehículo.

**Dato esperado:** Tabla de flota total por tramos de antigüedad (0–5 años, 6–10 años, 11–15 años, >15 años), con absolutos y porcentajes.

---

### HC-2 — Tasa de retiro anual del parque ICE (bajas del registro)

**Por qué cojea sin esto:** El argumento de renovación lenta del parque (Barrera 1) necesita mostrar no solo que se venden pocos EVs sino que el parque ICE viejo no sale del registro. El dato de 3 transferencias usadas por 1 nuevo (3:1 ratio) es flujo, no baja de stock.

**Dónde encontrarlo:** INE — misma publicación que HC-1 (Parque de Vehículos), tabla de altas vs. bajas anuales. También: ANAC Informe Parque Automotriz. URL: https://www.anac.cl/informe-del-parque-automotriz/

**Dato esperado:** Número de vehículos dados de baja del Registro Nacional de Vehículos Motorizados por año 2018–2024.

---

### HC-3 — Distribución del ingreso por quintil con datos de transporte / capacidad de pago (CASEN 2022)

**Por qué cojea sin esto:** El argumento de la Barrera 3 (crédito inaccesible para quintiles 1–3) se apoya en que el precio mínimo de un EV ($11,99M CLP) representa X veces el ingreso anual del quintil 2. Sin la cifra de ingreso por quintil de CASEN, el ratio es estimado ("4–5 años de ingreso mediano") pero no precisamente citable.

**Dónde encontrarlo:** Ministerio de Desarrollo Social — CASEN 2022 (más reciente con microdatos). Tabla de ingreso autónomo por quintil per cápita. URL: https://www.desarrollosocial.gob.cl/encuesta/casen

**Dato esperado:** Ingreso autónomo per cápita mensual por quintil (o ingreso total del hogar por quintil). Con esto, el ratio precio EV / ingreso anual puede calcularse para cada quintil.

---

### HC-4 — Tasa y condiciones exactas del crédito BancoEstado para EV particulares (si existe)

**Por qué cojea sin esto:** El Cap 4 describe los incentivos de demanda existentes en Chile. El crédito BancoEstado ha sido confirmado como producto vigente para taxis/colectivos (con tasa "preferencial"), pero nunca se ha confirmado si existe una versión para personas naturales particulares, ni a qué tasa. Si no existe para particulares, eso es **el dato central de la Barrera 3**: el único crédito verde está restringido al transporte remunerado.

**Dónde encontrarlo:** BancoEstado — sitio web, sección "Créditos de consumo" o "Vehículos eléctricos". También: Memoria Anual BancoEstado 2024 (sección productos financieros verdes / Impacto Verde). Si no existe producto para particulares, la ausencia confirmada es el dato.

**Dato esperado:** Tasa CAE, plazo, monto máximo, y segmento elegible del crédito EV BancoEstado para personas naturales. O confirmación de que no existe para particulares.

---

### HC-5 — Costo fiscal estimado de una exención IVA del 19% en compras de EV en Chile (escenario al 2025 y al 2030)

**Por qué cojea sin esto:** El cuadro de adaptatividad del Cap 7 requiere en la columna "factores económicos" el costo fiscal de cada política. Sin este dato, el análisis de viabilidad fiscal de la política más importante (exención IVA) es cualitativo, no cuantitativo.

**Cómo calcularlo (si no hay fuente directa):** Ventas proyectadas 2025 (~11.000 BEV+PHEV) × precio promedio (~$30M CLP) × 19% IVA × (parte que sería exenta) = renuncia fiscal anual. Este cálculo puede hacerse con datos ya disponibles y citarse como estimación propia basada en datos ANAC + Statista.

**Dónde encontrarlo si existe:** DIPRES — Nota Fiscal o Informe Financiero de proyectos de ley que hayan estudiado la exención IVA para EVs (si alguna propuesta llegó al Congreso). BCN Historial Legislativo.

---

### HC-6 — Texto del Reglamento / DS de la Ley de Eficiencia Energética (Ley 21.305) para vehículos

**Por qué cojea sin esto:** La Ley 21.305 es la política más importante del Cap 4/5 (Tipo B, explica el boom 2024), pero solo se cita de manera indirecta vía prensa. Para el Cap 7 (¿puede replicarse?), necesitamos confirmar si el mecanismo es vinculante (multa real) o solo indicativo.

**Dónde encontrarlo:** BCN — Ley 21.305 texto y reglamento. URL: https://www.bcn.cl/leychile/navegar?idNorma=1157988. También el Reglamento de Eficiencia Energética de Vehículos Livianos (DS del Ministerio de Energía). URL: https://energia.gob.cl/eficiencia/vehiculos

**Dato esperado:** Si el estándar es vinculante (multa por incumplimiento), su tipo de instrumento como Tipo B queda confirmado. Si es solo un target de reporte, su clasificación como política efectiva queda en entredicho.

---

### HC-7 — Cifras de market share EV Colombia 2020–2023 (serie temporal completa)

**Por qué cojea sin esto:** Los datos de Colombia 2025 son excelentes (7,5% penetración, 19.724 BEV, crecimiento +115%). Pero la comparación con Chile es más poderosa si se muestra la trayectoria: Colombia también estaba al 1–2% en 2020 y subió a 7,5% en 5 años. Sin la serie 2020–2023 de Colombia, el argumento de transferibilidad ("Colombia logró X a partir de una base similar a la Chile actual") no está completo.

**Dónde encontrarlo:** Fenalco/ANDI/RUNT Colombia informes anuales de ventas vehiculares. También IEA Global EV Data Explorer (Colombia). URL: https://www.iea.org/data-and-statistics/data-tools/global-ev-data-explorer

**Dato esperado:** Market share BEV+PHEV en Colombia por año 2019–2024.

---

*Fin del inventario. Próxima acción: cargar este archivo a NotebookLM junto con las fuentes primarias pendientes de HC-1 a HC-7 para completar el material antes de redacción.*
