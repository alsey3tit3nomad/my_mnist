# MNIST Classifier on PyTorch

Проект на PyTorch для классификации рукописных цифр из датасета MNIST.

## Модель
- NeuralNetMLP: написал на чистом numpy нейронку с одним скрытым слоем. 
- torch_NeuralNetMLP: написал нейронку на Pytorch. 

## Результаты NeuralNetMLP
```Python
print(f'Initial test MSE: {mse:.1f}')
```
Initial validation MSE: 0.0
```Python
print(f'Test MSE: {mse:.1f}')
```
Test accuracy: 96.1%

## Результаты torch_NeuralNetMLP
```Python
print(f'Test accuracy: {is_correct.mean():.4f}')
```
Test accuracy: 0.9709
