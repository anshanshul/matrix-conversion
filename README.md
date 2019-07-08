# matrix-conversion

import numpy as np
ar1=np.array([[1,2],[3,4]])
ar2=np.array([[2,8],[4,66]])
print(ar1*ar2)
print(np.dot(ar1,ar2))
tat=np.mat(ar1)
print(tat)
print(type(tat))
tat2=np.mat(ar2)
print(tat*tat2)
print(tat.T)
print(tat.T)
