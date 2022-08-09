#### MISC_CODE

#### Below are quick examples 
#### Replace all Nan values to empty string
df2 = df.replace(np.nan, '', regex=True)
print(df2)

#### Using multiple columns 
df2 = df[['Courses','Fee' ]] = df[['Courses','Fee' ]].fillna('')
print(df2)

#### Using pandas.DataFrame.fillna() to replace nan values 
df2 = df.fillna("")
print(df2)

#### Using pandas replace nan with null 
df2 = df.fillna('', inplace=True)
print(df2)

#### Pandas single column using replace nan empty string 
df2 = df.Courses.fillna('')
print(df2)

#### Using Courses column replace nan with Zeros
df2 = df['Courses']=df['Courses'].fillna(0)
print(df2)

#### Using Discount column to replace nan with Zeros
df2 = df['Discount']=df['Discount'].fillna(0)
print(df2)

#### Remove the nan and fill the empty string
df2 = df.Courses.replace(np.nan,'',regex = True)
print(df2)

#### Remove the nan and fill some values
df2 = df.Courses.replace(np.nan,'value',regex = True)
print(df2)
