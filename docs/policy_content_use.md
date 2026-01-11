# Policy: Content Use (FASE 1)

## Objetivo
Definir reglas legales y operativas para adquirir, almacenar y clasificar recursos (PDF/HTML) relacionados con Saber 11 (ICFES), garantizando trazabilidad y cumplimiento.

## Categorías de uso (allowed_use)

### 1) licensed_fulltext
Contenido con licencia explícita que permite reproducción/transformación y uso comercial.
- Se puede: descargar, extraer texto, almacenar, mostrar, entrenar.
- Requisito: licencia o permiso escrito verificable.

### 2) internal_only
Contenido público con restricciones (ej. “todos los derechos reservados”, “uso académico”, “no transformación”).
- Se puede: descargar y analizar internamente.
- NO se puede: publicar/redistribuir texto íntegro, exponer en producto comercial como banco de preguntas.
- Uso típico: benchmarking, calibración, validación, análisis de estructura.

### 3) index_only
Contenido altamente restringido o riesgoso.
- Se puede: guardar referencias y trazabilidad (URL, hash, páginas, número de pregunta, metadatos).
- NO se puede: almacenar texto íntegro procesado ni redistribuir.

### 4) do_not_use
Contenido detrás de login/paywall/app o con TOS que prohíben extracción.
- NO se descarga ni se automatiza sin permiso explícito.
- Solo se documenta su existencia y se registra link a TOS.

## Regla por defecto para ICFES
Todo contenido oficial ICFES se clasifica por defecto como internal_only o index_only hasta tener autorización expresa para uso comercial/full-text.

## Trazabilidad obligatoria
Cada descarga debe registrar:
- URL, fecha, status HTTP
- hash SHA256
- allowed_use
- notas de licencia y evidencia (captura o texto relevante)