## Devise & Active Directory integration

Source: https://medium.com/@takatoyo/step-by-step-implement-active-directory-auth-with-devise-33590bd3e3f1

Configured with sample public LDAP: https://www.zflexldapadministrator.com/index.php/blog/82-free-online-ldap

## Development setup

It's based on https://evilmartians.com/chronicles/ruby-on-whales-docker-for-ruby-rails-development
You need only docker to develop the application.
All the shell commands pls run inside `docker-compose run --rm runner` or `dip bash`

To improve docker interaction on development we recommend to use [dip](https://github.com/bibendi/dip#dip)


```
provision
compose up web
```

Same can be achieved using docker-compose:

```
docker-compose run --rm runner sh -c 'bin/setup'
docker-compose up web
```
