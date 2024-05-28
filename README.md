# Deep-networks-modern-approaches-Lab-3

Так как в предудущей работе нейронка уже и так была улучшена (в нее добавлены слои Dropout и использован оптимизатор Adam), из допустимых улучшений в данной работе были рассмотрены следующие подходы:
1) Добавление аугментаций (обучающий датасет был увеличен в 3 раза)
2) Добавление шедулера (выбран ReduceLROnPlateau)

Новая точность составила 90.70 % в сравнении с предыдущей 87.20 %, т.е. улучшения себя оправдали (однако т.к. датасет увеличился в 3 раза, время обучение увеличилось соответственно):
![image](https://github.com/MEHovick/Deep-networks-modern-approaches-Lab-3/assets/52539883/79e4dc37-596b-4ad9-bc7f-5601e0b38b2a)

Помимо точности были посчитаны и другие метрики:

Precision: 0.91

Recall: 0.91

Confusion Matrix:

![image](https://github.com/MEHovick/Deep-networks-modern-approaches-Lab-3/assets/52539883/ea6b0ab2-1ba4-43ec-9abf-8e680a537ba6)
