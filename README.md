# Fun-with-python
This repo contains some cool fun/fact related to python

# print_statement.py

In this python file, I have just tried to understand how a print statement affect the execution time of pipeline. I took two for loops, in 1st for loop, I put one print statement and in 2nd for loop, I did not put any print statement. And we can see the difference. So the conclusion is whenever we are going to put our pipeline/system in production, we must try to put as minimal print statement as possible. (I have realized this when I was doing final testing of one of my computer vision project) 

# swap.py
In python, we can easily swap two (or more) numbers without any temp variable.

# read_vs_resize.py
Sometimes a small fraction of time matters when we are deploying the project/model in production, so we need to keep in mind very small-small factor like either we should read the image in required size or resize the image after reading.

# reverse_list.py
It is very easy to reverse a list in python



# Check the folder size of google drive
Step1: 1st of all open the google colab https://colab.research.google.com/notebooks/intro.ipynb#recent=true and then create a new notebook <br>
Step2: Now mount your drive <br>
Step3: Run the command in a cell ```!du -sh /content/drive/My\ Drive/Label```

