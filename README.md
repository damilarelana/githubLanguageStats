# Github Language Statistics Monitor

## A simple React app that consumes [Github's repository API](https://api.github.com/search/repositories?q=stars:>1+language:${language}&sort=stars&order=desc&type=Repositories) to display engagement statistics for key per language ['all', 'javascript', 'python', 'go', 'rust'] i.e.

```
* respository name
* respository owner handle
* stargazers_count
```

### Implemented with 

* pure react
* pure babel