# modified-fixed-point-iteration
Modifying fixed point iteration for convergence

## Method
Use simple reflection for updating the next point

## Result
![3-org](https://user-images.githubusercontent.com/20160685/121988956-3de44e80-cdd6-11eb-8a63-fbb1e8a3cc51.png)
![3-mod](https://user-images.githubusercontent.com/20160685/121988952-3c1a8b00-cdd6-11eb-8f95-e62d27d6d618.png)       
While original algorithm diverges, modified algorithm converges to the exact root where g'(x) > 1


## Limitation
![4-org](https://user-images.githubusercontent.com/20160685/121988959-3e7ce500-cdd6-11eb-8ddb-3aaf8b8c66f3.png)
![4-mod](https://user-images.githubusercontent.com/20160685/121988957-3e7ce500-cdd6-11eb-8ee0-2c306aff9200.png)      
Further research on the case where g'(x) < -1 is necessary, while showing better performance than the original with respect to error.

## Contributor
