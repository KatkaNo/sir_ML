# SVD
1. Для любой ЧБ картинки реализовать SVD-сжатие с различными уровнями сжатия. Изобразить результаты.
2. Сопоставить время умножения матрицы, заданной сл. образом: $$A(i,j)=sin(i+j)+2,$$ размером $$2048×2048$$, на рандомный вектор с использованием сжатия и без использования сжатия.
3. Реализовать ε-округление для матриц через SVD.

[Realization on github](https://github.com/KatkaNo/sir_ML/blob/main/hw/SVD.ipynb)

# PageRank
1. Для матрицы $$A(i,j)=\frac{1}{i+j+1},$$ размера $$M×N=2048$$ вызвать SVD и RSVD (rank = 10, 15) и сравнить погрешности и время выполнения программы.
2. Найти формулу перехода от матриц инцидентности к матрице смежности.
3. Вычислить PageRank для Московского метро.

[Realization on github](https://github.com/KatkaNo/sir_ML/blob/main/hw/graph.ipynb)

# Metropolis
1. Для $$f(x)=e^{-\frac{x^2}{2}}$$ сделать выборку $$10^6$$ методом Метрополиса.
2. С помощью библиотеки SALib провести анализ чувствительности для $$f(x_1,x_2,x_3)=10^{-4}sin(x_1+x_2)+x_3$$.
3. В канонической ф. оценить сложность вычисления D(A) при R.

[Realization on github](https://github.com/KatkaNo/sir_ML/blob/main/hw/Sobol.ipynb)

# SVM
[Realization on github](https://github.com/KatkaNo/sir_ML/blob/main/hw/SVM.ipynb)
# Lasso
[Realization on github](https://github.com/KatkaNo/sir_ML/blob/main/hw/Lasso.ipynb)
# GradientBoosting
[Realization on github](https://github.com/KatkaNo/sir_ML/blob/main/hw/GradientBoosting.ipynb)