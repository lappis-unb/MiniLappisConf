# lappis website

## Getting Started

#### Docker

```console
docker run -p 4000:4000 --rm -it $(docker build -q .)
```


#### Manual

1) Install a full [Ruby development environment](https://jekyllrb.com/docs/installation/)
2) Install Jekyll and [bundler](https://jekyllrb.com/docs/ruby-101/#bundler) [gems](https://jekyllrb.com/docs/ruby-101/#gems)
```bash
gem install jekyll bundler
```
3) Build the site and make it available on a local server
```
bundle exec jekyll serve
````

4) Now browse to http://localhost:4000