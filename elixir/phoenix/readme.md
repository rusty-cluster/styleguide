## Conventions

* front-end agnostic JSON API with CORS 
* [JWT via https only cookie](https://blog.logrocket.com/jwt-authentication-best-practices/) 
* Ueberauth for authentication
* Bodyguard for authorization
* Postgres with jsonb over Mongo
* configuration via ENV variables

## Boilerplate

```
mix phx.new fitlog-phoenix --app fitlog --no-assets --no-html --no-dashboard --no-gettext --no-live --no-mailer
```

## Anti-patterns

* Phoenix.LiveView moves computation from browser to back-end. It can't [work offline](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps) too. 
