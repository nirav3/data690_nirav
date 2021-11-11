## Filtering Dataframe
* df.loc[] - label based indexing. 
* df.iloc[] -  position based indexing. 
* df.ix[] - old way. 
* df.loc[ (df['Year'] == 1967) & (df['pop'] > 1000000), ['year']['pop'] ]

## Condensing Dataframe
* pd.melt() - this converts wide dataframe to long dataframe. similar to pivot() 

## Interesting things
* 1_000_000 is same as 1000000

## Cleaning Dataframe
* df.drop_duplicates()

## Merging Dataframes
* df.merge()
