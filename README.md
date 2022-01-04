![DuoBahn Logo](https://github.com/tscholze/kotlin-surfaceduo-duobahn/blob/main/docs/logo.png?raw=true)

# kotlin-aggregator-script-duobahn
> This Aggregator script for my app Android ["DuoBahn"](https://github.com/tscholze/kotlin-surfaceduo-duobahn) app is written in Kotlin, compiled to a *.jar and now runs on GitHub Actions every 6 hours to fetch all interesing information from the German federal Autobahn API.

**Caution**
Currently disabled until DuoBahn app uses the data.

# What does a GitHub Action run do?
1. Checks out the repository
2. Renames the latest `autobahns.json` to an archived one with time stamp
3. Sets up a JVM environment
4. Runs the script which creates a new `autobahns.json` file
5. Commits the updated file

# Links
The actual source code of the script is located in the [Android app repository](https://github.com/tscholze/kotlin-surfaceduo-duobahn). Please use this "parent" repository for issues, code pull requests and all other shenanigans

## Authors

At the moment, it is just me, [Tobi]([https://tscholze.github.io).

## Acknowledgments

* [Federal Autobahn API](https://autobahn.api.bund.dev/)
* Github Actions: [Setup Java](https://github.com/actions/setup-java)
* [Crontab Guru](https://crontab.guru]) for teaching my the syntax

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
Dependencies or assets maybe licensed differently.
