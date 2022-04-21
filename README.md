# AWS CDK Python Devcontainer

A barebones devcontainer with AWS CLI and CDK installed. These are installed at container build time, so it's the version that's availeble now.

It:
* mounts your `~/aws` folder into the devcontainer so you get access to your local AWS_PROFILE options.
* includes DIND (Docker in Docker) so your CDK can build your Python Lambda functions. 🎉 🐍
* has the git CLI - cos that's table stakes.
