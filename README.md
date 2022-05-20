# What is `aws-mocks` 

Sometimes you want to run unit tests that require credentials to AWS, you may not have those off hand, or may just want to run without AWS. This allows you to run mock AWS credentials for key AWS functionalities. 

## Usage 

Once you setup your `.travis.yml` file, you sohuld start seeing AWS being called: 


<img width="1233" alt="Screen Shot 2022-05-19 at 8 34 05 PM" src="https://user-images.githubusercontent.com/20936398/169445359-15d16ec3-9a74-42ec-a171-edebbc7ad57b.png">

This means the mocks are working. 
