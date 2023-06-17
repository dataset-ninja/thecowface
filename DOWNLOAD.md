Dataset **Thecowface** can be downloaded in Supervisely format:

 [Download](https://assets.supervise.ly/supervisely-supervisely-assets-public/teams_storage/A/T/3Z/R6OtRz15K41bSmPNKh8syiNtzT2VSoTyH5X2pM4faw4mRP3imKMz2j2pr8WJrCjmT0PtFPNWFXOeShOftv0jNKLNiTVm5LtcEEoJmtquQOSt84fQdkqC2L8DSt2N.tar)

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