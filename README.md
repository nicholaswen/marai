This is a modified implementation of a Reinforcement Learning bot that tries to solve the first level of SuperMario Bros

The original implementation can be found here:
https://medium.com/datadriveninvestor/super-mario-bros-reinforcement-learning-77d6615a805e

# Install virtual environment
```
python3 -m venv marai-env  
source marai-env/bin/activate
```

# Install required packages
```
pip3 install -r requirements.txt
```


# Copy the Super Mario Bros Nes rom to the folder accessible by Gym Retro
```
cp roms/rom.nes marai-env/lib/python3.7/site-packages/retro/data/stable/SuperMarioBros-Nes
```
If this doesn't work then go to your lib folder and find the correct name for the python version folder

# Run the script
```
python3 marioai.py
```
