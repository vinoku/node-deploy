
This is the README file for testing changes to the repository.I'm deploying to staging
=======
Another change
Another change
Testing the CircleCI Install
Checking on the local remote
Another new line for testing
One final github test
Adding a line for heroku push test.



## Import Data
mongoimport --username vinh78 --password vinh78 --uri "mongodb+srv://vinh78:vinh78@cluster0.iezrm.mongodb.net/node_deploy" --collection games --file games.tsv --type tsv --headerline

## SET ENV Variables
cd upload
export NG_CMD=prod
export MONGO_URL=mongodb+srv://vinh78:vinh78@cluster0.iezrm.mongodb.net/node_deploy
