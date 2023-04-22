# CLIP Reward

## Reference:
1. <https://github.com/cedro3/CLIP-Caption-Reward>

## Setting Up Environment
The Python environment is python==3.7.16
```
$ conda create -n clip4caption python==3.7.16
$ conda activate clip4caption
```
```
$ git clone https://github.com/tomo-cps/clip_reward.git
```
```
$ pip install -r requirements.txt
```

## Convert image to caption
```                                                   
$ python main.py
```

## Example
- input image [/images/02.jpg]
![02.jpg](/images/02.jpg) 

- output caption
```
['a couple of people standing together with a pizza in a restaurant']
```