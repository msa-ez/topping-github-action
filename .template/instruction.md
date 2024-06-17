#### Integrated Environment: GitHub Actions is built directly into the GitHub platform, allowing for CI/CD (Continuous Integration and Continuous Deployment) setups without the need for additional tools or services.

#### Easy Configuration: Workflow files in .yml or .yaml format allow for easy definition and structuring of desired tasks.

#### Diverse Event Triggers: You can set workflows to run in response to a variety of events in a GitHub repository, such as pull requests, issue creations, or new branch creations.

#### Matrix Builds: This feature enables simultaneous testing and building across multiple OS, versions, and runtime environments.

#### Customization & Extensibility: Utilize thousands of ready-made Actions from the marketplace or write your own custom Actions to expand your workflows.

#### Security: GitHub Actions provides features for security, including secret storage and user permissions management.

#### Hosted Runners: GitHub provides hosted runners across various OS environments, allowing workflows to run without the need for additional infrastructure setup.

#### Support for Self-hosted Runners: If there are specialized requirements or a need for fine-grained control over infrastructure, users can host runners on their own servers.

#### Container Support: Execute jobs within Docker containers in workflows.

#### Real-time Logging: Live logs can be viewed during workflow execution, making debugging easier.

#### Cost-effective: GitHub Actions is free for public repositories and also offers a generous amount of free minutes for private repositories.

### How to run

#### 1. change the folder name 
```
github/workflows -> .github/workflows
```
#### 2. change the configuration of git-action.

1) Check Setting of your repository 
<img width="931" alt="setting1" src="https://github.com/sooheon45/topping-github-action/assets/54785805/4007c96b-1244-43ad-bf5c-042a114a0ba1">

2) Setting > Actions > Genernal > Workflow permissions 
<img width="333" alt="setting2" src="https://github.com/sooheon45/topping-github-action/assets/54785805/059d6d61-ee9e-41ec-8e08-1021031a18fe">

3) Select of "Read and write Permissions."
<img width="903" alt="setting3" src="https://github.com/sooheon45/topping-github-action/assets/54785805/fe562497-e860-4d8b-9d5a-f189ef3dce8d">

#### 3. to execute the action, create a release with version v0.x.
<img width="845" alt="image" src="https://github.com/msa-ez/topping-github-action/assets/123912988/2cecbec8-212e-4804-a998-b9203d8218d0">

