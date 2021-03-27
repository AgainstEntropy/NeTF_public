# NeTF_public
The repository is the released code for paper "Non-line-of-Sight Imaging via Neural Transient Fields". [[Paper]](https://arxiv.org/abs/2101.00373#:~:text=Title%3ANon-line-of-Sight%20Imaging%20via%20Neural%20Transient%20Fields.%20Non-line-of-Sight%20Imaging,within%20a%20pre-defined%20volume%29%20of%20the%20hidden%20scene.)

The preprocessed data we use can be downloaded at [[Google Drive]](https://drive.google.com/file/d/1kGVrFcNZZbZs0ute_roEOg5UkYeh3jRl/view?usp=sharing) or [[Baidu Netdisk]](https://pan.baidu.com/s/16lWXwhm8CbXWAumJmlw9MQ) with password: netf

The raw data can be downloaded at [Zaragoza NLOS synthetic dataset](https://graphics.unizar.es/nlos_dataset.html), [f-k migration](http://www.computationalimaging.org/publications/nlos-fk/) and [Convolutional Approximations](https://imaging.cs.cmu.edu/conv_nlos/)

# Environment setup
Make sure that the dependcies in `requirements.txt` are installed, or they can be installed by 
```
"pip install -r requirements.txt"
```

# How to run
Make sure that data is place correctly like
```
project
│   README.md
│   file001.txt    
│
└───folder1
│   │   file011.txt
│   │   file012.txt
│   │
│   └───subfolder1
│       │   file111.txt
│       │   file112.txt
│       │   ...
│   
└───folder2
    │   file021.txt
    │   file022.txt
```
Then run with preset settings:
```
"python run_netf.py --config configs/zaragoza_bunny.txt"
```
Different settings are stroaged at "./configs/".
