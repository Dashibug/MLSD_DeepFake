# MLSD_DeepFake

Проект в рамках ML System Design: **Бенчмарк методов генерации DeepFake для борьбы с мошенничеством**.

## Цель

Построить воспроизводимую библиотеку, которая позволяет:
- собирать датасет реальных и синтетических deepfake фото и видео;
- прогонять через него разные модели детекции;
- сравнивать решения по качеству (TPR/FPR, ROC-AUC), скорости и устойчивости к новым атакам;
- давать рекомендации по выбору модели для продакшена в сценариях KYC и антифрода.

## Стек

- Python 3.10+
- Computer Vision / Deep Learning (PyTorch / TensorFlow, TBD)
- Ruff (линтер + форматтер)
- pre-commit

## Установка

```bash

pip install --upgrade pip
pip install ruff pre-commit

pre-commit install
