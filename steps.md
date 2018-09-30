
rake -T   see tasks
rake db:seed
rake db:migrate

Build class < have migration  inherit from from ::Base if ::Base built

rake db:seed
migrate
.tables



# rake db:seed to see pending task or task

  result bellow
# ------------------------------------------
# => have 1 pending migration:
# => 1 CreateMovies
# => Run `rails db:migrate` to update your database then try again.



        **rake db:create_migration NAME=.....**
***to create your migration file. Once you have a migration file add columns for title (string), release_date (integer), director (string), lead (string), and in_theaters (boolean). After your migration is ready run rake db:migrate to migrate your table and rake db:migrate SINATRA_ENV=test to migrate a test database so you will be able to run learn
