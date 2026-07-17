# Task Manager
---
### Quick start
```bash
# 1. Clone a repository and enter your new directory
git clone https://github.com/hostvark/hexlet-task-manager.git
cd hexlet-task-manager

# 2. Set up the environment with .env file
cp .env_sample .env  # Edit the file .env based on the example of the .env_sample file

# 3. Install project dependencies
make install
make migrate
```

### Launch the project
```bash
# development modeApply migrations
make start-server

# Access at: http://localhost:8000
```

## Features

- **Registration and authorization** of users
- **Task Management** (CRUD)
- **Tags and Statuses** for tasks
- **Filtering** by tags, artist, status
- **Responsive Design** (Bootstrap 5)

## Technologies

- Python 3.13+
- Django 6.0+
- PostgreSQL / SQLite
- Bootstrap 5
- Gunicorn

## Basic commands

```bash
make install      # Install dependencies
make start-server # run the server
make test         # run the tests
make lint         # linter code check
make migrate      # apply migrations
```
