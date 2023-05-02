**EX1**
for example
import numpy as np

test = np.nan + None
print(test)  # Output: nan
**Outtome will be an error**
this is the error "TypeError: unsupported operand type(s) for +: 'float' and 'NoneType'"

**EX2**
example
import pandas as pd
int_series = pd.Series([None], dtype=int)
int_series
**The out come is**

**EX3**
I am Expecting to see results same as example3
import pandas as pd
import numpy as np

example3 = pd.Series([0, np.nan, '', None])
example3.notnull()

**EX4**
