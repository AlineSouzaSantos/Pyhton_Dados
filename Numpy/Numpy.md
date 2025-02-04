# NumPy

NumPy é uma biblioteca fundamental para a computação científica em Python. Ela fornece suporte para arrays e matrizes multidimensionais, além de uma coleção de funções matemáticas para operar nesses arrays de maneira eficiente.

## Principais Características

- **Arrays N-Dimensionais**: NumPy introduz o objeto `ndarray`, que é uma estrutura de dados eficiente para armazenar e manipular grandes conjuntos de dados.
- **Operações Matemáticas**: Oferece uma vasta gama de funções matemáticas, incluindo operações elementares, álgebra linear, transformadas de Fourier e geração de números aleatórios.
- **Integração com outras Bibliotecas**: NumPy é frequentemente usado como base para outras bibliotecas científicas em Python, como SciPy, Pandas e Matplotlib.
- **Desempenho**: As operações em arrays NumPy são implementadas em C, o que proporciona um desempenho muito superior em comparação com listas Python tradicionais.

## Exemplo de Uso

```python
import numpy as np

# Criar um array 1D
arr = np.array([1, 2, 3, 4, 5])
print("Array 1D:", arr)

# Criar um array 2D
arr_2d = np.array([[1, 2, 3], [4, 5, 6]])
print("Array 2D:")
print(arr_2d)

# Operações matemáticas
arr_sum = np.sum(arr)
print("Soma dos elementos do array 1D:", arr_sum)

arr_mean = np.mean(arr_2d)
print("Média dos elementos do array 2D:", arr_mean)