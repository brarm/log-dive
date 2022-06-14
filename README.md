# log-dive
Python-based COBB AccessPort Datalog Dive Tool

## Purpose
Write a tool to help AccessPort users better understand their driving habits.

## How to use
### Requirements:
- [Anaconda](https://anaconda.org/anaconda/python)
- AccessPort Logging Parameters (minimally):
  - Gear Position
  - Clutch Sw
  - Vehicle Speed
  - RPM
  - Accel Position
  - SI Drive Mode (optional, but helps)
  
### Use
- Install Anaconda, then

In log-dive directory, run
`conda create --name log-dive --file requirements.txt`

- Open Jupyter Notebook with
```
conda activate log-dive
jupyter notebook
```
 
 ## UX
 

https://user-images.githubusercontent.com/7589967/173479706-0c2da1de-e710-41b8-8560-57149bb34e9b.mov

 
 The app maintains a simple UX for now, to be refined with time and use.
 For now, running the chunks of the notebook is the best way to interact with the program.

 
 
 
