# RAILS NOTES

### Some notes on useful commands, sensible set up and domain modelling

## Commands

```rails new PROJECTNAME``` - generates new rails project directory

```rails new PROJECTNAME -d postgresql -T``` - generates new rails project, with postgresql preconfigured as database and default test suite turned off

```rails s``` - starts rails server

```rake db:create``` - sets up database locally

```rake routes``` - shows all existing routes for the rails project

```rails g rspec:install``` - sets up RSpec spec directory with basic files

```rails g model MDLNAME PROPERTY:DATATYPE``` - generates specified model, with any properties/datatypes listed. model will translate to a table in the db, property will translate to a column in the table

```rails g controller MDLNAME``` - generates a controller file for specified model

```rake db:migrate``` - carries all migrations over into the local database
