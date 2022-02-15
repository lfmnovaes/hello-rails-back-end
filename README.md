![](https://img.shields.io/badge/Microverse-blueviolet)

# Hello Rails Back-End

> Introductory project for Rails only dealing with the Back-End

## Built With

Ruby >= 3.0.0

Rails >= 7.0.0

Postgresql >= 12.9

## Getting Started

- To get a local copy of the repository please run the following commands on your terminal:
   ```
   git clone https://github.com/lfmnovaes/hello-rails-back-end.git
   ```
- Go to the cloned directory with `cd hello-rails-back-end`
- Run `bundle install` to install the necessary packages for rails
- Install the `postgresql` database and all necessary dependencies (if you are on Ubuntu just run `sudo apt install postgresql postgresql-contrib`)
- Run `rails db:create` and `rails db:migrate` to create the database locally
  - If you already have one with the same name just run `rails db:reset` instead
- After installing everything, you can run now the website with `rails s`

<details>
   <summary>Running linters</summary>
   
   - Rubocop (Ruby code linter), run: `rubocop`
   - Stylelint (CSS linter), run: `npm install` and then `npx stylelint "**/*.{css,scss}"`
</details>

## Author

👤 **Luís Fernando**

- GitHub: [![@lfmnovaes](https://img.shields.io/github/followers/lfmnovaes?color=lightgray&style=plastic&labelColor=blue)](https://github.com/lfmnovaes)
- Twitter: [![@lfmnovaes](https://img.shields.io/twitter/follow/lfmnovaes?style=plastic&labelColor=blue)](https://www.twitter.com/lfmnovaes/)
- LinkedIn: [![@lfmnovaes](https://img.shields.io/badge/LinkedIn-blue?style=plastic&logo=linkedin)](https://www.linkedin.com/in/lfmnovaes/)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues/).

## Show your support

Give a ⭐️ if you like this project!

## Acknowledgments

- Microverse

## 📝 License

This project is [MIT](./LICENSE) licensed.
