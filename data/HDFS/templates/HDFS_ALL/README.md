As same as BGL,
here we used the  parsed BGL files, which are ``HDFS_ALL.txt_structured.csv`` and ``HDFS_ALL.txt_templates.csv``, the format of these files like the files at ``logpai``, link: https://github.com/logpai/loghub/tree/master/HDFS.
After these files are ready, please run these script to generate dataset for training and testing.
```
cd {project}/model
python utils/generate_HDFS_seq.py
``` 

Here we have uploaded the dataset to the cloud storage, link: https://pan.baidu.com/s/1kwEQz1rKUYaOKMIV8mu1ZA?pwd=auhz 