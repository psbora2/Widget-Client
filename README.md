# Widget Client App

WidgetClient is a simple application, consuming the [WidgetApi](https://showoff-rails-react-production.herokuapp.com), built with Ruby on Rails.

![enter image description here](https://onlinepaytax.s3.ap-south-1.amazonaws.com/login_logout.gif)

## Functionality

#### Guest Users Can
- Browse Widgets
- Search Widgets 
#### Signed In Users Can
- Browse Widgets
- Search Widgets
- Visit other user's profile
- Create/Edit/Delete own widgets

## Setting up the application
- Clone the repository
- Execute `bundle install` to install required gems.
- Edit the `config/api.yml` and update it with the URL of the Widget - - API. By default, the applications will use [https://showoff-rails-react-production.herokuapp.com](https://showoff-rails-react-production.herokuapp.com)
- Execute `rails server` to start the application on the default port.
- Navigate to [the application's home page](http://localhost:3000) and there you are.

## Behind the scenes
- **Bootstrap**: Responsiveness & styling
- **RestClient**: Talk with the API
- **FontAwesome**: Font icons used in some links

## Images
#### Search
![Search Functionality](https://onlinepaytax.s3.ap-south-1.amazonaws.com/search.gif)
