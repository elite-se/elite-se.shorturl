# Elite-SE: URL Shortener
This url shortener contains a list of arrays that are important for the program.

It is available as a GitHub Pages at https://elite-se.github.io/elite-se.shorturl/.

## 🏗️ Architecture

This project consists only of static files and is client-side only.
To achieve this, we use the three files in the `docs` folder:
- `links.json`: Contains the links and their shortened versions and a description.
- `index.html`: Shows a list of the available links.
- `404.html`: This is shown by GitHub Pages when no file is found for a give path.
  We use this page to load the links and redirect the user to the target of the link.

Since the GitHub Pages are built from the `main` branch, the shortener is always up-to-date.

> [!NOTE]
> The folder containing the public files is called `docs` as this is the only folder GitHub Pages will server (apart from root).
> Root was not chosen to keep other files from poluting the served files.

## 🛠️ Development
This project contains a `package.json` which only contains the `dev` script and the required dev-dependencies.
You can therefore locally use:

```shell
npm run dev
```

## 🧑‍🤝‍🧑 Contributing

Feel free to suggest more links or just create a pull request.\
The more links, the better!

## License
MIT License, see the [LICENSE file](LICENSE)
