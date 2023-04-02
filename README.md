# Advanced ANPR and FRS
Kavach'23 - Team: 404_Found
P.S. Code : KVH-005 

Phase 1 : Testing normal plate recogintion

- Successfully tested normal character recognition using ``python scripts`` and ``OpenCV`` 

![image](https://user-images.githubusercontent.com/115401171/229342728-6096a82a-a2cf-498d-913c-76fcef446545.png)

## Is that all ?
- Nope it all starts here 
1. we have also prepared the ground work for ``Easy OCR`` and ``TensorFlow Object Detection``
2. We are done setting up ``Virtual env/Kernel`` for our ANPR system (so while integrating ``Face Recognition System`` there won't be any problem about over-writing of libraries)

### Steps in creating Virtual environment
Step - 1 : 
``
python -m venv anprsys
``

Step - 2 : Activate your virtual environment <br>
``
source tfod/bin/activate # Linux
``
<br>
``
.\arpysns\Scripts\activate # Windows 
``

Step - 3 : Install dependencies and add virtual environment to the Python Kernel <br>
``
python -m pip install --upgrade pip
`` <br>
``
pip install ipykernel
`` <br>
``
python -m ipykernel install --user --name=anprsys
``


![image](https://user-images.githubusercontent.com/115401171/229343052-9d0fdfe9-69c0-421c-bd21-3e8211af6de6.png)

3. We are also in middle of completion of integrating ``TensorFlow API`` for out project
![image](https://user-images.githubusercontent.com/115401171/229343093-2c7de05b-72e2-4979-b093-950ccf872dd1.png)

4. To train model we will be using ``Transfer learning`` method in initial phase

### Upcoming Plan
!. Initially we will be using ``kaggel dataset``  and manually divided 
the collected images into two folders 
train and test so that all the images 
and annotations will be split among 
these two folders.

2. We will be using ``pre-trained state-of-the-art model`` 
and just fine tuned it on our <b>particular 
specific use case</b>. 
We will begin the training 
process by opening Real Time Number 
Plate Detection and installed the Tensoflow 
Object Detection (TFOD) + API

### Tech Stach :
1. Opencv
2. Easy OCR
3. Tensorflow
4. Jupyter Notebook/Jupyter Lab
5. Python Libraries
(more can be used depending upon the implementation*)

### Mentor : Ms Vernika Singh

### Team Members : 
1. Surya Pratap Singh Chauhan
2. Ujjawal Tyagi
3. Yash Vardhan Singh
4. Shravya Vashishtha
5. Suryansh Kapil
6. Shreya Srivastava
