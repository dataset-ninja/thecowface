Dataset **Thecowface** can be downloaded in Supervisely format:

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/l/K/uT/CHpSvOaMM6Kfoh6Fp4NEMYH1qaGz08PsESyyxNWNNm69DXvVosebDFBqtl7EfolqgLp8b19bllTgjN5DnPG51645yOxkXdSEIBXMxZG9VWhuanR1Sw3xC5mh0oQ9.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Thecowface', dst_path='~/dtools/datasets/Thecowface.tar')
```
The data in original format can be 🔗[downloaded here](https://universe.roboflow.com/face-cow/thecowface/dataset/1/download)