# MECHANIC

## Qué es el juego
Simulador de taller mecánico en primera persona, estilo low-poly, inspirado en la idea de My Summer Car pero con mecánica simplificada. El jugador empieza con poco, arregla y mantiene motos y avanza. Los trabajos extra y los empleados son opcionales: nunca obligatorios para jugar.

## Sobre el usuario
Principiante total: no sabe programar, ni usar Unity ni Blender. Explica los pasos con claridad, ve por partes pequeñas y pide que pruebe en Unity cuando algo esté listo. El usuario se encarga del arte en Blender poco a poco.

## Reglas del proyecto
- Unity (plantilla Universal 3D / URP), editor de scripts: Visual Studio.
- Scripts en `Assets/Scripts`, organizados por sistema. Un script por clase.
- Nombres de código, clases y variables en inglés; comentarios y explicaciones al usuario en español.
- Modelos en `Assets/Models` (FBX desde Blender: escala 1, rotación aplicada, objetos con nombres claros).
- Escenas en `Assets/Scenes`. Escena de pruebas: `GroundTest`.
- Nunca borrar ni mover archivos sin su `.meta`. Mover assets desde el editor de Unity.
- Una tarea pequeña por vez. Al terminar, el usuario prueba y hace commit.
- Revisar la consola de Unity después de cambiar scripts y corregir los errores antes de dar algo por terminado.

## Git
- Repositorio privado en GitHub (rama `main`). Git LFS para fbx, blend, png, jpg, psd, wav, mp3, ogg.
- Commit después de cada tarea que funcione, con mensaje descriptivo.

## Estado actual
- Proyecto creado, repositorio subido, Unity y Visual Studio conectados.
- Aún no hay sistemas de juego. Solo existe `Assets/prueba.cs` (script de prueba, se puede borrar).

## Primer hito (rebanada mínima)
1. Escena `GroundTest` con suelo y un garaje simple.
2. Controlador en primera persona (caminar, mirar, saltar).
3. Una moto con unas 10 a 15 piezas que se pueden quitar y poner.
4. Mantenimiento mínimo: cambio de aceite y de filtro.
5. Barras de necesidades básicas (hambre, energía).

## Más adelante (no hacer todavía)
Trabajos opcionales, empleados opcionales, carreras, más motos, carros, mundo más grande.

## Decisiones pendientes
- Cómo se monta una pieza: arrastrar y encajar, o tornillo por tornillo.
- Primer negocio o taller del jugador y su ambientación.
