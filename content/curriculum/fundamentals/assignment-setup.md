---
title: Setup for Assignments
---

This section describes the process for setting up assignments in Unit I.

First, ensure you have the [`app-app` generator](https://github.com/suncoast-devs/app-app) installed. We may have done
this in class, and you will only need to do it once:

```sh
npm install -g app-app
```

Also, set up hub to use `HTTPS` rather than `SSH` for repositories:

```sh
git config --global hub.protocol https
```

Open your terminal, then create and change into the project's directory:

```sh
mkdir -p ~/sdg/unit-1/hello-world
cd ~/sdg/unit-1/hello-world
```

Run the generator to create a boilerplate project:

```sh
app-app --alpha
```

Open the project folder in your editor (remember, `.` is an alias for the current directory):

```sh
code .
```

Tab back to your Terminal and start the development server:

```sh
npm start
```

This should automatically happen, but if it doesn't; navigate to [http://localhost:3000](http://localhost:3000) in your browser. As you make changes to your code, the development server will automatically refresh this page in real-time.

**Note**: Remember to check the appearance in your browser often! Fast, continuous feedback of your code will help
you create sites more efficiently.

While the development browser is running, it will control your Terminal. To exit it, press `Control-C`. You can always start it up again with `npm start`.

Using the file browser in your editor, open the file `public/index.html` and format your essay with HTML tags and place them into the document (remember all content goes _inside_ the `<body>` tags). Don't worry about the other files in the directory for now, we'll talk about those later, right now, we're mostly concerned with the two files in `public`; `index.html` and `screen.css`.
