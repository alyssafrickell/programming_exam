#TreeBalancing Benchmark

Порівняльний аналіз стратегій балансування бінарних дерев пошуку (BST).
Проєкт розроблено в рамках лабораторної роботи з програмування (Project 2.Research).
Джерела

## Команда
* **Іра** — Архітектура, PBT, Benchmarking
* **Лера** — AVL Tree, Splay Tree
* **Аня** — Red-Black Tree (RBT)

## Джерела і інструмнети
* **LLM:** Базовий каркас C++ коду, абстрактний клас `BSTInterface` та система заміру часу для бенчмаркінгу були згенеровані за допомогою **Google Gemini**.
* **Матеріали для дослідження:**
  * [GeeksforGeeks: AVL Tree Data Structure](https://www.geeksforgeeks.org/avl-tree-set-1-insertion/) - використано для реалізації рекурсивного перерахунку висоти та алгоритмів малих/великих поворотів.
  * [Wikipedia: Red–black tree](https://en.wikipedia.org/wiki/Red%E2%80%93black_tree) - теоретична база щодо інваріантів кольорів та 4-х випадків балансування при вставці.
  * [Splay Trees (Sleator & Tarjan, 1985)](https://www.cs.cmu.edu/~sleator/papers/self-adjusting.pdf) - оригінальна стаття розробників структури, використана для розуміння евристики `splay` (zig-zig, zig-zag) та амортизованої складності.

## 
* **Мова:** C++ (чисті вказівники, без STL для структур)
* **Agile:** GitHub Projects (Kanban), Issue tracking
* **Analytics:** Time Tracking (див. `time_tracking.csv`)
* **Insights:** Developer Diary (див. `dev_diary.md`)
