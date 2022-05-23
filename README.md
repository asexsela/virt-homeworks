# virt-homeworks

1. Задача 1 Вкратце опишите, как вы поняли - в чем основное отличие паравиртуализации и виртуализации на основе ОС.
    1. Ответ: Виртуализация основе ОС имеет свои процессы, а Паравиртуализация имеет процессы основной системы, но они разделены доступом, отличием является модификация ядер гостевых операционных систем
2. Задача 2 Выберите тип один из вариантов использования организации физических серверов, в зависимости от условий использования.
    1. Высоконагруженная база данных, чувствительная к отказу 
        1. Ответ: паравиртуализация. Так как физические сервера это дорого и они занимают место, виртуализация уровня ОС не имеет прослойки гипервизора, и при отказекакой нибудь системы откажет вся система
    2. Различные Java-приложения
        1. Ответ: WMware что бы эффективнее использовать ресурсы благодаря удобной системе управления жизненным циклом и ускоренному масштабированию по сравнению с физическими устройствами.
    3. Windows системы для использования Бухгалтерским отделом
        1. Ответ: Hyper-V изначально был частью серверной версии Windows, сердцем Microsoft System Center и нацелен на продуктивные высоконагруженные системы. Windows 10 сделала его так же частью системы и реализаций пользовательской виртуализ
    4. Системы, выполняющие высокопроизводительные расчеты на GPU
        1. Ответ: AWS EC2. Инстансы P3 в Amazon EC2 используют до восьми графических процессоров NVIDIA® V100 с ядрами Tensor и обеспечивают пропускную способность сети до 100 Гбит/с, чтобы создать условия для работы приложений машинного обучения и высокопроизводительных вычислений в облаке
3. Задача 3 Как вы думаете, возможно ли совмещать несколько типов виртуализации на одном сервере? Приведите пример такого совмещения.
    1. Ответ: Затрудняюсь ответить, возможно на апаратную или паравиртуализацию можно установить виртуализацию уровня ОС

    cdscds