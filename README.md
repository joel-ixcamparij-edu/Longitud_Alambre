# Página Web del Proyecto

Accede a la calculadora aquí:  
**[https://joel-ixcamparij-edu.github.io/Longitud_Alambre/](https://joel-ixcamparij-edu.github.io/Longitud_Alambre/)**

---

# Calculadora de Longitud de Alambre

Este proyecto consiste en una herramienta web simple para calcular la longitud aproximada de un alambre a partir de su peso, densidad (material) y diámetro.

La página permite al usuario ingresar los datos y visualizar el resultado junto con el detalle paso por paso del proceso de cálculo.

---

## Datos de Ejemplo

- **Peso:** 1 kg
- **Densidad:** 7850 kg/m³ El alambre es de tipo microalambre (acero de bajo carbono) núcleo fundente, designación E71T-GS.
- **Diámetro:** 0.8 mm


### Resultado

- **Longitud aproximada del alambre:** 253.43 metros

### Detalle del cálculo:

1. **Conversión de diámetro a metros:**
   \[
   0.8\ \text{mm} = 8.000000 × 10^{-4}\ \text{m}
   \]

2. **Cálculo del radio:**
   \[
   \text{radio} = 4.000000 × 10^{-4}\ \text{m}
   \]

3. **Área de sección transversal:**
   \[
   A = π × (4.000000 × 10^{-4})^2 = 5.026548 × 10^{-7}\ \text{m}^2
   \]

4. **Volumen del alambre:**
   \[
   V = \frac{1\ \text{kg}}{7850\ \text{kg/m}^3} = 1.273885 × 10^{-4}\ \text{m}^3
   \]

5. **Longitud del alambre:**
   \[
   L = \frac{V}{A} = \frac{1.273885 × 10^{-4}\ \text{m}^3}{5.026548 × 10^{-7}\ \text{m}^2} = 253.43\ \text{metros}
   \]

---

## Tecnologías usadas

- HTML5
- JavaScript (puro, sin librerías externas)
- CSS básico

Todo el código está contenido en un solo archivo HTML que puede ejecutarse localmente o ser alojado en plataformas como GitHub Pages.

---

## Propósito académico

Este proyecto fue desarrollado como parte del curso de **Física** de la carrera de **Licenciatura en Gestión de Energía y Ambiente (LGEA)** de la **Universidad Galileo**.

---

© 2025 - Joel Ixcamparij
