## Description

Using `put` to update **specific** properties on an object. If you do not configure `put` in this manner it will override the entire record. Which may or may not be something you desire. `put_global_db` uses a global `db` variable to store the `db` so we do not have to open a request every time we want to conduct a transaction. 


## Before
![f](https://imgur.com/mFbE40U.png)

## After
![f](https://imgur.com/WdXtZFW.png)


## Notice uses `destructuring assignment` aka `binding pattern` as shown below
![f](https://imgur.com/6CvdYnz.png)
