# Python Flask Docker image

This project provides a Python Flask Docker image for development purposes.


## Environment Variables

| Variable         | Required | Default   | Description |
|------------------|----------|-----------| ------------|
| `FLASK_APP`  | Yes      |     `app.py`      |  |
| `FLASK_RUN_HOST`  |     Yes     | `0.0.0.0`     | Local |
| `FLASK_ENV` |          | `development` | This allow the reload  |


## Start project

RUN in the terminal

```bash
    docker-compose up
```