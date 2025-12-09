# codesMLE
import sys
import numpy as np
import pandas as pd
import matplotlib
import sklearn

print("===Library Versions ")
print(f"Python    :{sys.version.split()[0]}")
print(f"Numpy    :{np.__version__}")
print(f"Pandas    :{pd.__version__}")
print(f"Matplotlib    :{matplotlib.__version__}")
print(f"scikitlearn    :{sklearn.__version__}")


from sklearn.linear_model import LinearRegression
test_model=LinearRegression()
print("Libraries imported successfully")
