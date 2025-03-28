# secure-devops-app

## Setup Guide

### 1. Launching an AWS EC2 Instance

1. **Sign in to AWS Management Console**: Access your AWS account and navigate to the EC2 dashboard.
2. **Launch Instance**: Follow the prompts to create a new EC2 instance with your desired specifications.
3. **Connect to Instance**: Use SSH to connect to your EC2 instance.

For detailed instructions, refer to the [AWS EC2 User Guide](https://docs.aws.amazon.com/ec2/index.html).

### 2. Setting Up the GitHub Repository

1. **Create a Repository**: On GitHub, create a new repository named `secure-devops-app`.
2. **Clone Repository Locally**: Clone the repository to your local machine.
3. **Add Project Files**: Add your project files to the repository.
4. **Commit and Push**: Commit your changes and push them to GitHub.

### 3. Writing Ansible Playbooks in VSCode

1. **Set Up VSCode**: Install Visual Studio Code and the Ansible extension.
2. **Create Ansible Roles**: Define roles for Nginx, MongoDB, and Flask application.
3. **Develop Playbooks**: Write playbooks to automate server configurations and deployments.

For guidance on writing Ansible playbooks, refer to the [Ansible Documentation](https://docs.ansible.com/ansible/latest/user_guide/playbooks.html).

### 4. Creating the Jenkins Pipeline (`Jenkinsfile`)

1. **Set Up Jenkins**: Install Jenkins on your EC2 instance.
2. **Create Jenkinsfile**: Define the pipeline stages, including checkout, dependency installation, and deployment.
3. **Configure Pipeline**: Set up the pipeline in Jenkins to automate the deployment process.

For more information on Jenkins pipelines, visit the [Jenkins Pipeline Documentation](https://www.jenkins.io/doc/book/pipeline/).

### 5. Deployment Walkthrough

1. **Set Up EC2 Instance**: Follow the EC2 setup instructions above.
2. **Run EC2 Setup Script**: Execute `setup_ec2.sh` to install dependencies and configure the server.
3. **Deploy Application**: Use Ansible playbooks to deploy the Flask application, configure Nginx, and set up MongoDB.

## Contributing

We welcome contributions to enhance the functionality and security of this project. To contribute:

1. **Fork the Repository**: Create a personal copy of the repository.
2. **Clone Your Fork**: Clone your fork to your local machine.
3. **Create a Branch**: Develop your feature or fix in a separate branch.
4. **Commit Changes**: Commit your changes with descriptive messages.
5. **Push and Create Pull Request**: Push your changes and submit a pull request for review.

Please ensure that your code adheres to the project's coding standards and passes all tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

- **Flask**: A micro web framework for Python.
- **MongoDB**: A document-oriented NoSQL database.
- **Nginx**: A high-performance web server and reverse proxy.
- **Jenkins**: An open-source automation server for continuous integration and delivery.
- **Ansible**: An automation tool for configuration management and deployment.

## Contact Information

For questions or feedback, please contact [Ifeoma Collins](ifeomalcollins@gmail.com).

