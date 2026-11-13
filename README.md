# GTX Report

<p align="center">
  <img src="https://img.shields.io/badge/Python-8A2BE2?style=for-the-badge&logo=python&logoColor=white&labelColor=1a0b2e" />
  <img src="https://img.shields.io/badge/FastAPI-8A2BE2?style=for-the-badge&logo=fastapi&logoColor=white&labelColor=1a0b2e" />
  <img src="https://img.shields.io/badge/PostgreSQL-8A2BE2?style=for-the-badge&logo=postgresql&logoColor=white&labelColor=1a0b2e" />
  <img src="https://img.shields.io/badge/Argon2-8A2BE2?style=for-the-badge&logo=lock&logoColor=white&labelColor=1a0b2e" />
  <img src="https://img.shields.io/badge/httpx%2Fasyncio-8A2BE2?style=for-the-badge&logo=python&logoColor=white&labelColor=1a0b2e" />
  <img src="https://img.shields.io/badge/DoS-8A2BE2?style=for-the-badge&logo=target&logoColor=white&labelColor=1a0b2e" />
</p>

<p align="center"> <sub>This README is in English. <a href="./README.es.md">Versión en español disponible aquí</a>.</sub> </p>

## Description

Security findings & PoCs on GTX Trading API, an educational university project (FastAPI + PostgreSQL).

## Findings

| Finding                               | File                        | Patch   |
| ------------------------------------- | --------------------------- | ------- |
| Resource-exhaustion DoS on /api/login | [DoS](reports/DoS_Login.md) | Pending |

## Methodology

Recon → Exploitation → PoC with evidence (code/requests). Each finding includes impact and proposed mitigation.

## Disclaimer

This repository documents security findings discovered during an authorized audit of GTX Trading API, an educational project at UCS University (formerly MSMK), with no malicious intent or production use. All content is published for learning and portfolio purposes.