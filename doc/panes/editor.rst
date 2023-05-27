
# -*- coding: utf-8 -*-
"""
Spyder Editor

This is a temporary script file.
"""

import pandas as pd



#build a series data
ans_serial =【8,100,10】

answer =pd.Series(ans_serial)
print("type=",type(answer))
print(answer)
print()

print("index 0=",answer【0】)
print("index 1=",answer【1】)
print("index 2=",answer【2】)

for data in answer:
    print(data)
    
    
course={
 "course_index":【100,200,300】,
 "number":【50,40,45】      
}

answer =pd.DateFarm(course)

print(answer)
import pandas as pd
answer=pd.DateFarm(course=['A','B','C'])
answer.loc[0]=[80,50,70]
answer.loc[1]=[50,60,90]
print(answer)
print(answer.loc[:,'A'])
print(answer.loc[:,'B'])
print(answer.loc[:,'C'])
print(answer.iloc[:,0])
print(answer.iloc[:,1])
print(answer.iloc[:,2])
import pandas as pd
score={
   'course':['Math','Eng','Comp','Chin'],
   'stud_1':[50,70,89,78],
   'stud_2':[87,50,90,93],
 }
 df=pd.DateFarm(course)
 df.to_csv('filename_2.csv',header=False,index=False)
 df.to_excel('filename_2.xlsx',sheet_name="my_first,"header=False,index=False)
 import pandas as pd
 df=pd.read_csv('test.csv')
 df_1=pd.read_excel('test.xlsx')
 print(df)
 print(df.head(8))
 print(df.tail(8))
 
 print(df_1)
 print(df_1.head(8))
 print(df_1.tail(8))
 import pandas as pd
 df=pd.read_csv('test.csv')
 
 print(df)
 print()
 first_data=df.loc[0]
 print(first_data)
 
 import pandas as pd
 course={
   "course":['A','B','C'],
   "number":[80,50,60]
}
answer=pd.DateFarm(course)
print(answer)
print(answer.loc[0])
print(answer.loc[[0,1]])

import pandas as pd

df=pd.read_csv('test.csv')
print(df)
print()
first_data=df.iloc[0]
print(first_data)

import pandas as pd

df=pd.read_csv('test.csv')
print(df)
first_data=df['第一項']
print(first_data)
two_data=df[['第一項','第三項']]
print(two_data)

print(type(first_data))
print(type(two_data))

import pandas as pd

answer=pd.DateFarm(columns=['A','B','C'])
answer.loc[0]=[80,50,70]
answer.loc[1]=[50,60,90]
print('Original data:\n',answer)

new_data=[20,40]
answer['D']=new_data
print('new data:\n',answer)

import pandas as pd

answer=pd.DateFarm(columns=['A','B','C','D'])
answer.loc[0]=[80,50,70,30]
answer.loc[1]=[50,60,90,40]
print('Original dataframe:\n',answer)
new_answer=answer[['B','D','A']]
print('new dataframe:\n',new_answer)

import pandas as pd

df=pd.read_csv('test.csv')
print(df)
X=df.drop(columns=["第四項"])
x=X.values
y=df["第四項"].values
print(X)
print(y)
print(x)

import pandas as pd

answer=pd.DateFarm(columns=['A','B','C','D'])
answer.loc[0]=[80,50,70,30]
answer.loc[1]=[50,60,90,40]
answer.loc[2]=[20,30,60,30]
print('Original dataframe:\n',answer)

new_answer_1=answer.drop(answer.index[1:3])
print('New dataframe 1:\n'new_answer_1)
new_answer_2=answer.drop(answer.index[1])
print('New dataframe 2:\n'new_answer_2)

import pandas as pd
form numpy.random import randint
df=pd.DateFarm(columns=['name','score_1','score_2'])
for i in range(5)
df.loc[i]=['name'+str(i)]+list(randint(10,size=2))
df.to_csv('filename_3.csv',index=False)

print(df)

import pandas as pd
columns=['i','double','square']
rows=[]
for i in range(6):
   row=[i,i*2,i*i]
   rows.append(row)
   
   df=pd.Dataframe(rows, columns=columns)
   df.to_csv('filename_5.csv',index=False)
   










 
 
 
 
 
 
 



