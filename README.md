# Crashing into The Rails

- create new project (API only)

```bash
rails new test-article --api
```

- Install packages @ Gemfile

```bash
bundle install
gem install <package_name>
```

- Start server

```bash
rails server
```

- generate model

```bash
rails generate model Article title: string body: text
```

- generate controller

```bash
rails generate controller api/v1/articles
```

- db migration

```bash
rails db:migrate
```

- [Seeding](./db/seeds.rb) db with faker

```bash
rails db:seed
```

- list routes

```bash
rails routes
```

### Issues

mysql2 installation @ windows 10 - ` gem install mysql2 --platform=ruby -- --with-mysql-lib="C:\Program Files\MySQL"`
