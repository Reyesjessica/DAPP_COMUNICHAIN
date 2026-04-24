# COMUNICHAIN
---

##  Descripción

Plataforma Web 3.0 diseñada para mejorar la *transparencia, **participación ciudadana* y *eficiencia* en la gestión de proyectos comunitarios financiados por gobiernos.

Permite que las comunidades propongan iniciativas y que las entidades gubernamentales las financien directamente mediante *wallets digitales* y *smart contracts*.

Los ciudadanos pueden monitorear en tiempo real el uso de los fondos y el progreso de cada proyecto, fortaleciendo la rendición de cuentas.

---

##  Características

*  *Propuestas comunitarias*
  Creación y publicación de solicitudes de proyectos por parte de la comunidad.

*  *Financiamiento transparente*
  Depósito directo de fondos a wallets asociadas a proyectos.

* *Seguimiento en tiempo real*
  Visualización del uso de recursos y avances.

* *Smart Contracts (Soroban)*
  Automatización y seguridad en la gestión de fondos.

*  *Participación ciudadana*
  Monitoreo abierto y seguimiento de iniciativas.

---

##  Tecnologías

### Frontend

* Vue.js

### Backend & Blockchain

* Rust
* Soroban (Smart Contracts sobre Stellar)
* Web3
 <img width="544" height="201" alt="image" src="https://github.com/user-attachments/assets/0aa0cbf2-3a8b-4157-8235-5d5632b2ec0b" />


---

##  Arquitectura

Arquitectura descentralizada basada en:

* Frontend en Vue.js
* Smart contracts en Rust
* Despliegue en Soroban
* Integración con wallets digitales

---

##  Flujo de la aplicación

graph TD
A[Comunidad crea proyecto] --> B[Publicación en plataforma]
B --> C[Gobierno evalúa]
C --> D[Financiamiento]
D --> E[Wallet del proyecto]
E --> F[Registro en blockchain]
F --> G[Monitoreo ciudadano]


---

##  Objetivo

Reducir la corrupción, aumentar la transparencia y empoderar a las comunidades mediante tecnología blockchain.

---

##  Instalación

bash id="inst123"
# Clonar repositorio
https://github.com/Reyesjessica/DAPP_COMUNICHAIN

cd tu-repositorio

# Instalar dependencias
npm install


---

## Ejecución

bash id="run123"
## Frontend
npm run dev

## Smart Contracts (Rust + Soroban)
cargo build

## Deploy contrato
soroban contract deploy

<img width="657" height="224" alt="image" src="https://github.com/user-attachments/assets/250a588b-406f-482a-bc5e-3fadf3d5a45c" />

<img width="756" height="374" alt="image" src="https://github.com/user-attachments/assets/0566e8b3-c44e-4e9f-9b71-8eb60f3b8481" />




---

##  Seguridad

* Smart contracts en Rust (seguros y eficientes)
* Transacciones inmutables en blockchain
* Transparencia total del flujo de fondos
  <img width="564" height="189" alt="image" src="https://github.com/user-attachments/assets/28cb8e35-5076-4f28-acbc-1056cccf53c2" />


---

##  Estructura del proyecto

bash id="struct123"
/frontend
/backend
  /contracts
/docs
README.md
```

---

## Contribuciones

1. Fork del proyecto
2. Crear rama (feature/nueva-funcionalidad)
3. Commit (git commit -m "feat: nueva funcionalidad")
4. Push
5. Pull Request
