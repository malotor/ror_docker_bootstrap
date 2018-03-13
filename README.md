# Ruby on Rails Docker skeleton project

## Create project

    $ docker-compose run web rails new .
  
## Initialize project

    $ docker-compose up -d web
    $ docker-composer exec web rails db:migrate
