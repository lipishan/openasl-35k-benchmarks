# Large-Scale 3D Representations for Continuous American Sign Language Understanding

This is the official Repo for "Large-Scale 3D Representations for Continuous American Sign Language Understanding". This sepcific codebase is for Sign Language Production.

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

> Sign Representations can be found here: [Data](https://huggingface.co/datasets/dongludeeplearning/OpenASL3D_Dataset/), ```texts``` folder can be found here: [texts](https://buffalo.box.com/s/5fbomz6rr007dcrvc15ek7uzur13wypl). For OpenASl-35k, [download](https://buffalo.box.com/s/15nanqj5bmw0vnab6ekk0qrmyrge602r). Please ensure to unzip the ```texts``` and ```openasl-35k pickle``` for ruuning



## Train
```
bash run_train.sh
```

> For Sign Language Translation pipeline, please [refer](https://github.com/neccam/slt)
> Sign Language Production code based on [github](https://github.com/GuyTevet/motion-diffusion-model)
