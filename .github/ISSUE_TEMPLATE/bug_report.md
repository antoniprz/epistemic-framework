---
name: Reporte de Error Epistémico (Bug Report)
about: Reportá un puntero colgado, un error polimórfico o una inconsistencia de capas.
title: "[BUG]: "
labels: bug, linter-audit

---

## 🔍 Diagnóstico del Error

**¿Qué tipo de error detectaste?**
*(Marcá uno con una [x])*
- [ ] **Dangling Pointer (v-err):** Un término que no tiene anclaje en C1/C2 (puntero colgado).
- [ ] **Polymorphic Error (poly-err):** Un término con múltiples significados de capas distintas no declarados.
- [ ] **Layer Mismatch (mismatch-err):** Se está tratando una convención C5 como una realidad física C1.
- [ ] **Circularidad:** La definición de un término solo remite a otros términos de la misma capa C5.

**¿En qué capa (C0-C5) se encuentra el error?**
> *Ejemplo: C5 (Instituciones/Leyes) o C2 (Percepción).*

**¿Cuál es el término o sección afectada?**
> *Copiá el fragmento del README o del Core aquí.*

## 🛠️ Propuesta de Reparación
**¿Cómo se debería "anclar" este término para que pase el Pipeline de Validación?**
*(Explicá el anclaje necesario hacia C1/C2 si aplica)*

**Evidencia:**
> Si el error es una falsa afirmación sobre la realidad física, mencioná el dispositivo o fenómeno de C1 que lo contradice (Axioma del Dispositivo).