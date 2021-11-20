<h1 align="center">Project - Cloud Mind App with Tags System</h1>

<p align="center">
  <img alt="Github top language" src="https://img.shields.io/github/languages/top/educooper/cloud-tags-app-dio?color=green"> 
  <img alt="Github language count" src="https://img.shields.io/github/languages/count/educooper/cloud-tags-app-dio?color=56BEB8">
 <img alt="Repository size" src="https://img.shields.io/github/repo-size/educooper/cloud-tags-app-dio?color=56BEB8">

<hr>

<p align="center">
  <a href="#dart-about">About</a> &#xa0; | &#xa0; 
  <!-- <a href="#sparkles-features">Features</a> &#xa0; | &#xa0; -->
  <a href="#rocket-technologies">Technologies</a> &#xa0; | &#xa0;
  <a href="#white_check_mark-requirements">Requirements</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-starting">Starting</a> &#xa0; | &#xa0;
  <!-- <a href="#memo-license">License</a> &#xa0; | &#xa0; -->
  <a href="https://github.com/educooper" target="_blank">Author</a>
</p>


<br>

## :dart: About ##

In this project we create a cloud mind app with tags and complete user and content management system whith content's association and CRUD. 

## :rocket: Technologies ##

- [GEM Devise](https://github.com/heartcombo/devise)
- [GEM Select2](https://github.com/select2/select2)

## :white_check_mark: Requirements ##

Before Starting :checkered_flag:, you need to install [Git](https://git-scm.com) and [Ruby](https://www.ruby-lang.org/en/).

## :checkered_flag: Get Starting ##

```ruby
# Clone this project
$ git clone https://github.com/educooper/cloud-tags-app-dio

# Access
$ cd cloud-tags-apps-dio

#Install commands

#create a new ruby project with postgreesql
rails new cloud-tags-app-dio -d postgreesql -T 

#Edit the GEMFILE and add DEVISE - a complete solution for user authentications
gem 'devise'
bundle install
rails generate devise install

#Starting database
rails db:setup
rails db:migrate

# Run the project
$ rails server

Access it on [http://localhost:3000](http://localhost:3000)
```

Thanks very munch to the great dev [Bruno Oliveira](https://github.com/brunoao86) and [Digital Innovation One](https://web.digitalinnovation.one/) for this great opportunity!

<a href="#top">Back to the Top</a>
