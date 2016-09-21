# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.

What is the purpose of a backend?

```bash
To store data, so it can be accessed by the site.
```

Which layer in the MVC pattern is used by the controller to fetch data?

```bash
The controler fetches data from the model.
```

Which layer in the MVC pattern communicates with the model?

```bash
The controler communicates with the model.
```

Why don't we use views in our interpretation of the MVC pattern?

```bash
// your response here
```

What does C.R.U.D stand for?

```bash
Create Read Update Delete.
```

In which part of the MVC pattern can we find C.R.U.D actions?

```bash
controler
```

List at least 5 standard actions that C.R.U.D corresponds to?

```bash
Create, index, show, update and destroy.
```

A user action fires a `GET` request for `/persons/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```bash
1) client requests data from server.
2) server tells controler ti get data.
3) controler requests data from model
4) model give data to controler
5) controler gives data to server
6) server sends data back to client
```

What is the command to generate a new rails-api app?

```bash
bundle exec rails server
```

What is the command to start an instance of a rails server?

```bash
bundle exex rake
```

What are the commands to drop, create and migrate a database? (3 bullet points)

```bash
1) drop_table
2) create_table
3) bin/rails db:migrate
```

What is the command to scaffold a pet with a name and age attributes (hint:
Also think of the data types for each attribute)?

```bash
// your response here
```
