# PI1_unet-graphene-segmentation
Segmentación Semántica de Capas de Grafeno mediante Deep Learning (U-Net/EfficientNet-B5)

Este repositorio contiene el código, modelos y análisis para la segmentación semántica automática de escamas de grafeno en imágenes de microscopía óptica.

El proyecto aborda el desafío del desbalance de clases y la escasez de datos (few-shot) utilizando una arquitectura U-Net con un encoder EfficientNet-B5 preentrenado. Se empleó una función de pérdida híbrida y optimización bayesiana para alcanzar una alta precisión (mIoU superior a 0.80) en la distinción entre las clases críticas: few-layer, bulk y background.

Tecnologías Clave: PyTorch, Segmentation Models PyTorch, EfficientNet-B5, Optimización Bayesiana (Optuna).
