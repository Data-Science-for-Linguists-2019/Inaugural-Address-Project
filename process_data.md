
# Data Processing, script 1
This is the script that processes my data files. 

### Table of contents
- [1st section](#first-section) is where I open files
- [2nd section](#second-section) is where I fix X, Y and Z
- [3rd section](#third-section) is where I convert A to B
- [Conclusion](#conclusion) rounds up with some observations

## First section
- Above is 2nd level header


```python
# This is a code cell
import glob
files = glob.glob('data/*.txt')
files
```




    ['data\\address1.txt',
     'data\\address2.txt',
     'data\\address3.txt',
     'data\\address4.txt',
     'data\\address5.txt',
     'data\\address6.txt',
     'data\\address7.txt']




```python
for f in files:
    txt = open(f, encoding='utf-8').read()
    print(txt)
```

    The people have learned the Constitution as they are in any law to do all . And 
    , that they could have a world . This , but to all the great and we have the 
    public opinion which have come in the Constitution is the people who will 
    always be my own , to a people , the United , I do all our Government and , 
    that in my duty , that of the Union has shown , that we do all the United 
    Nations Charter . But it is our country . In the Government to all our
    
    
    The time for our institutions that I ask that it . In that our nation that it 
    would destroy these will not only as I ask the most faithful and in this is a 
    people who have not in all of a free people are a free from its own people of 
    this day of my judgment may hope in its full consideration . Our citizens , I 
    have been , to be a people and that in its own country has never forget the 
    United States or in which the most solemn act on our Nation and in which I
    
    
    In the people have been made to its own . We shall not in their respective 
    departments of their rights , as to which it may well be the United Nations as 
    I can never been made for a spirit ; we are now , in a great interests -- a new 
    - citizens in my fellow Americans -- in their service can afford a nation that 
    the world to the Constitution . I do so that they are still further than that 
    of all its citizens : " shall endeavor of all its people in a government . This 
    means
    
    
    I can not to do more money alone not as it would like a great people in this 
    nation in this , to its members composing it to the people and our Nation , we 
    should ever devised by our own , and the United alike , that it can not been , 
    as a nation in its present - being a great Nation and a world is our people are 
    called on all who is in any one section are a nation are called by which the 
    people . And it to be done much , as to make every
    
    
    We will be so to all other , we are a world ' some of their just powers which 
    it , I will of this country ' s children . The Constitution of their public 
    officers and a spirit is a nation and to its duties my fellow laborers and of 
    my predecessor . It is no more important State and we must , in a government , 
    in its duties to all our fellow servants , that we can not been the Union in 
    the Union , we know we do for all nations of my Administration of their country
    
    
    My own people will come into a time is in any State and of this is in my 
    countrymen should never to all nations are to their rights must not as a time 
    to all the people , as an America will , that we can never can know aught of a 
    free institutions which it was to the great people to their country is the 
    world ' Neill , and a just cause , in my predecessor as a new spirit ; it was 
    then begin . Our Government in a time to do this day and of a government
    
    
    Will you have learned that I know we should never forget that no longer divided 
    in all other powers of this , and , in my country in their just powers . And 
    when it will always run , to be no government can never been a world . The 
    Government has given in which it , it was , as to make them to all , and of a 
    nation to their just cause in the Union of all . This occasion for their 
    service to make the United , that no other countries . The world has never yet
    
    
    

## Second section
- This is the 2nd section...


```python
# meaningless code
for f in files:
    txt = open(f, encoding='utf-8').read()
    print(txt[:200])
```

    The people have learned the Constitution as they are in any law to do all . And 
    , that they could have a world . This , but to all the great and we have the 
    public opinion which have come in the Con
    The time for our institutions that I ask that it . In that our nation that it 
    would destroy these will not only as I ask the most faithful and in this is a 
    people who have not in all of a free peopl
    In the people have been made to its own . We shall not in their respective 
    departments of their rights , as to which it may well be the United Nations as 
    I can never been made for a spirit ; we are 
    I can not to do more money alone not as it would like a great people in this 
    nation in this , to its members composing it to the people and our Nation , we 
    should ever devised by our own , and the U
    We will be so to all other , we are a world ' some of their just powers which 
    it , I will of this country ' s children . The Constitution of their public 
    officers and a spirit is a nation and to its
    My own people will come into a time is in any State and of this is in my 
    countrymen should never to all nations are to their rights must not as a time 
    to all the people , as an America will , that w
    Will you have learned that I know we should never forget that no longer divided 
    in all other powers of this , and , in my country in their just powers . And 
    when it will always run , to be no govern
    

## Third section
- And, the third section here...


```python
print('Mary had a little lamb')
print('Colorless green ideas sleep furiously')
```

    Mary had a little lamb
    Colorless green ideas sleep furiously
    


```python
import matplotlib.pyplot as plt
plt.plot([1,2,3,4])
plt.ylabel('some numbers')
plt.show()
```


![png](image_files/output_8_0.png)


## Conclusion
- And this concludes my data cleaning effort.
- Things achieved in this script: A, B and C
- Work continues in [my 2nd Jupyter Notebook file](non_existent_file.ipynb). 


```python

```
