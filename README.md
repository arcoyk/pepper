# pepper

```
$export PYTHONPATH=${PYTHONPATH}:/pynaoqi-python2.7-2.0.5.3-mac64/
$export DYLD_LIBRARY_PATH=${DYLD_LIBRARY_PATH}:/pynaoqi-python2.7-2.0.5.3-mac64/
```

```python:hello.py
from naoqi import ALProxy
tts = ALProxy("ALTextToSpeech", "192.168.100.19", 9559)
tts.say("4328903248329048903284023")
```

```
python hello.py
```
