## To run pytest
```
pytest <nameoftest>.py
```
## Make pytest output verbose
```
pytest -v <nameoftest>.py
```
## Interactive debugging:
- To run within a file
```
import ipdb; ipdb.set_trace()
```
- To run within a pytest test file:
```
import ipdb; ipdb.set_trace()
```
and run in terminal
``` 
  pytest -s <nameoftest>.py 
``` 
