# Ejercicio: Prototipado – División de gastos 💸

## Situación inicial

Un grupo de amigos necesita una aplicación para **registrar los gastos compartidos durante un viaje y saber cuánto dinero debe cada integrante**.

Para explorar posibles soluciones antes de comenzar el desarrollo, se utilizará **Google Stitch** para crear y evaluar prototipos de la aplicación.

## Parte A: Crear una primera propuesta 🔎

1. Ingresa a [Google Stitch](https://stitch.withgoogle.com/) e inicia sesión con tu cuenta de Google.

2. Crea un nuevo proyecto y selecciona **App nativa (Native App)** como tipo de interfaz.

3. Genera un prompt que describa la aplicación a partir de la situación inicial. La propuesta deberá contemplar, como mínimo:

   - Visualizar los gastos registrados.
   - Registrar un nuevo gasto, indicando descripción, monto y quién realizó el pago.
   - Visualizar un resumen de cuánto dinero debe cada integrante.

4. Genera una propuesta de interfaz utilizando Stitch.

**Tip:** Selecciona todas las pantallas generadas. En la esquina superior derecha encontrarás el botón **Play ▶️**. Utilízalo para visualizar una vista previa del prototipo en un dispositivo y recorrer las distintas pantallas.

## Parte B: Comparar propuestas ⚖️

5. Júntate con un compañero y comparen las propuestas generadas. Ambos partieron del mismo problema y de las mismas funcionalidades, pero pueden haber tomado decisiones diferentes.

Comparen las propuestas considerando:

- ¿se entiende fácilmente quién pagó, cuánto gastó y quién debe dinero?
- ¿qué tan sencillo es registrar un nuevo gasto?
- ¿es fácil conocer rápidamente el estado de las cuentas del grupo?

6. Identifica al menos **una diferencia** entre ambas propuestas y una decisión de la propuesta de tu compañero que incorporarías o considerarías para mejorar la tuya.

## Parte C: Nuevas necesidades del cliente 🔄

Luego de visualizar el prototipo, el cliente realiza algunas aclaraciones:

- No todos los gastos se dividen entre todos los integrantes. Se debe poder seleccionar **quiénes participaron**.
- La división no siempre es en partes iguales. Se debe poder indicar **cuánto corresponde pagar a cada persona**.
- Se necesita visualizar **quién le debe a quién y cuánto**, y no únicamente cuánto gastó cada integrante.

Además, el cliente proporciona el siguiente `design.md` con los lineamientos visuales de la aplicación:

```md
# Design Guidelines

La interfaz debe ser minimalista, moderna y amigable.

## Colores

- Principal: #2563EB
- Secundario: #60A5FA
- Fondo: #F8FAFC
- Texto: #1E293B
- Saldo a favor: #16A34A
- Saldo pendiente: #DC2626

## Tipografía

- Fuente: Inter
- Títulos: Semibold
- Texto general: Regular
```

7. Agrega los lineamientos de diseño a Stitch. En el chat, selecciona el **botón con varios colores**, luego **Crear nuevo** y selecciona `design.md`, allí puedes colocar el contenido proporcionado anteriormente.

8. Utiliza las funcionalidades de edición de Stitch para **iterar sobre tu prototipo**, incorporando las nuevas necesidades del cliente y utilizando el `design.md` como referencia visual.

> No generes un nuevo prototipo desde cero. El objetivo es iterar sobre la propuesta a partir del feedback recibido.

## Parte D: Pruebas sobre el prototipo 🧪

9. Prueba el prototipo utilizando el siguiente escenario:

> Ana paga una cena de **$3.000** para Ana, Bruno y Carla. A cada uno le corresponden **$1.000**.

Verifica que sea posible **registrar el gasto y visualizar correctamente quién le debe a quién**. Si encuentras algún problema, ajusta el prototipo.
