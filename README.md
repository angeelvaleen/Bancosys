# BancoSys · Prototipo de atención bancaria

**BancoSys** es un proyecto de interfaces web para representar el flujo de atención de una sucursal bancaria: recepción de clientes, generación de turnos y visualización de estados de atención.

Es un **prototipo formativo**, no un sistema bancario transaccional ni una plataforma de gestión de cuentas reales.

## Tecnologías presentes en este repositorio

- **HTML:** estructura de las pantallas.
- **CSS:** diseño visual y estilos.
- **JavaScript:** interacciones y simulación de turnos.
- **localStorage:** almacenamiento local usado por algunas pantallas para compartir datos de demostración en el mismo navegador.

Este repositorio **no implementa** el backend PHP, la base MySQL ni la seguridad de transacciones que aparecían en una descripción anterior.

## Pantallas

Los archivos se encuentran en la carpeta `bancosys/`.

| Archivo | Qué puedes explorar |
| --- | --- |
| `index.html` | Pantalla de inicio |
| `recepcion.html` | Recepción y generación de turnos |
| `monitor.html` | Visualización de turnos |
| `panel.html` | Interfaz de panel |
| `general.html` | Vista general |
| `login.html` | Interfaz de acceso |

## Cómo revisar el proyecto

```bash
git clone https://github.com/angeelvaleen/Bancosys.git
cd Bancosys/bancosys
```

Abre `index.html` en tu navegador. También puedes servir la carpeta con una extensión como **Live Server** en VS Code.

Para probar el flujo de turnos, abre las pantallas de recepción y monitor en pestañas del **mismo navegador y origen**; ambas consultan datos guardados con `localStorage`.

## Si estás aprendiendo, revisa esto

1. **Estructura:** compara el HTML de recepción y monitor.
2. **Interfaz:** observa las variables CSS, componentes visuales y estados.
3. **JavaScript:** busca las operaciones con `localStorage` para entender cómo se guarda y consulta una lista de turnos.
4. **Práctica:** intenta extraer la lógica compartida a un archivo JavaScript reutilizable.

## Limitaciones y siguientes pasos

- Los datos almacenados localmente son **solo de demostración** y no se sincronizan entre dispositivos.
- La interfaz de acceso no debe confundirse con un mecanismo seguro de autenticación.
- No maneja dinero, cuentas bancarias reales ni operaciones financieras seguras.
- [ ] Extraer estilos y scripts comunes a archivos reutilizables.
- [ ] Añadir una API y almacenamiento centralizado si se desea sincronización real.
- [ ] Incorporar validación, accesibilidad y pruebas.
- [ ] Documentar el flujo con capturas de pantalla.

---

**Autor:** [Ángel Valencia](https://github.com/angeelvaleen) · Proyecto académico para aprender y experimentar con interfaces y flujos de atención.
