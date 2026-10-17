# QA---Manual
Pruebas funcionales de Login - itca

 # 1. Descripción

Proyecto de QA manual realizado para practicar el proceso completo de testing sobre un formulario de inicio de sesión: planificación, diseño de casos, ejecución, reporte de defectos y regresión.

 # 2. Objetivo

Verificar que el login funcione correctamente con combinaciones de datos válidos e inválidos, y que el sistema valide los campos y los mensajes de error de forma adecuada.

# 3. Alcance

**Incluye:** autenticación con usuario y contraseña, validación de campos obligatorios, mensajes de error, enmascarado de contraseña, acceso a páginas protegidas y cierre de sesión.

**No incluye:** recuperación de contraseña, registro de usuarios, pruebas de rendimiento ni de seguridad avanzada.

# 4. Tipos de pruebas

- Pruebas funcionales
- Pruebas negativas
- Pruebas de validación
- Pruebas de regresión

# 5. Estructura del repositorio

| Carpeta / archivo | Contenido |

| 01-Plan-de-Pruebas/ | Plan de pruebas: alcance, estrategia y criterios |
| 02-Casos-de-Prueba/casos-de-prueba-login.xlsx | 14 casos de prueba, reporte de bugs y resumen de ejecución |
| 03-Evidencias/| Capturas de pantalla de la ejecución (un archivo por caso o bug) |
| README.md | Este documento |

# 6. Casos de prueba

Los 14 casos cubren, entre otros, estos escenarios:

- Login con usuario y contraseña válidos (CP-01)
- Login con contraseña incorrecta (CP-02)
- Login con usuario incorrecto (CP-03)
- Campos obligatorios vacíos (CP-04 a CP-06)
- Validación de mensajes de error (CP-07)
- Contraseña enmascarada, espacios y mayúsculas/minúsculas (CP-08 a CP-10)
- Envío con Enter, acceso sin sesión y cierre de sesión (CP-11 a CP-13)
- Regresión (CP-14)

# 7. Resultado

[Completar tras ejecutar: cantidad de casos que pasaron, fallaron o quedaron bloqueados, y cantidad de bugs registrados. La hoja "Resumen" del Excel lo calcula automáticamente.]

# 8. Herramientas

- GitHub
- Excel
- Navegador web

# 9. Rol

QA Manual Tester: diseño y ejecución de casos de prueba, reporte de defectos y pruebas de regresión.
