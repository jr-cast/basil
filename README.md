# Basil: Budget App

> Basil is a mobile web application where you can manage your budget: you have a list of transactions associated with a category, so that you can see how much money you spent and on what.

## Getting Started

This repository includes files with Ruby that can be used to test the created main classes from the app

Clone this link into your local device.

To run test make sure that rspec-rails and capybara libraries are installed in your project

To double check please run:
```
bundle install
```
This will install both gems if they were missing in your environment.

Run the server:
```
rails s
```

Open localhost:3000 port in your computer and go to /users to check all users
```
localhost:3000/users
```

Open localhost:3000 port in your computer and go to /users to check posts of a single user
```
localhost:3000/users/1
```

Open localhost:3000 port in your computer and go to /users to check posts, comments and likes of a user in greater detail
```
localhost:3000/users/1/posts
```

Open localhost:3000 port in your computer and go to /users to check an specific post
```
localhost:3000/users/1/posts/1
```

## Running tests

To run all tests including, user and post controllers (both features and request) please run rspec in the main project folder:
```
rspec
```

To run test for a specific test run rspec and add the location of the file:
```
rspec ./spec/requests/posts_spec.rb
```

## Authors

👤 **Jose**

- GitHub: [@jr-cast](https://github.com/jr-cast)
- Twitter: [@josercastanos](https://twitter.com/josercastanos)
- LinkedIn: [@jr-cast](https://linkedin.com/in/jr-cast)


## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

## Show your support

Give a ⭐️ if you like this project!

## Acknowledgments

- Hat tip to anyone whose code was used
- Inspiration
- etc

## 📝 License

This project is [MIT](./MIT.md) licensed.
