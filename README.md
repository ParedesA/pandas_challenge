# pandas_challenge

I received help from classmates to debug the following step(to revert the string to floats):

convert_budget = per_school_summary["Per Student Budget"].str.replace("$","").astype(float)
school_spending_df["Spending Ranges (Per Student)"] = pd.cut(convert_budget,spending_bins,labels = labels, include_lowest=True)
school_spending_df
