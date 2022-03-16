<p align="center">
    <a href="https://github.com/Vecnavium/FormsUI"></a><br>
    <b>A PocketMine-MP Virion that allows you to create forms. A longterm and ongoing support for this virion and will be done at it's best to improve. The project FormsUI has been taken from FormAPI to maintain and keeping it up to date for PocketMine API 4.0.0 and up.</b>
</p>

<p align="center">
    <img alt="GitHubrelease" src="https://img.shields.io/github/v/release/Vecnavium/FormsUI?label=release&sort=semver">
      <img alt="Stars" src= "https://img.shields.io/github/stars/Vecnavium/FormsUI?style=for-the-badge">
    <a href="https://discord.gg/6M9tGyWPjr"><img src="https://img.shields.io/discord/837701868649709568?label=discord&color=7289DA&logo=discord" alt="Discord" /></a>
</p>


# Pull Requests
Pull Requests are welcomed. PRs must be related to changes that patch bugs or improves the virion itself.

# BugReport

- Contact support in the [Discord Server](https://discord.gg/jWFB56RqUN)

- Create an [Issue](https://github.com/Vecnavium/FormsUI/issues/new)

- Write your bug & the issue you are having with all informations including the error so I can track the issue

- Submit the issue and be patient for a response for a solution to your problem
 
We will NOT assist you if you are using a spoon or modified PocketMine-MP version.

## Converting from FormAPI to FormsUI (Virion)

This is from FormAPI

```yml
projects:
  YourProject:
    libs:
      - src: jojoe77777/FormAPI/libFormAPI
        version: ^2.1.0
```

And you would need to change it to this to FormsUI


```yml
projects:
  YourProject:
    libs:
      - src: Vecnavium/FormsUI/libFormsUI
        version: ^2.0.0
```

## Converting from FormAPI to FormsUI (As a plugin)

It's nothing more than a simple drag and drop FormsUI and replace FormAPI that is in your libs directory. And if you properly remove FormAPI and dropped FormsUI into the libs directory everything should work as expected. No code is needed to be modified or changed
