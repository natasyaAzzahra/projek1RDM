# Program untuk indexing text dan image 

## Indexing Text 
### *Requirements :
1. ```sudo apt-get install libgtk-3-dev```
![](./ss/ss_text/1.png)
2. ```sudo apt install python3-pip```
![](./ss/ss_text/2.png)
3. ```sudo apt-get install build-essential libpoppler-cpp-dev pkg-config python-dev```
![](./ss/ss_text/4.png)

### *Cara menjalankan : 
1. ```cd indexText```
2. ```pip3 install -r requirements.txt```
![](./ss/ss_text/3.png)
3. ```pip3 install pdftotext```
![](./ss/ss_text/5.png)
4. ```pip3 install pgi```
![](./ss/ss_text/6.png)
5. ```python3 main.py```
![](./ss/ss_text/7.png)
6. Output
![](./ss/ss_text/8.png)

## Indexing Image
### *Cara menjalankan : 
1. ```cd indexImage```
2. ```sudo pip3 install -r requirements.txt```
![](./ss/ss_image/1.png)
3. ```cd app```
4. ```python3 index.py --dataset static/images --index index.csv```
![](./ss/ss_image/2.png)
5. Output
![](./ss/ss_image/3.png)


## Sumber :
* Text-Indexing: Swish-e (Package on Ubuntu)
* Image-Indexing: https://github.com/kudeh/image-search-engine.
