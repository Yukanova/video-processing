# video-processing
Обработка видеопотока сверточной нейронной сетью для поиска опасного контента. В результате работы программы сохраняется выходное видео, а тайм-коды детекции записываются в текстовый файл и базу данных. 

Графический интерфейс создан с помощью библиотеки Tkinter:
![alt text](https://raw.githubusercontent.com/Yukanova/video-processing/main/%D0%B8%D0%BD%D1%82%D0%B5%D1%80%D1%84%D0%B5%D0%B9%D1%81.png)

После обработки сохраняется видео с ограничивающими рамками:
![alt text](https://raw.githubusercontent.com/Yukanova/video-processing/main/output_video.gif)

Также сохраняются тайм-коды детекции в текстовый файл и базу данных sqlite:

![alt text](https://raw.githubusercontent.com/Yukanova/video-processing/main/%D0%B1%D0%B4.png)

![alt text](https://raw.githubusercontent.com/Yukanova/video-processing/main/time.png)
