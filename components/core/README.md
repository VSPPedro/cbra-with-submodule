## Create Submodule component_one in core folder

git submodule add git@github.com:VSPPedro/component-one-submodule.git components/core/component_one


## Make sure your submodule is actually at the branch that you want:

git checkout -b branch --track origin/branch

### If the master branch already exist:

git branch -u origin/master master


### Update submodules

git submodule update --remote


### Update only one submodule

git submodule update <specific path to submodule>
