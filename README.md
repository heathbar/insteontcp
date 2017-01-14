# insteontcp
A python package that interacts with the 2012 Insteon Hub (2242-222) PLM interface over it's TCP connection
https://pypi.python.org/pypi/insteontcp

## Installation

```bash
pip3 install insteontcp
```


## Usage
```python
import insteontcp
hub=insteontcp.InsteonTcp('xx.xx.xx.xx')
hub.turn_on('000000')
```

Where xx.xx.xx.xx is the IP address of the 2012 insteon hub and 000000 is the ID of an insteon light connected to the hub

