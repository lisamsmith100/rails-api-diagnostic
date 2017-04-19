# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.

What is the purpose of a backend?

```md
The purpose of a backend is to store data and persist data.
```

Which layer in the MVC pattern is used by the controller to fetch data?

```md
The model is used by the controller to fetch data.
```

Which layer in the MVC pattern communicates with the model?

```md
The controller communicates with the model.
```

Why don't we use views in our interpretation of the MVC pattern?

```md
We aren't using views because we are focusing on SPAs--beyond scope of this class.
```

What does C.R.U.D stand for?

```md
Create, Read, Update, Destroy
```

In which part of the MVC pattern can we find C.R.U.D actions?

```md
Router
```

List at least 5 standard rails actions that C.R.U.D requests correspond to?

```md
Index, Show, Create, Update, Destroy
```

A user action fires a `GET` request for `/people/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```md
ran out of time to write more elaborate answer
~design curl request - use server to send req
~update routes.rb - router takes a look at where to look and what to do (GET/POST)
~update controller_file.rb - controller translates the Rails command to SQL and sends to model/DB
~use localhost to view changes
```

What is the command to generate a new rails-api app?

```bash
bin/rails generate
```

What is the command to start an instance of a rails server?

```bash
bin/rails server
```

What are the commands to drop, create, migrate and seed a database from the command
line? (5 bullet points)

```bash
~$bin/rake db:drop
~$bin/rake db:create
~$bin/rake db:migrate
~$bin/rake db:seed

```

What is the command to scaffold a pet with a name and age attributes (hint:
Also think of the data types for each attribute)?

```bash
bin/rails generate scaffold pet name:string age:integer
```
