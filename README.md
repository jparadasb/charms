<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/5114020/206097802-1a82330d-4b36-4c4a-8580-4aeb45285aaa.png">
    <img alt="Lerna" src="https://user-images.githubusercontent.com/5114020/206097528-433d7cec-d729-4b4f-a611-17c5d02c2bdd.png" width="128">
  </picture>
</p>
<br />

<div align="center" style="font-family:Papyrus; font-size:5em;">
Charms
</div>
<div align="center" style="font-family:Papyrus;">
Small scripts for small and repetitive tasks
</div>
</br>

<p align="center">
    <a href="">
      <img alt="MIT Licensed" src="https://img.shields.io/npm/l/@nrwl/workspace.svg?style=flat" />
    </a>
    <a href="https://www.npmjs.com/package/@jparadasb/charmsa">
      <img alt="NPM Status" src="https://img.shields.io/npm/v/@jparadasb/charms.svg?style=flat" />
    </a>
</p>

<hr />
</br>


<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#license">License</a></li>
  </ol>
</details>

</br>

<!-- ABOUT THE PROJECT -->
## About The Project

This project contains two magical spells to encrypt and decrypt secret files in your repository, using Keybase to handle the private keys to sign and allow you to use the teams feature to distribute secrets in your work team.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started


### Prerequisites

You will need to have setup your keybase account and the keybase CLI installed. 
[Read more](https://keybase.io/download)

### Installation

```sh
npm install --location=global @jparadasb/charms
```

<!-- USAGE EXAMPLES -->
## Usage

### Fidelius Charm (encrypt)

Imagine you have all your secrests or env files ignored in your project

![ignored env files](https://user-images.githubusercontent.com/5114020/206108353-43781239-b40a-4da2-8bea-a72216fbafa6.png)

you should run 

```sh
fidelius --user <keybase_username>
```
or
```sh
fidelius --team <keybase_teamname>
```
![charmfidelius](https://user-images.githubusercontent.com/5114020/206108678-29dbb9ed-5baa-4d29-b650-2d2ac90a5de7.gif)

Now you will see the encrypted files which you are secure to commit.

![encrypted files](https://user-images.githubusercontent.com/5114020/206109092-87d8c1f0-5359-4b91-937d-369ff908e5a5.png)

### Fidelio Charm flags

* --force [By default, the command will skip the generated encrypted files. To regenerate it use this flag]
* --user [If you are using your own user to encrypt]
* --team [If you are using the name of a team to encrypt]
* --paterm [the pattern of the secrets files to encrypt. default: *.env]

### Revelio Charm (decrypt)

Assuming you are cloning the repository, you are including in the keybase team and you want to decrypt the secrets files, run:

```sh
revelio
```
![charmrevelio](https://user-images.githubusercontent.com/5114020/206109643-b8da1a04-8506-4924-8a78-55d3111cd35b.gif)

Now you have the secrets files decrypted and can run your project without hesitate

### Revelio Charm flags

* --force [By default, the command will skip the generated decrypted files. To regenerate it use this fla]


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<sub>
    Icon made by Freepik from <a href="https://www.flaticon.com/free-icon/magic-wand_4233842?term=magic%20wand&related_id=4233842"> flaticon.com </a>
</sub>

