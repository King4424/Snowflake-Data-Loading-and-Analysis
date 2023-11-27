# 	:dart: Snowflake Data Loading & Analysis
### Load Organisation's Report Dataset into Snowflake through Snowflake Dashbord
### The basic steps to load local data into snowflake:

1) Check the input source type of your Dataset.

2) Create & Run target table SQL Command.

3) Select database, schema and table

4) Load data into table

**After we have the source input, let us check the data first:**
<img width="960" alt="image" src="https://github.com/King4424/Snowflake-Data-Load/assets/121480992/b43efacb-c503-4e7c-8141-23e2a8f4e812">

:diamond_shape_with_a_dot_inside: We should notice that there is a redundant header in the first line we will not use it. Also, the data format needs to be processed carefully, as there is no second suffix. The comma in a inner sentence should be isolated, it is not a delimiter anymore. All these works need to be done before we load data to table of database.

:diamond_shape_with_a_dot_inside: The next step is to create the target table to Snowflake. We need to choose which one database and schema we want to upload. The constraints can be roughly used:

<img width="960" alt="image" src="https://github.com/King4424/Snowflake-Data-Load/assets/121480992/69722f2b-2b0b-4385-9442-ca68b82b36c9">
We can see the Empty Table has been created on your selected Database and schema


:diamond_shape_with_a_dot_inside: Now we have to Load Data Into the Table :
<img width="940" alt="image" src="https://github.com/King4424/Snowflake-Data-Load/assets/121480992/70d0dcf6-9116-44b9-bd51-47b067a159f5">

:diamond_shape_with_a_dot_inside: Browse your dataset file :
<img width="960" alt="image" src="https://github.com/King4424/Snowflake-Data-Load/assets/121480992/093b2809-40fd-4d3d-91c1-902430645fd7">

:diamond_shape_with_a_dot_inside: After selecting your file click on next:
<img width="951" alt="image" src="https://github.com/King4424/Snowflake-Data-Load/assets/121480992/5e9c375b-20c6-4c96-9e65-11f31d34c8d5">

:diamond_shape_with_a_dot_inside: Select your File Formate, Header, Field optionally enclosed by, and other :
<img width="946" alt="image" src="https://github.com/King4424/Snowflake-Data-Load/assets/121480992/1875df55-1eea-4f5b-b989-2665c34a40e5">

:diamond_shape_with_a_dot_inside: See Data Preview:
<img width="960" alt="image" src="https://github.com/King4424/Snowflake-Data-Load/assets/121480992/7ead5c31-8be8-4218-9403-1dd53f188e91">

:diamond_shape_with_a_dot_inside: We can also use sql queries to check data using < Select * from > :
<img width="960" alt="image" src="https://github.com/King4424/Snowflake-Data-Load/assets/121480992/d449db22-8b0d-4ba5-aaa4-b32969b95880">


:white_check_mark: That's All. We managed to load the data from the local to Snowflake.

:bar_chart: We can also do Analysis of our Data using snowflake charts and filters:
<img width="960" alt="image" src="https://github.com/King4424/Snowflake-Data-Load/assets/121480992/48d2611f-4d6f-41bd-a28a-e9966f0dd6ef">


<img width="960" alt="image" src="https://github.com/King4424/Snowflake-Data-Load/assets/121480992/84d80ae9-308b-46a6-9985-3f13780e939b">








