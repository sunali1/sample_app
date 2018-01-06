## Ruby on Rails Sample Application

## Getting Started
To run this application

Clone the repo and then bundle install the needed gems.
```
 $ bundle install --without production
```
 Next, Migrate the Database
 ```
  $ rails db:migrate
 ```

 Finally, run the test suite to verify everything is working correctly
 ```
  rails test
 ```

 If the test suite passes you are ready to run the app in the local servers
 ```
  rails server
 ```
