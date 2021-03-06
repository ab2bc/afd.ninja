Running at http://localhost:3000/

Every push to master will deploy a new version of this app to https://afdme.herokuapp.com/.
Deploys happen automatically: be sure that this branch in GitHub is always in a deployable state and any tests have passed before you push.

#### Add Hubot

The docker image is ready.
Everyone can start hacking the adapter code, or launch his/her own bot within a few minutes now.
Please head over to the [Hubot Integration Project](https://github.com/RocketChat/hubot-rocketchat) for more information.

## Development Installation

Prerequisites:

* [Git](http://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
* [Meteor](https://www.meteor.com/install)

Now just clone and start the app:

```sh
git clone https://github.com/ab2bc/afd.ninja.git
cd afd.ninja
meteor
```

or use docker:

```
git clone https://github.com/ab2bc/afd.ninja.git
cd afd.ninja
docker run -it -p 3000:3000 -v "$(pwd)":/app danieldent/meteor
```

Emoji provided free by [Emoji One](http://emojione.com)

Performance monitoring provided by [Kadira](https://kadira.io/)
