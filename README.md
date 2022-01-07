## Locking rows issue

see https://github.com/rsim/oracle-enhanced/issues/2237

```
rails c
> a = Article.create!(title: "test", body: "test body")
> a.with_lock {}
```

##
