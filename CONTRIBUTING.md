# Contribution Guidelines

- Fork the Repository
> Click on <kbd>Fork</kbd> button on top right corner

- Clone the Repository
```bash
$ git clone https://github.com/<YOUR USERNAME>/git-n-github-101.git
```

- Make your changes
> - Add your name and your avatar in the list.json file
> - Find the link to your avatar from this website: [dsc-pokemon-list.netlify.app](https://dsc-pokemon-list.netlify.app/)

> Convention Followed in the JSON file
>   - See the position of comma `,`

❌
```js
[
    {
        "avatar": "https://pokeres.bastionbot.org/images/pokemon/1.png",
        "name": "John Doe"
    },
    {
        "avatar": "https://pokeres.bastionbot.org/images/pokemon/1.png",
        "name": "John Doe"
    }
]
```

✅
```js
[
    {
        "avatar": "https://pokeres.bastionbot.org/images/pokemon/1.png",
        "name": "John Doe"
    }
    ,{
        "avatar": "https://pokeres.bastionbot.org/images/pokemon/1.png",
        "name": "John Doe"
    }
]
```

- Push your changes
```bash
$ git push origin master
```

- Make a Pull Request
> Go back to your repo on the GitHub website and make a Pull Request to dscssgi/git-n-github-101

- Finally after successfully merging your Pull Request you can see your contribution in the website: [dsc-open-source.netlify.app](https://dsc-open-source.netlify.app/)

### Thank You for attending the session and for your contribution.
