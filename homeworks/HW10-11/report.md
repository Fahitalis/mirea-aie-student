# HW10-11 – компьютерное зрение в PyTorch: CNN, transfer learning, detection/segmentation

## 1. Кратко: что сделано

- Для части A выбран датасет `STL10`, поскольку это рекомендуемый базовый вариант для задач классификации, который обеспечивает разумный компромисс между размером и сложностью.
- Для части B выбран датасет `OxfordIIITPet` и трек `segmentation`, поскольку это позволяет хорошо изучить работу с масками и использование предобученных сегментационных сетей типа DeepLabV3.
- В части A сравнивались простая CNN без аугментаций и с ними, а также transfer learning на базе `ResNet18` (head-only vs partial fine-tuning). Во второй части сравнивались базовый и альтернативный (с морфологической фильтрацией) режимы постобработки масок.

## 2. Среда и воспроизводимость

- Python: 3.10+
- torch / torchvision: актуальные версии из requirements
- Устройство (CPU/GPU): (будет обновлено после запуска)
- Seed: 42
- Как запустить: открыть `HW10-11.ipynb` и выполнить Run All.

## 3. Данные

... *Будет заполнено по мере выполнения*

## 4. Часть A: модели и обучение (C1-C4)

... *Будет заполнено по мере выполнения*

## 5. Часть B: постановка задачи и режимы оценки (V1-V2)

... *Будет заполнено по мере выполнения*

## 6. Результаты

Ссылки на файлы в репозитории:

- Таблица результатов: [./artifacts/runs.csv](./artifacts/runs.csv)
- Лучшая модель части A: [./artifacts/best_classifier.pt](./artifacts/best_classifier.pt)
- Конфиг лучшей модели части A: [./artifacts/best_classifier_config.json](./artifacts/best_classifier_config.json)
- Кривые лучшего прогона классификации: [./artifacts/figures/classification_curves_best.png](./artifacts/figures/classification_curves_best.png)
- Сравнение C1-C4: [./artifacts/figures/classification_compare.png](./artifacts/figures/classification_compare.png)
- Визуализация аугментаций: [./artifacts/figures/augmentations_preview.png](./artifacts/figures/augmentations_preview.png)
- Визуализации второй части (примеры сегментации): [./artifacts/figures/segmentation_examples.png](./artifacts/figures/segmentation_examples.png)
- Метрики второй части (сравнение результатов): [./artifacts/figures/segmentation_metrics.png](./artifacts/figures/segmentation_metrics.png)

... *Остальное будет заполнено по завершении*

## 7. Анализ

...

## 8. Итоговый вывод

...
