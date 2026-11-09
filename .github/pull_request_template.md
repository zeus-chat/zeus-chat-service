## Cambio
<!-- Qué cambia y por qué (en español). El título del PR es un Conventional Commit en inglés: feat(HU-04): reject empty message bodies -->

## Historia
<!-- HU-xx · ADR-NNN -->

## Checklist (Definition of Done)
- [ ] Desarrollado con TDD (tests primero, el historial de commits lo evidencia)
- [ ] Los criterios de aceptación de la historia están cubiertos por tests (`@DisplayName("HU-xx: …")`)
- [ ] Si cambia un endpoint o evento: el contrato en `zeus-chat-docs` (`07-api`) se actualizó **antes** y está aprobado
- [ ] Si cambia el esquema: *changeset* de Liquibase con `--rollback`
- [ ] Reglas ArchUnit, Spotless y cobertura en verde (CI)
- [ ] Sin secretos, tokens ni contenido de mensajes en logs
- [ ] Documentación afectada actualizada (README del servicio, ADR)
