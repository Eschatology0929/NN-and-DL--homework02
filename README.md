# NN-and-DL--homework02
## Preparation for Training & Testing
### 1.Download the training, validation, test data and VOCdevkit
```
wget http://host.robots.ox.ac.uk/pascal/VOC/voc2007/VOCtrainval_06-Nov-2007.tar
wget http://host.robots.ox.ac.uk/pascal/VOC/voc2007/VOCtest_06-Nov-2007.tar
wget http://host.robots.ox.ac.uk/pascal/VOC/voc2007/VOCdevkit_08-Jun-2007.tar
wget http://host.robots.ox.ac.uk/pascal/VOC/voc2012/VOCtrainval_11-May-2012.tar
```
### 2.Extract all of these tars into one directory named VOCdevkit
```
tar xvf VOCtrainval_06-Nov-2007.tar
tar xvf VOCtest_06-Nov-2007.tar
tar xvf VOCdevkit_08-Jun-2007.tar
tar xvf VOCtrainval_11-May-2012.tar
```
### 3.It should have this basic structure
```
$VOCdevkit/                           # development kit
$VOCdevkit/VOCcode/                   # VOC utility code
$VOCdevkit/VOC2007                    # image sets, annotations, etc.
$VOCdevkit/VOC2012                    # image sets, annotations, etc.
# ... and several other directories ...
```
## Train for PASCAL VOC
Run 'train_voc.py'
## Evaluation for PASCAL VOC
Run 'eval_voc.py'
## Detect Image
Run 'detect.py'
