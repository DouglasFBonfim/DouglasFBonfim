# Portfolio — Integração ERP — sync financeiro

> Public case study only. **No source code** is published here (client/production systems remain private).  
> Estudo de caso público. **Sem código-fonte** (sistemas de cliente/produção permanecem privados).  
> Caso de estudio público. **Sin código fuente** (sistemas de cliente/producción permanecen privados).

---

## 🇧🇷 Português

### Integração ERP — sync financeiro

**Role / Papel / Rol:** Integração Delphi de lançamentos financeiros  
**Stack:** `Delphi, PostgreSQL, jobs/timers, auditoria`

#### Problem / Problema
Lançamentos financeiros do sistema local precisavam espelhar em ERP externo (incluir/alterar/cancelar/excluir) de forma automática e auditável.

#### Solution / Solução / Solución
Serviço Delphi com importações incrementais, tratamento de cancelamentos/exclusões via auditoria, agrupamento de vendas e timers de execução.

#### Highlights
- Sync incremental + auditoria
- Agrupamento de vendas
- Execução agendada em background


---

## 🇬🇧 English

### ERP Integration — financial sync

**Role / Papel / Rol:** Delphi integration for financial postings  
**Stack:** `Delphi, PostgreSQL, jobs/timers, auditoria`

#### Problem / Problema
Local financial postings needed to mirror into an external ERP (insert/update/cancel/delete) automatically and auditably.

#### Solution / Solução / Solución
Delphi service with incremental imports, cancel/delete handling via audit, sales grouping, and scheduled timers.

#### Highlights
- Incremental sync + audit
- Sales grouping
- Scheduled background runs


---

## 🇪🇸 Español

### Integración ERP — sync financiero

**Role / Papel / Rol:** Integración Delphi de asientos financieros  
**Stack:** `Delphi, PostgreSQL, jobs/timers, auditoria`

#### Problem / Problema
Los asientos financieros locales debían reflejarse en un ERP externo (alta/cambio/cancelación/baja) de forma automática y auditable.

#### Solution / Solução / Solución
Servicio Delphi con importaciones incrementales, manejo de cancelaciones/bajas vía auditoría, agrupación de ventas y timers.

#### Highlights
- Sync incremental + auditoría
- Agrupación de ventas
- Ejecución programada en background


---

## Notes / Observações / Notas

- Author: **Douglas Francisco Bonfim**
- Related private implementation (not public): `IntegracaoProtheus`
- No credentials, customer data, hostnames, or proprietary payloads are included in this document.
