# Mapa Multimedia Offline – Grupo 3.1  
Proyecto académico – Sistemas Multimedia Audiovisuales 2025-01

## Descripción
Este proyecto consiste en una aplicación móvil que permite explorar puntos emblemáticos de la ciudad de Cali de manera offline.  
La aplicación ofrece información cultural y turística enriquecida con audio, imágenes, relatos y datos sobre miradores, zonas de baile, espacios deportivos y culturales.  

Forma parte del proyecto integrador narrativo transmedia: ¿Cómo suena Cali?

## Objetivo
Visibilizar el potencial turístico, cultural y social de Cali a través de una narrativa transmedia que explore sus sonidos, paisajes, bailes y expresiones cotidianas, accesible desde dispositivos móviles sin necesidad de conexión a internet.

## Stack Tecnológico
- Motor: Unity LTS (IL2CPP, ARM64)  
- Lenguaje: C#  
- Mapas: Mapbox Offline Packs o MapLibre con MBTiles  
- Base de datos local: SQLite embebido  
- Multimedia: Audio (OGG), Imágenes (WebP/PNG), Video (H.264)  
- Servicios opcionales: Firebase (Autenticación, FCM), Supabase (Postgres+REST)  
- Control de versiones: Git + GitHub  
- Licencias: Código MIT, Recursos CC-BY  

## Equipo
- Grupo 3.1 – Mapa Multimedia Offline  
- Integrantes:  
  - [Nombre 1]  
  - [Nombre 2]  

## Flujo de trabajo con Git
1. La rama `main` está protegida (solo permite integración mediante Pull Requests).  
2. Para cada Historia de Usuario se crea una rama `feature/<nombre-hu>`.  
3. Se abre un Pull Request, revisado por al menos un integrante del equipo.  
4. Solo se integra a `main` tras aprobación.  

### Convenciones de commits
- `feat: ...` → nueva funcionalidad  
- `fix: ...` → corrección de errores  
- `docs: ...` → cambios en documentación  
- `chore: ...` → tareas menores  

## Estructura del proyecto (Unity)
