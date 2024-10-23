### Ejemplo 4.5.2
 
Trabajemos en el sistema de dos partículas más simple y no trivial: cada partícula solo puede estar en dos puntos. Consideremos el estado
 
 
### Discusiones
 
1. **Estructura del Estado Cuántico**: El estado se puede expresar como una combinación lineal de productos tensoriales de estados de partículas individuales.
 
2. **Importancia del Producto Tensorial**: Esto resalta la naturaleza del sistema cuántico, donde las propiedades de las partículas no son independientes, y el estado total es una combinación de las contribuciones de cada subsistema.
 
3. **Amplitudes de Probabilidad**: La representación muestra que cada estado individual está asociado con coeficientes \( c_0 \) y \( c_1 \), que representan las amplitudes de probabilidad de cada estado, fundamentales en la mecánica cuántica.
 
4. **Indeterminación Cuántica**: La forma del estado refleja la indeterminación inherente de los sistemas cuánticos, donde el resultado de una medición no se determina hasta que se realiza.
 
5. **Relevancia en Computación Cuántica**: La comprensión de cómo estos estados se combinan es esencial para aplicaciones en computación cuántica, donde las propiedades de superposición y entrelazamiento ofrecen ventajas computacionales.
 
 
### Ejemplo 4.5.3
 
$$
|\psi\rangle = |x_0\rangle \otimes |y_1\rangle + |x_1\rangle \otimes |y_1\rangle
$$
 
A continuación, escribimos esto como combinación lineal:
 
$$
|\psi\rangle = 0|x_0\rangle \otimes |y_0\rangle + 1|x_0\rangle \otimes |y_1\rangle + 0|x_1\rangle \otimes |y_0\rangle + 1|x_1\rangle \otimes |y_1\rangle
$$
 
Luego:
 
$$
|\psi_x\rangle = C_0|x_0\rangle + C_1|x_1\rangle 
$$
 
$$
|\psi_y\rangle = C_0|y_0\rangle + C_1|y_1\rangle
$$
 
Después:
 
$$
|\psi_x\rangle \otimes |\psi_y\rangle = C_0xC_0y|x_0\rangle \otimes |y_0\rangle + C_0xC_1y|x_0\rangle \otimes |y_1\rangle + C_1xC_0y|x_1\rangle \otimes |y_0\rangle + C_1xC_1y|x_1\rangle \otimes |y_1\rangle
$$
Podemos concluir que:
$$
C_0y = 0,
C_1y = 0,
C_0x = 1,
C_1x = 1
$$
Asi que el sistema si es separable.

tiene menú contextual
