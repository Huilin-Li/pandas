# pandas_
1. ```Series/df.diff()``` => [1,5,3,9] --> [NaN, 4, -2, 6]
2. 
```
import py7zr 
with py7zr.SevenZipFile('folder.7z', mode='r') as z:
     z.extractall()
```
3. rename column
```
pandas rename .set_axis(['new_name'], axis=1) inplace
```
5.  pd.concat([df_Ch2X_P2P, df_Ch2Y_P2P], axis=1)
6.  df.set_index
7.  df.reset_index
8.  df to series = .squeeze
9.  ```series.empty``` ```DataFrame.empty``` => ```True```
10.  dictionary to DataFrame to csv
```
pd.DataFrame(dict).to_csv("name.csv")
```
11.
```
df.loc[(df[‘Color’] == ‘Green’) & (df[‘Shape’] == ‘Rectangle’)]
```
12.
```
df.keys()
```
13.
```
df = df.drop(index=['first', 'second', 'third'])
```
14.
```
format()
```
