# Generador de requerimiento de cumplimiento de comodato

Página estática (un solo `index.html`) para generar el oficio de requerimiento del DADEP.
Se editan fecha, destinatario, correo, contrato de comodato, matrícula inmobiliaria y consecutivo;
hay vista previa en vivo y descarga en PDF. Todo se genera en el navegador (jsPDF desde cdnjs).

## Uso local
Abrir `index.html` en el navegador (requiere internet para cargar jsPDF).

## Despliegue en Vercel
1. Subir este repositorio a GitHub.
2. En Vercel: *Add New → Project* → importar el repositorio.
3. Framework Preset: **Other**. No hay build ni carpeta de salida: se sirve `index.html` tal cual.

## Archivos
- `index.html`: página completa (estilos, lógica, logo, firma y pie de página embebidos).
