# Project Title
Quantum States and Systems: A Study on Two-Particle Systems

## Project Description
Este proyecto explora los conceptos de mecánica cuántica aplicados a sistemas de partículas, centrándose en la representación de estados cuánticos y sus combinaciones lineales mediante productos tensoriales. Se desarrollan ejemplos específicos que ilustran la estructura de los estados cuánticos y su relación con la probabilidad en la computación cuántica.

## Getting Started
Estas instrucciones te ayudarán a obtener una copia del proyecto en funcionamiento en tu máquina local para fines de desarrollo y pruebas. Consulta la sección de despliegue para obtener notas sobre cómo implementar el proyecto en un sistema en vivo.

### Prerequisites
Para instalar este software, necesitas tener instaladas las siguientes bibliotecas:

- NumPy: para cálculos matemáticos y manipulaciones de matrices.
- Matplotlib: opcional, para visualizaciones gráficas.

Instalación de las bibliotecas necesarias:

```bash
pip install numpy matplotlib
## Deployment
Para implementar este proyecto en un sistema en vivo, sigue los siguientes pasos:

1. **Configuración del Entorno**: Asegúrate de que el entorno de producción tenga todas las dependencias necesarias instaladas, como NumPy y Matplotlib.

2. **Configuraciones de Seguridad**: Revisa las configuraciones de seguridad, como la restricción de acceso a ciertas funcionalidades y la validación de entradas de usuarios para evitar inyecciones de código o datos maliciosos.

3. **Optimización del Rendimiento**: Utiliza técnicas de optimización, como la minimización de cálculos innecesarios y la carga diferida de datos, para mejorar el rendimiento del sistema.

4. **Monitoreo y Registro**: Implementa soluciones de monitoreo para seguir el rendimiento del sistema y registrar eventos importantes para facilitar la depuración.

5. **Pruebas Previas al Despliegue**: Realiza pruebas exhaustivas en un entorno de preproducción antes de llevar el proyecto a producción.

## Built With
- **NumPy** - La biblioteca utilizada para cálculos numéricos.
- **Matplotlib** - Usada para visualizaciones gráficas.

## Contributing
Por favor, lee el archivo [CONTRIBUTING.md](CONTRIBUTING.md) para conocer nuestros códigos de conducta y el proceso para enviar solicitudes de extracción.

## Versioning
Usamos SemVer para el versionado. Para las versiones disponibles, consulta las etiquetas en este repositorio.

## Authors
Jacobo Diaz Alvarado - Trabajo inicial




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



