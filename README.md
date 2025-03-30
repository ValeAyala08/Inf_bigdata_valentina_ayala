# Inf_bigdata_valentina_ayala

Autores:
Valentina Ayala Zapata, Luisa A. Carvajal Mazo y Hugo A. Carvajal

Clonar el repositorio desde https://github.com/ValeAyala08/Inf_bigdata_valentina_ayala.git

Ejecutar los siguientes pasos
Verifica tu version de python

    $ python-version: '3.9.2'
paso1 crea entorno virtual
    $ python -m venv venv
paso2 - activar entorno virtual
    $ ./venv/Scripts/activate   
paso3 - actualizar pip
    $ pip install --upgrade pip
paso4 - instalar dependencias
    $ pip install -e .
paso5 - Ejecutar ingestion
    $ python src/bigdata/ingestion.py 
paso6 - Ejecutar Auditoria
    $ python src/bigdata/audit_script.py
paso7 - Ejecutar datos sucios
    $ python src/bigdata/data_sucio.py
paso8 - Ejecutar limpieza
    $ python src/bigdata/cleaning.py
paso9 - Ejecutar Enriquesimiento
        run: python src/bigdata/enrichement.py

NOTA IMPORTANTE:
Despues de hacer git push al repositorio remoto es muy importante si se va a trabajar en codigo local que se bajen los cambios del remoto al local para evitar divergencias en las ramas. Una vez hecho los cambios y sincronizada las ramas, puede hacer nuevamente git push. Esto debido a que el workflows ejecuta comandos que escriben archivos del repositorio y estos archivos no estan ignorados para git.

pico y chao.