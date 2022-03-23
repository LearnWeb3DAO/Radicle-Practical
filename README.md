# Radicle Practical level

![](https://i.imgur.com/Adjv2wy.png)

We will learn how to create a repository on Radicle and push some code in there similar to how you would do on github
Lets get started 🚀

# Prerequisites
- You have completed the [Radicle level](https://github.com/LearnWeb3DAO/Radicle)
- You have completed the [ENS level] https://github.com/LearnWeb3DAO/ENS


# Installation


- We will use Radicle CLI to do our operations

- Open up your terminal and clone the Radicle CLI repo

    ```bash
    git clone https://github.com/radicle-dev/radicle-cli.git
    cd radicle-cli
    ```

- Install `rustup` by following the instructions on the given [link](https://doc.rust-lang.org/cargo/getting-started/installation.html)

    ![](https://i.imgur.com/sofFA70.png)

- Close your terminal and open it again(this step is important, otherwise you wont be able to follow the next steps)

- Execute the following command on your terminal pointing to radicle-cli folder

    ```bash
    rustup
    ```
- After the previous step on the same terminal execute the following

    ```bash
    cargo install --force --locked --path .
    ```

- Before procedding further, make sure your git is updated. To update git follow [the following instructions](https://confluence.atlassian.com/bitbucketserver/installing-and-upgrading-git-776640906.html)
![](https://i.imgur.com/D21GyGS.png)

- We will now create a profile on radicle, execute the following command to authenticate yourself on radicle

    ```bash
    rad auth
    ```
    ![](https://i.imgur.com/9SYf3uf.png)

    ![](https://i.imgur.com/4kkEK5W.png)

- Now lets go inside the `ENS` repo, on your computer from the [ENS level](https://github.com/LearnWeb3DAO/ENS)

- In your terminal pointing to the `ENS` folder execute the following command
    - `rad init` creates a project URN for your repository and associates your Peer ID with it for sharing on the Radicle network.


    ```bash
    rad init
    ```
    ![](https://i.imgur.com/MiIjKoJ.png)

- Then we can finally push our repo to the radicle network, execute the following command on the same terminal window

    ```bash
    rad push --seed willow.radicle.garden
    ```
    
    ![](https://i.imgur.com/KciQ53j.png)

- Click on one of the web links provided and you should be able to see your repository using the radicle's web client

- The one I deployed can be viewed [here](https://app.radicle.network/seeds/willow.radicle.garden/rad:git:hnrke75ditp1por96j4z9tg3bne9wbpb5qico)



Lets goo 🚀 You have finally published your repo on radicle
