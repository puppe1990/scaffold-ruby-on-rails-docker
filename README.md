Scafold with Docker to create a project in Ruby On Rails

To use:
1. sudo docker-compose run web rails new . --force --database=postgresql
2. sudo chown -R $USER:$USER .
3. sudo docker-compose build
4. change your database.yml to https://gist.github.com/puppe1990/aeebc4e4946f0680a99425dd943e90fe
5. sudo docker-compose up
6. sudo docker-compose run web rake db:create
