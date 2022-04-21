# AWS CDK Python Devcontainer

A barebones devcontainer with AWS CLI and CDK installed. These are installed at container build time, so it's the version that's available now.

It's all ready to run `cdk init --language python` - but you'll need to `rm README.md` first to get rid of this README file!

Once the CDK app has init, you don't need to follow the otherwise excellent advice to activate a virtaulenv - the devcontainer is your environment.

It:
* mounts your `~/aws` folder into the devcontainer so you get access to your local AWS_PROFILE options.
* includes DIND (Docker in Docker) so your CDK can build your Python Lambda functions. 🎉 🐍
* has the git CLI - cos that's table stakes.


