## Conventions

* front-end agnostic JSON API with CORS 
* [JWT via https only cookie](https://blog.logrocket.com/jwt-authentication-best-practices/) 
* Ueberauth for authentication
* Bodyguard for authorization
* Postgres with jsonb over Mongo
* [ExMachina](https://github.com/thoughtbot/ex_machina) and [Faker](https://github.com/elixirs/faker) for creating test data 
* configuration via ENV variables

## Boilerplate

```
mix phx.new fitlog-phoenix --app fitlog --no-assets --no-html --no-dashboard --no-gettext --no-live --no-mailer
```
