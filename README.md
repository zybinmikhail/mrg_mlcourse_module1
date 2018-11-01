# mrg_mlcourse_module1
MNIST digit recognizer
Используется алгоритм softmax, со стохастическим градиентным спуском. 
В данные добавлены квадратичные признаки, затем данные отнормированы.
Было проведено порядка 1200 итераций, что заняло примерно час.



Поведение на тренировочных данных:
             precision    recall  f1-score   support

          0       0.97      0.95      0.96      6017
          1       0.97      0.95      0.96      6894
          2       0.89      0.92      0.90      5752
          3       0.89      0.91      0.90      6040
          4       0.93      0.92      0.92      5919
          5       0.86      0.89      0.87      5212
          6       0.96      0.94      0.95      6033
          7       0.93      0.93      0.93      6226
          8       0.89      0.88      0.88      5919
          9       0.90      0.89      0.90      5988

avg / total       0.92      0.92      0.92     60000

Поведение на тестовых данных
             precision    recall  f1-score   support

          0       0.98      0.95      0.96      1011
          1       0.98      0.96      0.97      1153
          2       0.88      0.93      0.91       980
          3       0.91      0.90      0.90      1019
          4       0.93      0.91      0.92      1005
          5       0.85      0.90      0.88       842
          6       0.95      0.93      0.94       975
          7       0.92      0.92      0.92      1020
          8       0.89      0.87      0.88      1003
          9       0.89      0.90      0.90       992

avg / total       0.92      0.92      0.92     10000

При увеличении числа эпох качество должно возрасти.
