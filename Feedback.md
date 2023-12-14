## Feedback 

Nice work on this project, you can consider it complete. 

I'm also not sure why you ran into so many issues with the data types. I know that most students who used pandas defined every column type for their data frames and defined a specific schema for big query. I'm pretty sure that your solution lets pandas define the scheme and this is how you can get mismatches between different tables. With the strategy where you fully specify all the data types, you run into issues with conversion, where pandas has a hard time putting a certain column in the data type you ask for.

Thanks for the feedback about having more hands-on work with different tools. I'll see how I can get that in next year. Problem this year is that I did so many things and exercises and I'm not sure that very many people took those seriously.
