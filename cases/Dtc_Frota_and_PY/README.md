# Portfolio — DTC Frota Backend — serviços e API

> Public case study only. **No source code** is published here (client/production systems remain private).  
> Estudo de caso público. **Sem código-fonte** (sistemas de cliente/produção permanecem privados).  
> Caso de estudio público. **Sin código fuente** (sistemas de cliente/producción permanecen privados).

---

## 🇧🇷 Português

### DTC Frota Backend — serviços e API

**Role / Papel / Rol:** Backend de sincronização e API REST  
**Stack:** `Delphi/Object Pascal, PostgreSQL, REST, integração com medidores`

#### Problem / Problema
Abastecimentos e medições de tanque precisavam ser processados em background e expostos via API para o frontend web.

#### Solution / Solução / Solución
Serviço Delphi em background com sync, comunicação com equipamentos e API REST consumida pelo frontend Python.

#### Highlights
- Arquitetura backend/frontend desacoplada
- Integração com hardware de posto/frota
- API REST


---

## 🇬🇧 English

### DTC Frota Backend — services and API

**Role / Papel / Rol:** Sync backend and REST API  
**Stack:** `Delphi/Object Pascal, PostgreSQL, REST, integração com medidores`

#### Problem / Problema
Fueling events and tank measurements needed background processing and a REST API for the web frontend.

#### Solution / Solução / Solución
Delphi background service with sync, device communication, and REST API consumed by the Python frontend.

#### Highlights
- Decoupled backend/frontend
- Forecourt/fleet hardware integration
- REST API


---

## 🇪🇸 Español

### DTC Frota Backend — servicios y API

**Role / Papel / Rol:** Backend de sincronización y API REST  
**Stack:** `Delphi/Object Pascal, PostgreSQL, REST, integração com medidores`

#### Problem / Problema
Los abastecimientos y mediciones de tanque debían procesarse en background y exponerse vía API al frontend web.

#### Solution / Solução / Solución
Servicio Delphi en background con sync, comunicación con equipos y API REST consumida por el frontend Python.

#### Highlights
- Backend/frontend desacoplados
- Integración con hardware de estación/flota
- API REST


---

## Notes / Observações / Notas

- Author: **Douglas Francisco Bonfim**
- Related private implementation (not public): `Dtc_Frota_and_PY`
- No credentials, customer data, hostnames, or proprietary payloads are included in this document.
