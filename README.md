# 📚 ChatRoom - Ruby On Rails 7 

Welcome to **ChatRoom**! This guide will help you get started with setting up and running the application on your local machine. 🚀

## Prerequisites 📋

Before you begin, ensure you have the following installed on your machine:

- **Ruby** (version 3.3.2 or newer)
- **Rails** (version 7.2.0.beta2 or newer)
- **Bundler** (a dependency manager for Ruby)
- **Node.js** and **Yarn** (for managing JavaScript dependencies)

## Getting Started 🛠

Follow these steps to get the application up and running:

### 1. Clone the Repository 📦

First, clone the repository to your local machine using git:

```
git clone https://github.com/Muhthoriqas/ChatApp-RubyOnRails
cd ChatApp-RubyOnRails
```
## Install Dependencies 📥

Install the necessary Ruby gems and JavaScript packages:

```
bundle install 
yarn install
```

# Set Up the Database 🗄

Set up the database by running the following commands:

```
rails db:create
rails db:migrate
rails db:seed
```

# Start the Rails Server 🌐
Launch the Rails server to run the application locally:

```
rails server
```

You can now access the application by navigating to http://localhost:3000 in your web browser. 🎉

# Additional Commands 💻

Here are some additional commands you might find useful:

- Run Tests: rails test
- Open Rails Console: rails console
- Generate New Resource: rails generate <resource_name>

# Troubleshooting 🛠

If you encounter any issues, here are some common solutions:

- Postgres Issue : Check [here](https://www.digitalocean.com/community/tutorials/how-to-use-postgresql-with-your-ruby-on-rails-application-on-ubuntu-20-04)
- Bundler Issues: Ensure you have the correct version of Bundler installed. You can update Bundler with gem install bundler.
- Server Issues: Check for any error messages in the terminal and ensure all dependencies are installed.

# Contributing 🤝
We welcome contributions! Please fork the repository and create a pull request with your changes. Make sure to follow the code style and include tests for any new features or bug fixes.


