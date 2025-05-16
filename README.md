# Large-Scale 3D Representations for Continuous American Sign Language Understanding

This is the official Repo for "Large-Scale 3D Representations for Continuous American Sign Language Understanding".

## Dataset:
Prepare the data, we uploaded the data to HuggingFace. use  ```hugginface-cli``` to download the data to under ```data-bin``` under the main folder. Create one, if not present. The folder should looks like:

```
|--data-bin/
|  |--motions/
|  |  |--<file1.pt>
|  |  |--<file2.pt>
|  |-- texts/
```


### For OpenASL-35k
```
|--data-bin/
|  |--motions/
|  |  |--<file.train.pkl>
|  |  |--<file.test.pkl>
|  |-- texts/
```

> Note, due to limit to per folder in Huggingface, we uploaded data in parts, please ensure to combine them in a single folder called ```motions```. ```data``` can be found here: [Data](https://huggingface.co/datasets/dongludeeplearning/OpenASL3D_Dataset/), ```texts``` folder can be found here: [texts](https://buffalo.box.com/s/5fbomz6rr007dcrvc15ek7uzur13wypl). For OpenASl-35k, [download]()



## Train
```
bash run_train.sh
```
