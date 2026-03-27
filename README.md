# Deep Learning — ВМК МГУ (4 курс)

Task 1 — Полносвязные сети и классификация (MNIST) ≥ 92% на тесте

PyTorch · TorchVision · NumPy · Matplotlib

---

Task 2 — Сегментация и регуляризация (FashionMNIST)

a) Переобучение и борьба с ним (FashionMNIST)
- Исследование переобучения на FashionMNIST
- Сравнение методов регуляризации: Dropout, BatchNorm, L1/L2

b) Семантическая сегментация животных
- Трёхклассовая сегментация: фон / кошка / собака
- PSPNet-подобная архитектура с предобученным ResNeXt в качестве энкодера
- Реализация кастомных loss-функций и метрик

Результаты сегментации:
| Метрика | Значение |
|---|---|
| Mean IoU | > 0.83 |
| Mean Recall | > 0.94 |

PyTorch · TorchVision · NumPy · Matplotlib
