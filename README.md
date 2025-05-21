# nativescript
# Proyecto Final NativeScript 
## ✅ Requisitos cumplidos

1. **Template base usado**  
   El proyecto fue iniciado desde el repositorio `template-drawer-navigation-ng`, que implementa navegación modularizada por features usando el side drawer.

2. **Al menos 2 componentes nuevos**  
   Se crearon los componentes:
   - `PerfilComponent` (features/perfil)
   - `TestimoniosComponent` (features/testimonios)

3. **Un nuevo módulo creado**  
   Se agregó el módulo `contacto`, ubicado en `features/contacto`.

4. **Submódulo de ruteo**  
   El módulo `contacto` tiene su propio archivo de rutas y se encuentra registrado en la navegación.

5. **Integración con el side drawer**  
   Los nuevos módulos fueron añadidos al `app-routing.module.ts`, y aparecen como opciones en el menú lateral.

6. **Nuevo servicio con inyección global**  
   Se creó `UserService` en `src/app/services`, el cual está inyectado a nivel global mediante `providedIn: 'root'`.

7. **Uso de `*ngFor`**  
   El componente `TestimoniosComponent` usa `*ngFor` para iterar sobre un array de objetos con mensajes.

8. **Estilos diferenciados por plataforma (Android/iOS)**  
   - `testimonios.component.android.css` y `testimonios.component.ios.css` aplican colores diferentes según el sistema operativo.

9. **Ícono personalizado en App_Resources**  
   Se añadió el ícono `icon-heart.png` en las carpetas de recursos de Android e iOS (`App_Resources/...`).

10. **Código condicional para Android**  
   En `PerfilComponent`, se usa `isAndroid` de `@nativescript/core` para asignar valores distintos según la plataforma.

---

## 📦 Estructura del proyecto

