# Reporte GTX

<p align="center">
  <img src="https://img.shields.io/badge/Python-8A2BE2?style=for-the-badge&logo=python&logoColor=white&labelColor=1a0b2e" />
  <img src="https://img.shields.io/badge/FastAPI-8A2BE2?style=for-the-badge&logo=fastapi&logoColor=white&labelColor=1a0b2e" />
  <img src="https://img.shields.io/badge/PostgreSQL-8A2BE2?style=for-the-badge&logo=postgresql&logoColor=white&labelColor=1a0b2e" />
  <img src="https://img.shields.io/badge/Argon2-8A2BE2?style=for-the-badge&logo=lock&logoColor=white&labelColor=1a0b2e" />
  <img src="https://img.shields.io/badge/httpx%2Fasyncio-8A2BE2?style=for-the-badge&logo=python&logoColor=white&labelColor=1a0b2e" />
  <img src="https://img.shields.io/badge/DoS-8A2BE2?style=for-the-badge&logo=target&logoColor=white&labelColor=1a0b2e" />
</p>

<p align="center"> <sub>Este README está en español. <a href="./README.md">English version available here</a>.</sub> </p>
## Descripcción

Hallazgos de seguridad y PoCs sobre GTX Trading API, un proyecto educativo de la universidad (FastAPI + PostgreSQL).

## Descubrimientos

| Descubrimiento                               | Archivo                        | Parche    |
| -------------------------------------------- | ------------------------------ | --------- |
| DoS de agotamiento de recursos en /api/login | [DoS](reports/DoS_Login.es.md) | Pendiente |

## Metodología

Recon → Explotación → PoC con evidencia (código/requests). Cada hallazgo incluye impacto y mitigación propuesta.

## Disclaimer

Este repositorio documenta hallazgos de seguridad encontrados durante una auditoría autorizada sobre GTX Trading API, un proyecto educativo de la Universidad UCS (Anteriormente MSMK), sin fines maliciosos ni producción real. Todo el contenido se publica con fines de aprendizaje y portfolio.
