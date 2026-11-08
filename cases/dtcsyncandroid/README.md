# Portfolio — DTC Sync Android — autorização remota do PDV

> Public case study only. **No source code** is published here (client/production systems remain private).  
> Estudo de caso público. **Sem código-fonte** (sistemas de cliente/produção permanecem privados).  
> Caso de estudio público. **Sin código fuente** (sistemas de cliente/producción permanecen privados).

---

## 🇧🇷 Português

### DTC Sync Android — app Kotlin/Compose

**Role / Papel / Rol:** Desenvolvimento completo (Android nativo)  
**Stack:** `Kotlin, Jetpack Compose, Material 3, BiometricPrompt, WireGuard, Foreground Service`

#### Problem / Problema
Gerentes e operadores precisam liberar o PDV fora do balcão — no celular — com o mesmo fluxo seguro do Client desktop, incluindo cadastro do aparelho e aprovação na matriz.

#### Solution / Solução / Solución
App Android com login (usuário do PDV), biometria opcional, conexão VPN DTC, cadastro de aparelho aguardando aprovação, serviço em foreground que observa pedidos de autorização e ações Liberar/Recusar na home.

#### Highlights
- Autorização remota do PDV (Liberar / Recusar)
- Biometria + preferências locais
- VPN WireGuard e descoberta do cliente na rede
- Serviço em foreground com notificações


---

## 🇬🇧 English

### DTC Sync Android — Kotlin/Compose app

**Role / Papel / Rol:** Full development (native Android)  
**Stack:** `Kotlin, Jetpack Compose, Material 3, BiometricPrompt, WireGuard, Foreground Service`

#### Problem / Problema
Managers need to approve the POS away from the counter — on a phone — with the same secure flow as the desktop Client, including device enrollment.

#### Solution / Solução / Solución
An Android app with POS-user login, optional biometrics, DTC VPN, device registration pending matrix approval, a foreground watcher for authorization requests and Approve/Reject actions on the home screen.

#### Highlights
- Remote POS authorize / reject
- Biometrics + local preferences
- WireGuard VPN and on-network client discovery
- Foreground service with notifications


---

## 🇪🇸 Español

### DTC Sync Android — app Kotlin/Compose

**Role / Papel / Rol:** Desarrollo completo (Android nativo)  
**Stack:** `Kotlin, Jetpack Compose, Material 3, BiometricPrompt, WireGuard, Foreground Service`

#### Problem / Problema
Hay que liberar el PDV fuera del mostrador — en el móvil — con el mismo flujo seguro del Client de escritorio, incluido el alta del aparato.

#### Solution / Solução / Solución
App Android con login (usuario del PDV), biometría opcional, VPN DTC, registro del dispositivo pendiente de aprobación, servicio en primer plano que observa pedidos y acciones Liberar/Rechazar.

#### Highlights
- Autorización remota del PDV
- Biometría + preferencias locales
- VPN WireGuard y descubrimiento en red
- Servicio en primer plano con notificaciones


---

## Notes / Observações / Notas

- Author: **Douglas Francisco Bonfim**
- Related private implementation (not public): `dtcsyncandroid`
- No credentials, customer data, hostnames, or proprietary payloads are included in this document.
