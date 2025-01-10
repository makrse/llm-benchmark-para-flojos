# llm-benchmark-para-flojos
Es un mini projecto que parte de base del repositorio ingles DeepEval, para hacer benchs de forma fácil.
Debido a que para poder hacer los benck requiere que leas muchos docs,videos,etc puede convertirse algo muy engorroso, es por eso que surge este mini-projecto como hobby personal.

Solo se enfoca por el momento a los modelos gguf y el uso de la gpu(cuda)

# Cómo usarlo:

1. Crea un entorno virual usando anaconda[conda] ó python venv, luego al instalar escoges 1 de 2:
   - python version 3.10(ideal)
   - python version 3.10.8(El que uso por el momento, no he probado otras versiones de python)
2. Instala llama.cpp (python) 
   - [No te podria guiar en la instalación, debido que los errores que ocurre depende de cada sistema, Hare una guia en un futuro con todos las soluciones posibles.]
3. Descargate el repositorio DeepEval en github, solo su carpeta principal y luego creas tu una carpeta vacia y lo pones ahi.
>
4. pip install -U deepeval==2.1.2
>
5. Descarga mi repo las carpetas y los archivos y ponlo en la carpeta principal, si te pide reemplazar le das que si.
>
6. Abres el archivo del tipo de bench que quieres usar y modificas los parametros a tu gusto pero ten en cuenta del modelo llm que usas y modificas los parametros de acuerdo a ello.
>
7. Inicializas.
    - py bench_type.py

# Notas finales:
Gracias al equipo de DeepEval y al Llama.cpp python por su trabajo.
Hare subidas y mejoras de los archivos en mi tiempo libre, hacer todos los tipos de bench puede ser contraproducente en cierta manera, muchos datasets algunos estan mal formados
y como todo bench tiene sus contras, asi que te recomiendo que escojas algunos pocos que investigues bien y te pueda servir.


Si usas mi repo y te es útil, no olvides mencionarlo, cualquier idea me lo podes decir, aunque lo que hago esto para un experto es algo sencillo, es una forma que aprendo, puede tener errores.
Si tienes sugerencias,etc me podes mandar mensaje y lo vere en mi tiempo libre.
