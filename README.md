# DevConnector
Networking Tool for Developers - A MERN Project

This app requires a file in the config directory called keys_dev.js. This file is used for the local dev environment and contains environmental variables. It is the same as keys_prod.js, except it may include hard-coded variables. See the example below.

keys_dev.js example:

module.exports = {
	mongoURI: <'mongoKey'>,
	jwtSecret: <'tokenVar'>,
	githubClientId: <'keyForGithubClient'>,
	githubSecret: <'githubApiKey'>
}

Each key requires a value in order to make the application work.