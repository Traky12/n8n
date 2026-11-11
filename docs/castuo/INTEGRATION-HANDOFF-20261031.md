# CASTÚO-SYSTEM — contrato de evaluación de n8n (sin activar)

**Estado:** `NOT_CONNECTED` · `DESIGNED_ONLY` · `NO_DEPLOY`.

Este repositorio es una copia del **código fuente** de n8n. La presencia de esta documentación no significa que exista una instancia n8n conectada con CASTÚO-SYSTEM, ni que sus workflows estén desplegados o ejecutándose.

## Ámbito de la prueba

1. Inventariar los workflows CASTÚO realmente versionados; si no hay ninguno, registrar `NOT_FOUND` y no crear datos ficticios.
2. Definir un contrato de integración sintético: `event_id` estable, `tenant_id` autenticado, `source_commit` y hash de evidencia, `action` propuesta, `approval_state`, `correlation_id`, `retry_count`.
3. Validar idempotencia: reenvío del mismo `event_id` sin duplicar efectos.
4. Verificar por separado `NOT_CONNECTED`, `CREDENTIALS_PENDING`, `ERROR`, `403`, `503`, timeout y éxito simulado. Un estado de prueba **no** es conectividad real.
5. Incorporar controles de permiso mínimo, presupuesto y límite de reintentos, intervención humana y `deny-by-default` para toda acción destructiva o irreversible.
6. Exigir pruebas reproducibles, SHA literal y revisión independiente antes de permitir un workflow activo.

## Controles prohibitivos

- No instalar paquetes, ejecutar servidores, crear webhooks, introducir credenciales ni ejecutar peticiones remotas.
- No activar agentes de IA, OpenClaw, pasarelas de pago o facturación.
- No modificar archivos upstream del motor n8n o sus workflows de CI para cumplir este contrato.
- No transferir código ni documentos privados del núcleo CASTÚO-SYSTEM a este repositorio público.
- No confundir la revisión del PR con aprobación de producción.

## Resultado

`SOURCE_INVENTORY=PENDING` · `WORKFLOW_RUNTIME=NOT_CONNECTED` · `SECURITY_REVIEW=PENDING` · `G1/G2=BLOCKED` en el sistema principal. Esta declaración no cambia los gates del núcleo.

El repositorio tenía GitHub Issues deshabilitado (respuesta 410 al intento de crear una incidencia). Se usa exclusivamente un PR Draft de documentación para esta coordinación; Issues permanece deshabilitado.
