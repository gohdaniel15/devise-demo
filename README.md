# Devise Demo App

This application is used for the purposes of practicing using Devise gem in
Rails.

# Setup

1. Clone the application
```
git clone https://github.com/gohdaniel15/devise-demo.git
cd devise-demo
```

2. Install gems
```
bundle
```

3. Set up the database
```
rake db:create db:migrate db:seed
```

This will give you a user with the following attributes to log in

full_name: "User"
email: "user@example.com"
password: "123123123"
