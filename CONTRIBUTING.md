# Guías para Contribuciones a RedConciencia

¡Gracias por tu interés en contribuir a este proyecto de conciencia artificial! Este repositorio desarrolla una red neuronal con 5 instancias de ConcienciaArtificial para procesar datos de sensores emocionales (entrada de 262,144 dimensiones) y simular simbiosis humano-máquina. Sigamos estas guías para mantener el código limpio y colaborativo.

## Reportando Bugs o Solicitando Features
- Abre un [issue](https://github.com/diegomy2002-source) con un título claro (e.g., "Error en forward pass con datos de 512² dims").
- Describe el problema: Incluye pasos para reproducir, versión de PyTorch, y datos de ejemplo (e.g., tensor de spikes neuronales).
- Para features: Explica cómo se integra con el modelo (e.g., agregar LSTM para memoria en sensores inalámbricos).

## Haciendo una Contribución
1. **Forkea el repositorio** y clona tu fork: `git clone https://github.com/diegomy2002-source.git`.
3. **Crea una rama**: `git checkout -b mi-feature/fix-spikes-sensor`.
4. **Instala dependencias**: Usa `pip install torch numpy` (o un requirements.txt).
5. **Desarrolla y prueba**:
   - Sigue el estilo de código: Usa PEP 8 (e.g., con black: `pip install black; black .`).
   - Agrega tests: Escribe unit tests con pytest (e.g., prueba el forward con entrada de 262,144 dims).
   - Documenta cambios: Actualiza el README si modificas capas o datos simulados.
6. **Commit y push**: Usa mensajes claros (e.g., "feat: Agregar dropout para ruido neuronal"). `git push origin mi-feature`.
7. **Abre un Pull Request (PR)**:
   - Referencia el issue relacionado.
   - Explica qué cambia y por qué (e.g., "Mejora convergencia en entrenamiento con MSELoss").
   - Incluye resultados de pruebas (e.g., pérdida final ~0.008).

## Estilo de Código y Mejores Prácticas
- Usa PyTorch para modelos; mantén dimensiones consistentes (e.g., 512² para sensores).
- Maneja errores: Incluye try-except para datos ruidosos (e.g., spikes de Neuralink-like).
- Ética: Asegura que contribuciones respeten privacidad en datos emocionales.
- No rompas compatibilidad: Prueba con datasets simulados antes de mergear.

## Preguntas
Si tienes dudas, abre un issue o únete a la discusión en [https://www.linkedin.com/in/diego-muñoz-yllescas-89231b365]. ¡Tu contribución puede avanzar la simbiosis humano-máquina!

## Atribución
Basado en las guías de GitHub y open source best practices.
