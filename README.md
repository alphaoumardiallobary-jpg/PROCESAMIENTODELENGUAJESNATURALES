# ProcesamientodeLenguajesNaturales
NLP: PROCESOS DE LENGUAJES NATURALES.
Estos son los paquetes y versiones instalados que se utilizaron en este curso.
 Todos se instalaron en un entorno conda
 (vea más abajo cómo los creé).

nltk==3.9.1 
pandas==2.2.3 
matplotlib==3.10.0 
spacy==3.8.3 
textblob==0.18.0.post0 
vaderSentiment==3.3.2 
transformers==4.47.1 
scikit-learn==1.6.0 
gensim==4.3.3 
seaborn==0.13.2 
torch==2.5.1 
ipywidgets==8.1.5

Los entornos virtuales son una excelente manera de administrar 
diferentes paquetes para distintos proyectos.
Crear un entorno virtual para esta sección del curso 
te permite asegurarte de usar los paquetes correctos para continuar,
sin afectar a los demás paquetes que ya tengas instalados.

conda create --name nlp_course_env python=3.11
conda activate nlp_course_env
pip install nltk==3.9.1 pandas==2.2.3 matplotlib==3.10.0 spacy==3.8.3
 textblob==0.18.0.post0 vaderSentiment==3.3.2 transformers==4.47.1 
   scikit-learn==1.6.0 gensim==4.3.3 
     seaborn==0.13.2 torch==2.5.1 ipywidgets==8.1.5
python -m spacy download en_core_web_sm
pip install ipykernel jupyterlab notebook
python -m ipykernel install --user --name=nlp_course_env
