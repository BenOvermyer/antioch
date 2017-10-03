# Antioch, a Theme for WordPress

This is a theme for WordPress. It's meant for the Geek Partnership Society.

## Development

This project requires Docker and Sass.

Start by running the Docker containers:

```
docker-compose up -d
```

And then, whenever you change some Sass:

```
sass --scss sass/style.scss style.css
```

or:

```
sass --scss --watch sass/style.scss style.css
```