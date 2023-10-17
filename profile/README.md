# <img src="https://github.com/Belgify/.github/assets/146539991/c00b78bc-d7f3-4782-a852-4a7e5ccad27e" width="25" /> Belgify project - E-Shop 🍺 - 🇧🇪

* [Technologies](#technologies)
* [Workflow](#workflow)
  * [Github configuration](#github-configuration)
  * [Github workflow](#github-workflow)

## Technologies
1. Backend
   * Laravel (php)
   * Docker
   * K8S (Kubernetes)
2. Database
   * SQL
3. Frontend
   * NextJs v13 (server & client components) (typescript)
   * 

## Workflow
------------
### Github configuration
[Setup an SSH key on your account settings for pulling the repositories](https://docs.github.com/fr/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

> Never cloning/pulling/pushing on a repository with `https`! Always using `ssh`

### Github workflow

1. Commit angular convetions

> Syntax : "type(Scope): Ticket-Name-0: Atomic message about your commit"
>
> Ex : "chore(Project): Front-1: First commit"

The different type :
1. chore : This type used to commit the core of the project
2. feat  : This type used to commit a new features of the project
3. doc   : This type used to commit a new documentation
4. style : This type used to commit an update about the code style
5. fix   : This type used to commit a fix of a bug
6. hotfix: This type used to commit a fix for pushing in a production

2. Branch's conventions

* main ( production branch )
* develop ( development branch )
  * feat/Scope--New-of-feaure ( feature's branch )
  * fix/Scope--fix-name ( Fix's branch )
  * ... Same type of a commit. You should replace the suffix before `/`
