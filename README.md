# AWS Lambda Skillset Assessment

1. Create a new trial AWS account, or use an existing one.
2. Implement an API usign AWS Lambda with endpoints capable to provide the following functionality
   * GET /movies: returns a collection of movies using the following parameters
      * page: page index number starting from 0
      * size: number of results per page max 100
      * director: filter movies by director
      * genre: filter movies by genre
   * GET /actor_stats/{actor_id}: consider & implement possible approaches to optimizing this endpoint performance. 
     Should return the following data schema:
      * id
      * name
      * top_genre
      * number_of_movies
      * number_of_movies_by_genre: dictionary, key: genre_name, value: number
      * most_frequent_partner: find actor that acts in the same movies most frequently
         * partner_actor_id
         * partner_actor_name
         * number_of_shared_movies
 
 ![image](https://user-images.githubusercontent.com/101377478/180582363-7cac887a-8015-4cec-b215-ebf6d939b02e.png)

## Installation

Use the package manager npm to install a package.

```bash
npm install
```

## Usage

* Create a new trial AWS account
* Create a new AWS lambda account
* Zipped the folder and upload to AWS lambda.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## Note
There is required MySQL database.
So, Before that, have to execute Node JS Skill set Assessment
