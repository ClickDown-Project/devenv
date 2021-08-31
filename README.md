# Devenv

Devenv is a summary folder of the ClickDown Project.

## Installation

If you wanna use the ClickDown Project, you need to get other repositories below.

```
Webapp: git@github.com:ClickDown-Project/webapp.git
Api: git@github.com:ClickDown-Project/api.git
Auth: git@github.com:ClickDown-Project/auth.git
Message-broker: git@github.com:ClickDown-Project/message-broker.git
```

## Usage

First, you need to build all images.

```docker
docker-compose build
```

Next steps, run your containers after building.

```docker
docker-compose up -d
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
