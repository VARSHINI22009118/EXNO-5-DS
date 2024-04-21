# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

# Aim:
  To Perform Data Visualization using matplot python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:
### Line
 ```python
marks=[13,45,63,78]
student=['ABC','QOR','EFB','TOB']
plt.plot(marks,student)
plt.xlabel('Marks')
plt.ylabel('Student name')
plt.show()

student=['A','B','C','D']
attendence=[90,85,73,88]
plt.plot(attendence,student)
plt.xlabel('Attendence')
plt.ylabel('Student name')
plt.show()

```

![image](https://github.com/VARSHINI22009118/EXNO-5-DS/assets/119401150/0e16a7b1-b213-4746-beec-5a413e7076f9)

![image](https://github.com/VARSHINI22009118/EXNO-5-DS/assets/119401150/7f36c8a7-7824-41e6-a9cf-5b7a9283c6db)


### Bar graph
```python
x=[10,20,30,40,50]
names=['A','B','C','D','E']
plt.bar(x,y,color='blue')
plt.show()

x=[14,30,25,6,20]
names=['A','B','C','D','E']
plt.bar(x,y,color='blue')
plt.show()
```

![image](https://github.com/VARSHINI22009118/EXNO-5-DS/assets/119401150/d975e561-6d4b-44fb-a60e-a074dc9c24a1)

![image](https://github.com/VARSHINI22009118/EXNO-5-DS/assets/119401150/eeadbf38-6f7f-422f-9f5f-551984f9ccea)


### Scatterplot
```python
x=[10,20,30,40,50]
y=[100,200,300,400,500]
plt.scatter(x,y,label='stars',color='green',marker='*',s=30)
plt.show()

x=np.arange(0,15)
y=np.arange(0,15)
x
y
plt.scatter(x,y,c='r')
plt.xlabel('X axis')
plt.ylabel('y axis')
plt.title('Scatter plot')
plt.show()
```
![image](https://github.com/VARSHINI22009118/EXNO-5-DS/assets/119401150/6cd440e2-1f37-4c5d-a8da-7d6106bec699)

![image](https://github.com/VARSHINI22009118/EXNO-5-DS/assets/119401150/1b757ae2-055f-413c-9756-25e1938da6a3)


### Histogram
```python
ages=[2,5,70,40,30,45,50,45,43,40]
range=(0,80)
bin=10
plt.hist(ages,bin,range,color='green',histtype='bar',rwidht=0.8)
plt.xlabel('ages')
plt.ylabel('No of people')
plt.legend()
plt.title('Histogram')
plt.show()

x=[2,1,6,4,2,4,8,9,4,2,10]
plt.hist(x,bins=10,color='blue',alpha=0.5)
plt.show()
```

![image](https://github.com/VARSHINI22009118/EXNO-5-DS/assets/119401150/6f6629d7-9393-421d-a935-5f71e85daf7e)

![image](https://github.com/VARSHINI22009118/EXNO-5-DS/assets/119401150/08cefc2c-a1bb-4f9c-8918-e244b175c111)



### Pie chart
```python
act=['eat','sleep','work','play']
slices=[3,7,8,6]
color=['r','y','g','b']
plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()

feedback=['Good','excellent','Perfect','Ok']
slices=[4,10,3,8]
color=['y','r','b','g']
plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()
```

![image](https://github.com/VARSHINI22009118/EXNO-5-DS/assets/119401150/b66938e7-e6a1-46d1-a0b8-b5087d230088)

![image](https://github.com/VARSHINI22009118/EXNO-5-DS/assets/119401150/3e5f1d45-85df-42e7-8e13-eca6931d963b)



# Result:
Thus, all the data visualization techniques of matplotlib has been implemented.
