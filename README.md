## Locking rows issue

https://github.com/rails/rails/issues/44114

```
rails c
> a = Article.create!(title: "test", body: "test body")
> a.with_lock {}
```

##
