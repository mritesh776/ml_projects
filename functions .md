1. def columns_in_a_dataframe(dataframe):

    number_of_columns = len(dataframe.columns)
    print(f"Number of columns: {number_of_columns}\n")

    for index, column in enumerate(df.columns):
        if index == 0:
            print(f"[{column}", end=", ")
        elif index == number_of_columns - 1:
            print(f"{column}]")
        else:
            print(column, end=", ")

columns_in_a_dataframe(dataframe)

2. 