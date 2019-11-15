# Community Art Project

**Community art** is a social media like community for artists and painters.

### Installation on local machine

#### 1) Requirements
  - Ruby version: 2.6.5
  - Rails version: 6.0.1
  - Node.js >= 10.x
  - Yarn
  - Postgresql

#### 2) Install gems
  - Run  ```bundle install && yarn```

#### 3) Create and migrate DB
  - Run ```bundle exec rails db:create db:migrate```

#### 4) Install Foreman gem
  - Run ```gem install foreman```

#### 5) Run Locally
  - Run ```foreman start -f Procfile.dev```



### TODO: Run with Docker