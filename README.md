![GitHub repo size](https://img.shields.io/github/repo-size/felipebacelo/LinearRegression?style=for-the-badge)
![GitHub](https://img.shields.io/github/license/felipebacelo/LinearRegression?style=for-the-badge)
![GitHub language count](https://img.shields.io/github/languages/count/felipebacelo/LinearRegression?style=for-the-badge)
![GitHub All Releases](https://img.shields.io/github/downloads/felipebacelo/LinearRegression/total?style=for-the-badge)
![GitHub followers](https://img.shields.io/github/followers/felipebacelo?style=for-the-badge)

# LinearRegression
Simples Exemplo de Regressão Linear em Python.

***

### Desenvolvimento

Desenvolvido em Python através do Jupyter Notebook.

***

### Bibliotecas Utilizadas

* Numpy
* Scipy
* Matplotlib
* Sklearn
* Pandas

***

### Exemplo de Plotagem do Gráfico

```
#realiza o plot da figura
f = plt.figure(figsize=(4, 4), dpi=100) #indica o tamanho da figura
axes = f.add_subplot(111) #cria os objetos para o subplot

#realiza o plot dos dados (pontos no gráfico)
axes.plot(xData, yData,'ro')

#cria os dados para serem utilizados na construção da linha (equação) 
xModel = np.linspace(min(xData), max(xData)) #encontra os valores máximos e mínimos da linha
yModel = equacaoLinear(xModel, *parametrosOtimizados) #aplica a função com os parâmetros obtidos

#realiza o plot da linha
axes.plot(xModel, yModel)
plt.xlabel("Idade")
plt.ylabel("Salário Anual (R$)")
```
***
### Licenças

_MIT License_
_Copyright   ©   2020 Felipe Bacelo Rodrigues_
