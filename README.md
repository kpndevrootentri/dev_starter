# dev_starter

## install nvm 

```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.0/install.sh | bash && source ~/.zshrc

```
node v18 is recommened 
```bash
nvm install v18
```

## install yarn 
yarn is a default node package manager
```bash
npm i -g yarn
```
## recommend softwares used 
```bash
slack-desktop gedit gedit visual-studio-code curl brave-browser firefox google-chrome postman notejot kdeconnect
```

## recommend packages 
```bash
docker-ce docker-compose python3 python3-pip python3-pytest postgresql postgresql-contrib
```

## recomended pip packages

```bash
virtualenv virtualenvwrapper
```
## git commands

```bash
git status
git add .
git commit -m "commit name"
git push origin branch_name
git checkout alpha-2 // alpha-2 is the channel branch
git reset --hard origin/add-new-freshchat-fields //add-new-freshchat-fields  feature branch
git push origin alpha-2 -f
```
## additional git commands

```bash
git stash list
git switch add-new-freshchat-fields
git checkout alpha-2
git log
git checkout 75d4b9f6 // 75d4b9f6 is the commit id
git cherry-pick 6f7db0351006029e6ece873bcf3b8ace5d59e857
git cherry-pick --abort
git commit --allow-empty
git rebase -i bc4b2ddfa3dfe8e7cd9c0d63b66d534e325a6bfc
git push origin add-new-freshchat-fields -f
git checkout alpha-2
git reset --hard origin/add-new-freshchat-fields
git log
git push origin alpha-2 -f

```

## clone the repos

landing page cms
```bash 
git clone git@gitlab.com:entri/entrime.git && cd entrime
```
entri webapp
```bash
git clone git@gitlab.com:entri/entriweb.git && cd entriweb && yarn
```
entri content dashboard
```bash
git clone git@gitlab.com:entri/content-platform.git
```


## git lab ssh connection 
```bash
 ssh-keygen -t ed25519 -C  "gitlab" && cat $HOME/.ssh/id_ed25519.pub
```
Visit the link [gitlab](https://gitlab.com/-/user_settings/ssh_keys).
and add the ssh key 

