# Desafio BInding Formilarios 1

[Enlace Directo](https://binding-forms1.vercel.app/)

![Vue.js](https://img.shields.io/badge/vuejs-%2335495e.svg?style=for-the-badge&logo=vuedotjs&logoColor=%234FC08D)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

> Una aplicación interactiva de formulario de tarjeta de crédito construida con Vue.js

## 🌟 Características

- 🔄 Actualización en tiempo real de la visualización de la tarjeta
- 📝 Validación de entrada de datos
- 🎨 Diseño responsivo y atractivo
- 🔢 Detección automática del tipo de tarjeta

## 📋 Prerrequisitos

Antes de comenzar, asegúrate de tener instalado:

- [Node.js](https://nodejs.org/) (v14.0 o superior)
- [npm](https://www.npmjs.com/) (v6.0 o superior)

## 🚀 Instalación

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/vue-credit-card-form.git
   ```

2. Navega al directorio del proyecto:
   ```bash
   cd vue-credit-card-form
   ```

3. Instala las dependencias:
   ```bash
   npm install
   ```

## 🖥️ Uso

Para iniciar el servidor de desarrollo:

```bash
npm run serve
```

Visita `http://localhost:8080` en tu navegador para ver la aplicación en acción.

## 🛠️ Desarrollo

### Estructura del Proyecto

```
vue-credit-card-form/
│
├── src/
│   ├── components/
│   │   └── CreditCardForm.vue
│   ├── App.vue
│   └── main.js
│
├── public/
│   └── index.html
│
└── README.md
```

### Componente Principal

El componente principal `CreditCardForm.vue` contiene toda la lógica para el formulario y la visualización de la tarjeta.

```vue
<!-- Inserta aquí el código de CreditCardForm.vue -->
```

## 🎨 Personalización

Para personalizar los estilos, modifica el CSS en `CreditCardForm.vue`. Considera usar variables CSS para una fácil personalización:

```css
:root {
  --primary-color: #4CAF50;
  --secondary-color: #FFC107;
  --text-color: #333;
  /* Añade más variables según sea necesario */
}
```

## ✨ Animaciones Sugeridas

Para hacer la interfaz más atractiva, considera agregar estas animaciones:

1. **Flip de Tarjeta**: Añade una animación de volteo cuando el usuario enfoca el campo CVV.

   ```css
   .card-container {
     transition: transform 0.8s;
     transform-style: preserve-3d;
   }
   
   .card-container.flipped {
     transform: rotateY(180deg);
   }
   ```

2. **Pulsación de Campos**: Añade una suave animación de pulsación cuando los campos están activos.

   ```css
   input:focus {
     animation: pulse 1s infinite;
   }
   
   @keyframes pulse {
     0% { box-shadow: 0 0 0 0 rgba(76, 175, 80, 0.4); }
     70% { box-shadow: 0 0 0 10px rgba(76, 175, 80, 0); }
     100% { box-shadow: 0 0 0 0 rgba(76, 175, 80, 0); }
   }
   ```

3. **Transición Suave de Tipo de Tarjeta**: Implementa una transición suave cuando cambia el logo de la tarjeta.

   ```css
   .card-logo {
     transition: opacity 0.3s ease-in-out;
   }
   ```

## 🤝 Contribuir

Las contribuciones son bienvenidas! Por favor, lee la guía de contribución antes de enviar un pull request.

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

## 👏 Agradecimientos

- Iconos por [Font Awesome](https://fontawesome.com/)
- Inspirado en diversos diseños de [Dribbble](https://dribbble.com/)

---

<p align="center">
  Hecho con ❤️ por [Tu Nombre]
</p>

<p align="center">
  <a href="https://github.com/tu-usuario">
    <img src="https://img.shields.io/github/followers/tu-usuario?label=Follow&style=social" alt="GitHub">
  </a>
  <a href="https://twitter.com/tu-usuario">
    <img src="https://img.shields.io/twitter/follow/tu-usuario?style=social" alt="Twitter">
  </a>
</p>