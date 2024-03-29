# goit-algo-hw-04

Даний код реалізує сортування за допомогою алгоритмів вставок (insertion sort) та злиття (merge sort), а також вимірює час їх виконання на різних об'ємах даних. Для порівняння також використовуються вбудовані алгоритми сортування в Python: sorted та метод sort().

# Отримані результати:

| Algorithm            | Small                | Medium               | Large                |
| -------------------- | -------------------- | -------------------- | -------------------- |
| Insertion Sort       |              0.00030 |              0.16264 |             16.21807 |
| Merge Sort           |              0.00104 |              0.01348 |              0.16384 |
| Timsorted            |              0.00003 |              0.00040 |              0.00516 |
| Timsort              |              0.00002 |              0.00039 |              0.00526 |

# Висновки:


Згідно з результатами емпіричного тестування, видно, що Timsort, який використовується в методі sorted() та sort(), є найшвидшим на всіх об'ємах даних.
- Алгоритм вставок має найгіршу продуктивність на великих об'ємах даних, оскільки має квадратичну складність.
- Алгоритм злиття виявляється ефективнішим за вставки на великих наборах даних, але менш ефективним, ніж Timsort.
- Підтверджується перевага використання вбудованих алгоритмів сортування (таких як Timsort)
- Timsort виявляється набагато ефективнішим, ніж злиття або вставки окремо, на великих наборах даних. Це підтверджується емпіричними даними.
- Timsort використовується як вбудований алгоритм сортування в Python через свою високу ефективність та оптимізації для різних типів даних.
- У реальних застосуваннях зазвичай краще використовувати вбудовані алгоритми сортування, оскільки вони оптимізовані та підтримуються великими ком'юніті.

