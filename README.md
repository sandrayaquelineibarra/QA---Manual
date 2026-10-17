# qa-manual-login

Proyecto de QA Manual: pruebas funcionales de un formulario de inicio de sesión (login).

## 1. Descripción

Proyecto realizado para practicar el proceso completo de testing manual sobre un login: planificación, diseño de casos de prueba, ejecución y reporte de defectos.

## 2. Objetivo

Verificar que el login funcione correctamente con combinaciones de datos válidos e inválidos, y que los mensajes de error y el acceso al sistema se comporten como se espera.

## 3. Alcance

- Incluido: formulario de login de "Acceso Estudiantes" de ITCA (www.itca.com.ar): usuario, contraseña, botón de ingreso, mensajes de error y acceso posterior.
- No incluido: registro de usuarios, recuperación de contraseña, rendimiento y pruebas de seguridad intrusivas (el caso TC-LOGIN-012 queda documentado pero no se ejecuta sobre el sitio real).

## 4. Pruebas realizadas

- Login con usuario y contraseña válidos.
- Login con contraseña incorrecta.
- Login con usuario incorrecto.
- Campos obligatorios vacíos.
- Validación de mensajes de error.
- Validación de acceso al sistema.
- Contraseña enmascarada, mayúsculas/minúsculas, espacios en el usuario, tecla Enter e intento básico de inyección SQL.

## 5. Tipos de pruebas

- Funcionales
- Negativas
- De validación
- De seguridad básica
- De regresión

## 6. Documentación

| Carpeta / archivo | Contenido |
| --- | --- |
| `01-Plan-de-Pruebas/` | Plan de pruebas |
| `02-Casos-de-Prueba/Casos-de-Prueba-Login.xlsx` | 15 casos de prueba, resumen de ejecución y hoja de reporte de bugs |
| `04-Reporte-de-Bugs/` | Plantilla para reportar defectos |
| `03-Evidencias/` | Capturas de pantalla de la ejecución |

## 7. Estructura de un caso de prueba

ID, tipo, prioridad, descripción, precondiciones, pasos, datos de prueba, resultado esperado, resultado obtenido, estado (Pasó / Falló / Bloqueado / Pendiente) y bug asociado.

## 8. Resultado

Los resultados de la ejecución y los defectos encontrados se registran en el archivo Excel (hojas "Resumen" y "Reporte de bugs").

## 9. Herramientas

- GitHub
- Excel
- Navegador web
- Testing manual

## 10. Rol

QA Manual Tester: Sandra Ibarra

