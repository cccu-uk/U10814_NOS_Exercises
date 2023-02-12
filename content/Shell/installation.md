# Installation 

## Downloadable resources/data

Click here to download the [shell-lesson-data](./shell-lesson-data.zip) for the exercises throughout understanding the Shell.

## JupyterHub

1. Navigate to [JupyterHub](https://jupyterhub.canterbury.ac.uk/) 
   - an online environment where you can code and explore the Shell.
>>
2. Login to [JupyterHub](https://jupyterhub.canterbury.ac.uk/) using your CCCU user account credentials.
>>
3. Start your server... 
   >>
   ![](./fig/jh-server.png)
>>
4. Once server has started <kbd>Right Click</kbd> File Browser view and create a new folder called `NOS`
>>
5. <kbd>Double Click</kbd> `NOS` and select the upload files icon to upload the `shell-lesson-data.zip`. Alternatively you can drag the `shell-lesson-data.zip` from your host machine to the file browser in jupyter hub to upload it. 
>>
6. Next select from the `Launcher` window the 'Terminal' icon to load a terminal. 
   >>![](.fig/../fig/jh-terminal-launch.png) 
>>
7. Now you can navigate to the correct directory using the following commands, note we will be going over what these mean at a later date. 
   ```bash
   $ cd NOS
   ```
   ```bash
   $ unzip shell-lesson-data.zip && rm shell-lesson-data.zip 
   ```
   You should see something like this on your terminal...

```sh
jovyan@jupyter-seb-20blair:~/NOS$ unzip shell-lesson-data.zip 
Archive:  shell-lesson-data.zip
   creating: shell-lesson-data/
   creating: shell-lesson-data/exercise-data/
   creating: shell-lesson-data/exercise-data/writing/
  inflating: shell-lesson-data/exercise-data/writing/LittleWomen.txt  
  inflating: shell-lesson-data/exercise-data/writing/haiku.txt  
   creating: shell-lesson-data/exercise-data/animal-counts/
  inflating: shell-lesson-data/exercise-data/animal-counts/animals.csv  
   creating: shell-lesson-data/exercise-data/proteins/
  inflating: shell-lesson-data/exercise-data/proteins/ethane.pdb  
  inflating: shell-lesson-data/exercise-data/proteins/propane.pdb  
  inflating: shell-lesson-data/exercise-data/proteins/cubane.pdb  
  inflating: shell-lesson-data/exercise-data/proteins/octane.pdb  
  inflating: shell-lesson-data/exercise-data/proteins/methane.pdb  
  inflating: shell-lesson-data/exercise-data/proteins/pentane.pdb  
   creating: shell-lesson-data/exercise-data/creatures/
  inflating: shell-lesson-data/exercise-data/creatures/basilisk.dat  
  inflating: shell-lesson-data/exercise-data/creatures/unicorn.dat  
  inflating: shell-lesson-data/exercise-data/creatures/minotaur.dat  
 extracting: shell-lesson-data/exercise-data/numbers.txt  
   creating: shell-lesson-data/north-pacific-gyre/
  inflating: shell-lesson-data/north-pacific-gyre/NENE02040A.txt  
  inflating: shell-lesson-data/north-pacific-gyre/NENE01843A.txt  
  inflating: shell-lesson-data/north-pacific-gyre/goostats.sh  
  inflating: shell-lesson-data/north-pacific-gyre/NENE01729A.txt  
  inflating: shell-lesson-data/north-pacific-gyre/NENE02018B.txt  
  inflating: shell-lesson-data/north-pacific-gyre/NENE02043A.txt  
  inflating: shell-lesson-data/north-pacific-gyre/NENE01751A.txt  
  inflating: shell-lesson-data/north-pacific-gyre/NENE02040Z.txt  
  inflating: shell-lesson-data/north-pacific-gyre/NENE01812A.txt  
  inflating: shell-lesson-data/north-pacific-gyre/NENE01971Z.txt  
  inflating: shell-lesson-data/north-pacific-gyre/NENE02043B.txt  
  inflating: shell-lesson-data/north-pacific-gyre/goodiff.sh  
  inflating: shell-lesson-data/north-pacific-gyre/NENE01843B.txt  
  inflating: shell-lesson-data/north-pacific-gyre/NENE01751B.txt  
  inflating: shell-lesson-data/north-pacific-gyre/NENE01978B.txt  
  inflating: shell-lesson-data/north-pacific-gyre/NENE01729B.txt  
  inflating: shell-lesson-data/north-pacific-gyre/NENE01978A.txt  
  inflating: shell-lesson-data/north-pacific-gyre/NENE02040B.txt  
  inflating: shell-lesson-data/north-pacific-gyre/NENE01736A.txt  
```

1. Ok good job, you are ready for lab exercises. 
   
[Back to Contents Page](shell.md)