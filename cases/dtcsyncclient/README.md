# Portfolio — DTC Sync Client — desktop de autorização do PDV

> Public case study only. **No source code** is published here (client/production systems remain private).  
> Estudo de caso público. **Sem código-fonte** (sistemas de cliente/produção permanecem privados).  
> Caso de estudio público. **Sin código fuente** (sistemas de cliente/producción permanecen privados).

---

## 🇧🇷 Português

### DTC Sync Client — desktop na bandeja

**Role / Papel / Rol:** Desenvolvimento completo (UI desktop + integração API/VPN)  
**Stack:** `Python, CustomTkinter, pystray, WireGuard, REST, PyInstaller`

#### Problem / Problema
O caixa (PDV) precisa de autorização humana em tempo real; o técnico/gerente também precisa puxar módulos liberados (Dashboard, PontoBR, Portal) sem instalar tudo à mão.

#### Solution / Solução / Solución
Cliente Windows na bandeja do sistema: login de sessão, autorização/recusa do PDV com aviso sonoro, acesso VPN, importação de dados do PDV e sync dos executáveis liberados pela API do ecossistema DTC Sync.

#### Highlights
- Autorização do PDV em tempo real (liberar / recusar)
- Ícone na bandeja + tema alinhado ao Portal
- VPN WireGuard e sync de módulos contratados
- Autoatualização via GitHub Releases


---

## 🇬🇧 English

### DTC Sync Client — tray desktop for POS authorization

**Role / Papel / Rol:** Full development (desktop UI + API/VPN integration)  
**Stack:** `Python, CustomTkinter, pystray, WireGuard, REST, PyInstaller`

#### Problem / Problema
The POS needs live human authorization; staff also need to pull licensed modules without manual installs.

#### Solution / Solução / Solución
A Windows tray client handles session login, approve/reject POS prompts with sound alerts, VPN access, PDV import and download of licensed Dashboard/PontoBR/Portal packages from the DTC Sync API.

#### Highlights
- Real-time POS authorize / reject
- System tray + Portal-aligned theme
- WireGuard VPN and contracted module sync
- Auto-update via GitHub Releases


---

## 🇪🇸 Español

### DTC Sync Client — escritorio en bandeja para autorización del PDV

**Role / Papel / Rol:** Desarrollo completo (UI desktop + integración API/VPN)  
**Stack:** `Python, CustomTkinter, pystray, WireGuard, REST, PyInstaller`

#### Problem / Problema
El PDV necesita autorización humana en tiempo real; también hay que bajar módulos contratados sin instalación manual.

#### Solution / Solução / Solución
Cliente Windows en la bandeja: login, aprobar/rechazar el PDV con alerta sonora, VPN, importación y sync de ejecutables liberados por la API del ecosistema DTC Sync.

#### Highlights
- Autorización del PDV en tiempo real
- Bandeja del sistema + tema del Portal
- VPN WireGuard y sync de módulos
- Autoactualización vía GitHub Releases


---

## Notes / Observações / Notas

- Author: **Douglas Francisco Bonfim**
- Related private implementation (not public): `dtcsyncclient`
- No credentials, customer data, hostnames, or proprietary payloads are included in this document.
