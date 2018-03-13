## Virtual Dealership Manager
Ruby on Rails application built with Postgres database that mimics car dealership assets management. Users can sign up as employees or managers. This application implements security measures for authentication and authorization. As a manager user has the ability to generate reports, modify employees' permission levels and create and delete dealerships.

##Features and Technologies used
- Ruby on Rails
- Bootstrap used for styling
- Custom built authentication system
- Custom build autherization system
- OmniAuth Github strategy (Login with GitHub)
- Full CRUD support (Create, Retrieve, Update, Delete) with complex inner joins relationships
- PostgreSQL database

## Usage
This application has been deployed to Heroku. You can find the live version on http://virtual-dealership.herokuapp.com. You do not have to signup, you can use the 'Login as guest' option.

After you have cloned the repository run "bundle install" and then run rake db:migrate.

## Development
After cloning the repository run 'bundle install'. Run 'rake db:migrate' to set up the database schema. The application is set up to run the seed file to populate the database if it detects that the database is empty. 

## Contributing
Bug reports and pull requests are welcome on GitHub at https://github.com/'omikolaj'/virtual-dealership-manager. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## License
This project is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT)