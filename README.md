# accelerating-pandas-with-modin

We all love working with pandas but it is inherently single-threaded which makes it slow and it can be painfully annoying sometimes. One easy way to accelerate Pandas is to use Modin
https://modin.readthedocs.io/en/latest/

- pip install modin[all]
- import modin.pandas as pd

Is all you need now use pd(pandas) as you used to but now it will run on multiple cores automatically :D

![Example](https://github.com/BahramKBaloch/accelerating-pandas-with-modin/blob/main/test.png)



Note: For this to work you must have multiple cores available. (google-colab only provides a single-core)

