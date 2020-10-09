# Machine-Learning exercises

## Problema 1:

Model creating to predict the vehicle consumption from the following variables: 
- Cylinders
- Displacement
- Power
- Weight
- Acceleration
- Car year
- Origin
- Consumption (mpg)

The autos characteristics units is not in the international system. The "Origin" variable is a code identify the origin country. 

## Problema 2:

Create a dataset using the following code:

trX = np.linspace(-1, 1, 101)

trY = np.linspace(-1, 1, 101)

for i in range(len(trY)):

trY[i] = math.log(1 + 0.5 * abs(trX[i])) + trX[i] / 3 + np.random.randn() * 0.033

Use Theano to get the W_0 and W_1 parameters of the following model:
y = log (1+ w0|x|)+ w1|x|

## Problema 3:

The crime_data.csv file contains the number of crimes per 100,000 inhabitants in each of the United States states, as well as the percentage of the population that is urban. The crimes have been grouped into: assault, murder and rape.

Segment this data set using k-means and obtain the centroids of each cluster and the list of the states in each of the clusters. To do this, the optimal cluster number into which the data set is divided must be found.

