# 🇸🇻 Landing Page Promocional - Almacenes Simán El Salvador

Landing page moderna, responsiva y de alto impacto visual diseñada para promocionar ofertas especiales, eventos exclusivos y captar suscriptores para **Almacenes Simán en El Salvador**.

Desarrollada **100% con HTML5 semántico y CSS3 puro** (sin JavaScript).

---

## 🚀 Características Principales

- **Diseño Responsive:** Totalmente adaptado para teléfonos inteligentes, tablets y computadoras de escritorio.
- **Identidad de Marca:** Paleta de colores oficial de Simán (Rojo `#D11927`, Azul Marino `#0F172A`, Dorado Credisiman `#D4AF37`) y tipografías *Montserrat* y *Poppins*.
- **3 Páginas Enlazadas:**
  - `index.html`: Portada de ofertas, categorías destacadas, productos en descuento, video promocional, beneficios Credisiman y formulario de suscripción.
  - `eventos.html`: Cartelera de experiencias en tiendas (Pasarela en La Gran Vía, Tech Fest en Galerías y Masterclass en Multiplaza) con formulario de reserva VIP.
  - `sucursales.html`: Directorio de sucursales en El Salvador con horarios especiales de temporada y amenidades en tienda.
- **Interactividad 100% CSS Puro:**
  - Menú hamburguesa responsivo resuelto mediante la técnica *Checkbox Hack*.
  - Modales de cupones y confirmación de suscripción resueltos mediante la pseudo-clase `:target`.
  - Formularios con validación nativa de HTML5.
- **Recursos Multimedia:** 12 ilustraciones vectoriales SVG optimizadas y reproductor de video HTML5 integrado.

---

## 📁 Estructura del Proyecto

```
landing-siman/
├── index.html              # Página principal (Promociones & Suscripción)
├── eventos.html            # Eventos exclusivos y pasarelas
├── sucursales.html         # Sucursales en El Salvador y horarios
├── styles.css              # Hoja de estilos (Variables, Flexbox, Grid, Media Queries)
├── README.md               # Documentación del proyecto
├── .gitignore              # Archivos ignorados por git
└── img/                    # Recursos gráficos vectoriales optimizados
    ├── logo-siman.svg
    ├── hero-promo.svg
    ├── credisiman-badge.svg
    ├── promo-moda.svg
    ├── promo-tech.svg
    ├── promo-hogar.svg
    ├── promo-belleza.svg
    ├── evento-pasarela.svg
    ├── evento-tech.svg
    ├── evento-belleza.svg
    ├── sucursal-galerias.svg
    ├── sucursal-granvia.svg
    ├── sucursal-multiplaza.svg
    └── sucursal-metrocentro.svg
```

---

## 💻 Cómo Ejecutar Localmente

### Opción 1: Servidor HTTP local con Python
```bash
# Clona el repositorio
git clone https://github.com/estbust/landing-siman.git
cd landing-siman

# Inicia un servidor local
python3 -m http.server 8080
```
Luego abre tu navegador en: [http://localhost:8080](http://localhost:8080)

### Opción 2: Abrir directamente en el navegador
Puedes abrir directamente el archivo `index.html` con cualquier navegador web (Chrome, Firefox, Safari, Edge).

---

## 🎨 Paleta de Colores

| Color | Hex | Uso |
|---|---|---|
| **Rojo Simán** | `#D11927` | Botones de acción, badges de ofertas, acentos principales |
| **Rojo Oscuro** | `#A81320` | Estados hover y énfasis secundario |
| **Azul Marino** | `#0F172A` | Encabezados, fondos oscuros y pie de página |
| **Dorado Credisiman**| `#D4AF37` | Insignias VIP, beneficios de tarjeta |
| **Fondo Neutro** | `#F8FAFC` | Fondo general suave |

---

## 📄 Licencia

Este proyecto fue desarrollado con fines educativos y de demostración para Almacenes Simán en El Salvador.
