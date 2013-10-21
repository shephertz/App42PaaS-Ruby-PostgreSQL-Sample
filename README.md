App42PaaS-Ruby-PostgreSQL-Sample
================================

Sample Ruby App with PostgreSQL for App42 PaaS Platform

## Getting Start with App42

1. Setup infrastructure for required environment
2. Create service
3. Deploy a Ruby application

### Setup infrastructure for required environment

    $ app42 setupInfra   
    
### Create service

    $ app42 createService
    
DB Configure for Production environment (application_root_dir/config/database.yml) 

    adapter: postgres
    host: <host>
    port: <port>
    database: <database name> 
    username: <user_name>
    password: '<password>'
    
### Deploy a Ruby application

    $ app42 deploy

#### Get application details:

    $ app42 appInfo --app AppName    
    
Visit your application:

