# onsistems-email

Newsletter HTML para el cliente **onsistems** — servicio de páginas web en 24 horas.

## Descripción

Maquetación de una campaña de email marketing en HTML/CSS puro, sin frameworks externos. El email está estructurado en cajas independientes para facilitar el mantenimiento y la escalabilidad.

## Estructura del proyecto

```
onsistems-email/
├── onsistems_email.html   # Archivo principal del email
├── assets/               # Imágenes (alojadas en CDN externo)
└── README.md
```

## Características técnicas

- Layout basado en tablas para compatibilidad universal
- Responsive: adaptado a móvil (≤600px) y tablet (601–768px)
- Compatibilidad con Outlook mediante condicionales MSO y VML
- Tipografía: Heebo (Google Fonts) con fallback a Helvetica/Arial
- Imágenes con rutas absolutas (CDN)
- Accesibilidad: roles ARIA, atributos alt, contraste WCAG 2.1 AA

## Cliente

**onsistems** — Turn ON the future  
Servicio de digitalización de negocios. Web corporativa en menos de 24h desde 299€.

## Estado

En desarrollo — campaña de lanzamiento del servicio web 24h.
