# Simulator-Nissan-leaf-Unity
Simulador de manejo en unity nissan Leaf 2018

1. Instalar [anaconda](https://anaconda.org)
2. Abrir **Anaconda prompt** y crear un nuevo entorno donde instalaremos las dependencias de python necesarias para correr los scripts
    correr en la terminal:
    
        conda env create -f entorno.yml
          
3. El simulador funciona usando la version 5.5.1 de Unity
   Ir a \Simulator\Assets\1_SelfDrivingCar\Scenes, abrir la escena **LakeTrackAutonomous** y darle play:

4. Correr el modelo pre-entrenado:
   -Activar entorno usando conda, run: 
   
        conda activate car-simulator
          
   -Correr el script:
   
        python drive.py model.h5 
