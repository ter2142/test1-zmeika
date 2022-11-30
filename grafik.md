import numpy as np
import matplotlib.pyplot as plt



#f(x) = sin(x)
y = lambda x: np.sin(x)
fig = plt.subplots()
x = np.linspace(-8,11,5000)
plt.plot(x,y(x))


plt.show()
