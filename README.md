# ReadMe
These are compiled binaries（libmxnet.dll and mxnet_xx.dll）and their DLL dependencies on Windows.

1. Looking on the filename which have edition of mxnet ,cuda ,and python.
2. To extract a zip file to mxnet/python/mxnet/ . 
3. Running `python -m  pip install .\python\` .
4. The test code .
```
import mxnet.numpy as nd
import mxnet as mx

a = nd.array([1, 2, 3], ctx=mx.gpu())
print(a)
```
