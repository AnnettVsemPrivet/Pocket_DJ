### Pocket_DJ

Главная цель проекта - создать приложение, позволяющее сортировать разнообразную музыку по жанрам и прослушивать отсортированный вариант в виде плейлиста. 
Для этого планируется создать модель классификации, к которой добавится сортирующий алгоритм по принципу - в рамках жанра сначала идут песни в которых модель классификации больше всего уверена, 
в рамках общего плейлиста - жанры сортируются по близости их центров. На данный момент найден [датасет](https://github.com/mdeff/fma), из которого планируется взять файл fma_small.zip для обучения и валидации. 
Признаки в первую очередь будут браться из завуковых характеристик с помощью библиотеки Librosa. В качестве модели классификации будут изучены разные модели, в том числе K-Nearest Neighbors, Support Vector Machine, Recurrent Neural Network (LSTM). Будет выбрана лучшая по соотношению качества и скорости классификации.
