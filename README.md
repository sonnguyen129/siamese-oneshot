# siamese-oneshot
Keras implementation of paper [Siamese Neural Networks for One-shot Image Recognition](https://www.cs.cmu.edu/~rsalakhu/papers/oneshot1.pdf)
## Installation
To run, you'll first have to clone this repo and install the dependencies
```
git clone https://github.com/sorenbouma/keras-oneshot
cd keras-oneshot
sudo pip install -r requirements.txt
```
Then you'll need to download the omniglot dataset and preprocess/pickle it with the load_data.py script.
```
git clone https://github.com/brendenlake/omniglot
python load_data.py --path <PATH TO THIS FOLDER>
```
Then you can run the jupyter notebook.
```
SiameseNet.ipynb
SiameseNet_VGG.ipynb
```
**Note**: SiameseNet implement the original architecture introduced in paper, SiameseNet_VGG fine tune pretrain VGG model
## TO DO
- [x] Fine tuning pretrain with the original Siamese architecture
- [ ] Clean code, update Tensorflow 2.x 
