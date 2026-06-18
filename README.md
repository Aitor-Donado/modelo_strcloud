# modelo_strcloud

Página de streamlit que usa un modelo de ML. Preparado para desplegar en cloud.

Para mayor sencillez sólo requiere de la librería `streamlit` para la interfaz y `xgboost` para el modelo. Ambas cosas están ya en `requirements.txt`. 

**Streamlit cloud** instalará todo lo que encuentre en requirements por lo que es necesario actualizarlo con `pip freeze > requirements.txt` si hacemos algún cambio en el código que requiera instalar algo adicional.

Hay un secreto en `.streamlit/secrets.toml` que se muestra en la parte inferior de la página. Es simplemente para que veamos cómo hay que añadirlo a Streamlit Cloud, ya que no va a estar en github.