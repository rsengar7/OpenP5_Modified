## OpenP5 for ML100K Dataset with T5 Model

This is the working code for the training and checkpoint for ML100K dataset.

## Dataset for Training 

Download the data from [Google Drive link](https://drive.google.com/drive/folders/1W5i5ryetj_gkcOpG1aZfL5Y8Yk6RxwYE?usp=sharing), and put them into `data` folder.

The training command can be found in `command` folder. Run the command such as 

```
cd command
sh ML100K_collaborative.sh
```

## Checkpoint

Download the checkpoint from [Google Drive Link](https://drive.google.com/drive/folders/19v7vgNBkIRdBm4FwPgHHiRz6Dnom29aR?usp=sharing), and put them into `checkpoint` folder.

The evaluation command can be found in `test_command folder`. Run the command such as 

```
cd test_command
sh ML100K_collaborative.sh
```
