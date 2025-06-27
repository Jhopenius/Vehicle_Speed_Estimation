 Установка
1. Клонируйте этот репозиторий:
 ``
 git clone https://github.com/Jhopenius/Vehicle_Speed_Estimation.git
 cd Vehicle_Speed_Estimation
 ``
2. Создайте новое окружение:
Используйте  Conda
 ```
 conda env create -f conda.yml
 conda activate yolov9-deepsort
 ```
3. Загрузите входное видео:
  ```
 mkdir content
 wget -P content https://github.com/AarohiSingla/Speed-detection-of-vehicles/raw/main/highway.mp4
 wget -P content https://github.com/AarohiSingla/Speed-detection-of-vehicles/raw/main/highway_mini.mp4
 ``` 
4. Запустите:
 ``
 python object_tracking.py
 ```





