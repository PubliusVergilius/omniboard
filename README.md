# Omniboard
App to manage teams and their tasks.
## Features
- Written in Go
- Modular Design where the email service is not coupled to the implementation
- To maintain the stateless nature of the application, comments to a task is stored in redis while being stored: if succeceds a notification is sent to the task owner; if not, an error notification is sent to the author.
# TODO
- Alow users to leave comments for the tasks. When a user publishes a comment it is stored in a db, and the app send an email to a specific address configured in the app.
