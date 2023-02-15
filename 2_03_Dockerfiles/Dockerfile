FROM tensorflow/tensorflow:latest-gpu-jupyter
RUN apt-get update && apt-get upgrade -y
RUN apt-get install graphviz -y --fix-missing
RUN python3 -m pip install --upgrade pip
RUN pip install matplotlib
RUN pip install jupyterlab 
RUN pip install sympy
RUN pip install pandas
RUN pip install scipy
RUN pip install pydot
RUN pip install scikit-learn 
RUN pip install seaborn
RUN pip install opencv-contrib-python
RUN pip install opencv-python
RUN pip install opencv-python-headless
CMD ["/bin/bash"]
