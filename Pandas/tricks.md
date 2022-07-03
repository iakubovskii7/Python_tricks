https://towardsdatascience.com/pandas-exercise-for-data-scientists-part-2-4d532cfc00bf

# Assign Unique IDs to every Group
df["group_num"] = df.groupby("col_A").grouper.group_info[0] + 1

# Check if a column has NaN values
Check if a column has NaN values

# Append a list as a row to a DataFrame
new_row = ["E", 5]
df.loc[df.shape[0]] = new_row

# Identify the source of each row in Pandas Merge
df = pd.merge(df1, df2, how = "left", indicator = True)

