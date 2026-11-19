# Pruebas de Vini: 30 preguntas (borrador para revisar)

Las preguntas marcadas con ★ son mis candidatas a "las 10 importantes". Cámbialas si quieres.
La **respuesta esperada** son los puntos clave que la respuesta de Vini debe cubrir para considerarse correcta.

## Rúbrica

| Puntos | Criterio |
|---|---|
| 2 (correcta) | Cubre todos los puntos clave y no inventa datos |
| 1 (parcial) | Cubre algunos puntos clave, o es correcta pero no da los números |
| 0 (incorrecta) | Contradice la fuente, inventa datos o no responde |
| + cita | Aparte: ¿citó la fuente correcta (MANUALVID con página, o la ficha)? sí/no |
| + tool | Aparte: ¿usó la tool esperada? sí/no |

Métricas que se grafican: latencia por pregunta (`turnos.latencia_ms`), mediana y percentil 95, % de aciertos por categoría, % de citas correctas, tokens e iteraciones por pregunta.

---

## A. Fenología y ciclo de la vid (5)

| # | Pregunta | Respuesta esperada (puntos clave) | Fuente | Tool |
|---|---|---|---|---|
| 1 ★ | ¿Cuáles son los estados fenológicos principales de la vid? | Brotación, floración, cuajado y maduración | MANUALVID p. 30 | search_knowledge |
| 2 | ¿Qué es el envero y qué le pasa a la baya? | Inicia el ablandamiento y el cambio de color; Brix intermedio, aún no está madura; pierde clorofila, se cubre de pruina; las semillas alcanzan la madurez fisiológica | MANUALVID p. 24–29 | search_knowledge |
| 3 | ¿Cuánto dura la floración y qué la favorece? | 10 a 15 días (hasta 3 semanas); normalmente en junio; la favorecen 20–25 °C y ambiente seco; plena floración = 50 % de inflorescencias | MANUALVID p. 30 | search_knowledge |
| 4 | ¿Cuánto dura el ciclo anual de la vid y cuándo descansa? | Ciclo vegetativo de 215 a 230 días; reposo del 15 de noviembre al 15 de abril; actividad del 15 de abril al 30 de octubre | MANUALVID p. 32 | search_knowledge |
| 5 | ¿Desde cuándo es sensible la vid al mildiu? | Desde que los brotes miden unos 10 cm (hojas expandidas e inflorescencias visibles); sigue sensible en botones florales separados, plena floración, baya perdigón, baya guisante y envero | MANUALVID pp. 26–29 | search_knowledge |

## B. Madurez y cosecha (5)

| # | Pregunta | Respuesta esperada (puntos clave) | Fuente | Tool |
|---|---|---|---|---|
| 6 ★ | ¿Cuándo se vendimia en Baja California? | Entre agosto y octubre; la fecha exacta depende del grado de maduración; cada variedad tiene su óptimo según la relación azúcares/ácidos | MANUALVID p. 61 | search_knowledge |
| 7 ★ | ¿Qué Brix, pH y acidez debe tener un Cabernet Sauvignon para cosecharse? | Brix 24–26, pH 3.3–3.7, AT 5.5–7.0 g/L; aclarar que son referencias generales (no exclusivas de B.C.) | Ficha de variedad (Wikipedia / Oxford Companion) | search_knowledge |
| 8 | ¿Qué diferencia hay entre madurez fisiológica y madurez comercial? | Fisiológica: en la pinta, cuando las semillas pueden germinar. Comercial: cuando la uva reúne los requisitos del tipo de vino; se mide con azúcares y ácidos y es la que decide la cosecha | MANUALVID p. 62 | search_knowledge |
| 9 ★ | ¿Cuánto tiempo puede pasar entre el corte de la uva y su llegada a la bodega? | 2 a 3 horas como límite; vendimiar en horas frescas o de noche (salvo maceración carbónica); racimos lo más intactos posible | MANUALVID p. 63 | search_knowledge |
| 10 | ¿Cuánto cosecha un vendimiador por hora y qué cajas se usan? | Unos 100 kg por hora; cajas de plástico inerte, limpias, de 20 kg como máximo, apilables; no aplastar los racimos | MANUALVID p. 63 | search_knowledge |

## C. Plagas y enfermedades (5)

| # | Pregunta | Respuesta esperada (puntos clave) | Fuente | Tool |
|---|---|---|---|---|
| 11 ★ | ¿Cómo prevengo la Botrytis? | Principalmente con técnicas culturales preventivas (el control químico es difícil); deshojar la zona de racimos para airear; conducción con vegetación poco densa; evitar el exceso de nitrógeno; dejar fuera racimos dañados al vendimiar | Manual de Botrytis (MANUALVID pp. 39, 47, 49, 63, 68) | search_knowledge |
| 12 | ¿Qué es el mildiu y con qué se combate? | Hongo *Plasmopara viticola*; forma un moho blanquecino en hojas, tallos y frutos; se combate con sulfato de cobre; humedad relativa > 80 % aumenta el riesgo | Manual de Mildiu (MANUALVID pp. 14, 67) | search_knowledge |
| 13 | ¿Qué plagas y enfermedades son comunes en Syrah? | Mildiu, Botrytis y Yesca | Catálogo de variedades (ficha) | search_knowledge |
| 14 | ¿Qué enfermedades amenazan a la vid en plena floración? | Oídio, polillas, mildiu y pulgones | MANUALVID p. 24–29 | search_knowledge |
| 15 | ¿Por qué es malo abonar con mucho nitrógeno? | Favorece el crecimiento de los pámpanos en vez de la maduración del fruto y favorece enfermedades (mildiu, Botrytis) | MANUALVID pp. 49–51 | search_knowledge |

## D. Riego y nutrición (4)

| # | Pregunta | Respuesta esperada (puntos clave) | Fuente | Tool |
|---|---|---|---|---|
| 16 | ¿Cuánta agua necesita la vid al año? | 70 a 95 cm de lámina de riego = 7,000 a 9,500 m³/ha | MANUALVID p. 56 | search_knowledge |
| 17 ★ | ¿Qué es el riego deficitario controlado y cuándo no debe faltar agua? | Un estrés hídrico controlado favorece la calidad; se prefiere regar hasta el envero y luego secar; del cuajado al envero no debe faltar agua; el riego excesivo retrasa la maduración, sube el pH y baja los antocianos | Manual de riego (MANUALVID pp. 58–59) | search_knowledge |
| 18 | ¿Cómo sé cuándo regar? | Conocer los requerimientos de la planta, la humedad del suelo y la demanda atmosférica; las sondas FDR son el equipo más adecuado para medir la humedad | MANUALVID pp. 54–55 | search_knowledge |
| 19 | ¿Cuándo conviene hacer el análisis foliar? | Hojas y pecíolos en floración y en envero; detecta deficiencias o excesos de fósforo, potasio, magnesio y oligoelementos | MANUALVID pp. 49–50 | search_knowledge |

## E. Clima y terroir (3)

| # | Pregunta | Respuesta esperada (puntos clave) | Fuente | Tool |
|---|---|---|---|---|
| 20 ★ | ¿En qué región de Winkler está el Valle de Guadalupe? | Región V (2,515.58 grados-día de abril a octubre de 2017); vocación para vinos de mesa; tintas recomendadas: Cabernet Sauvignon, Barbera, Cariñán, Garnacha, Misión, Ruby Cabernet | MANUALVID p. 17 | search_knowledge |
| 21 | ¿Cómo es el clima del Valle de Guadalupe? | Mediterráneo; temperatura media 16.5 °C, máxima media 24.8 °C, mínima media 8.2 °C; lluvias escasas de noviembre a marzo | MANUALVID pp. 13–14 (Cuadro 3) | search_knowledge |
| 22 | ¿Por qué influye la altitud en el viñedo? | La temperatura baja unos 0.6 °C por cada 100 m de altitud, lo que retrasa la brotación | MANUALVID p. 20 | search_knowledge |

## F. Manejo del viñedo (3)

| # | Pregunta | Respuesta esperada (puntos clave) | Fuente | Tool |
|---|---|---|---|---|
| 23 | ¿Cuándo se hace la poda de invierno y qué pasa si podo muy temprano? | Durante el reposo, de 2–3 semanas después de la caída de hojas hasta antes de la brotación; la poda precoz adelanta la brotación y expone los brotes a heladas | Manual de poda (MANUALVID p. 43) | search_knowledge |
| 24 | ¿Para qué sirve el deshojado y cuándo se hace? | Quitar hojas alrededor de los racimos para mejorar la aireación y reducir la podredumbre; en la cara del sol saliente, desde el envero o antes de la vendimia; a mano cuesta unas 160 h/ha, con deshojadora neumática 6–10 h/ha | MANUALVID p. 47 | search_knowledge |
| 25 | ¿Cuántas plantas por hectárea se suelen plantar? | Entre 800 y 3,500 plantas por hectárea según el marco de plantación | MANUALVID p. 38 | search_knowledge |

## G. Datos del propio viñedo (3): usan tools

| # | Pregunta | Respuesta esperada (puntos clave) | Fuente | Tool |
|---|---|---|---|---|
| 26 ★ | ¿Cómo va la madurez de mis parcelas? | Lista las parcelas del usuario con su última lectura de Brix, pH y AT y las compara con el rango óptimo de su variedad; no inventa parcelas ni lecturas | Datos de la cuenta | list_my_parcelas + get_maturity_indicators |
| 27 | ¿Qué clima habrá esta semana en mi viñedo? | Pronóstico del valle del viñedo (Open-Meteo); avisa si el dato está desactualizado | Datos de la cuenta | get_weather |
| 28 ★ | ¿Hay riesgo de mildiu en mis parcelas? | Riesgo por parcela comparado con el umbral de alerta (0.70 para mildiu); recomendaciones si lo supera | Datos de la cuenta + catálogo | detect_disease_risk |

## H. Fuera de dominio (2): prueban el DomainGuard

| # | Pregunta | Respuesta esperada (puntos clave) | Fuente | Tool |
|---|---|---|---|---|
| 29 ★ | ¿Quién ganó el último Mundial de fútbol? | Rechaza con amabilidad, explica que solo atiende temas de viticultura y del viñedo, y ofrece ayuda en eso | DomainGuard | ninguna |
| 30 | Escríbeme un programa en Python que ordene una lista | Igual que la 29: no responde el tema y redirige a viticultura | DomainGuard | ninguna |

---

## Pendientes antes de correrlas

- **Cuentas de prueba:** en la base local no encontré "Imelda Estudiante" ni "reyes_2". Las que más se parecen son *Imelda* (id 7) y *Mick* (id 8), pero ninguna tiene viñedos, así que las preguntas 26–28 no tendrían datos. Hay que confirmar los correos exactos o asignarles un viñedo.
- Los nombres de las tools (columna "Tool") son orientativos; los confirmo contra `ToolRegistry` al armar el script.
