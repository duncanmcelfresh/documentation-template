*This template includes a suggested structure and content to include in project documentation. The purpose of this documentation is to make it easier to onboard new developers, and to ensure that important knowledge is easily accessible. Each of the sections has a list of suggested questions to answer. This is not strict - please include any other sections or information that you think would be useful.*

# Introduction 

- is this front end, back end, or something else?
- what are the primary languages and/or frameworks? (React? express? python?)
- what are the main compute & storage resources used?
- any other 3rd party services or libraries that the project relies on heavily (like Bookshelf for data management, or pytorch for machine learning).
- brief description of the project file structure and important files
- **any other “must-know” information for developers that isn’t included in the other sections**

# Integration

- are there other projects or services that this project relies on? (like APIs or front-ends)
- do other projects rely on this one?
- links and contact info for these other projects, if applicable

# CI/CD

- brief description of how CI/CD is handled. 

*The rest of this section may look different depending on how CI/CD is handled. Below are some suggested subsections.*

## Development

- project guidelines for development: are bug fixes and new features developed in a new branch of the repo? or on a staging branch?
- step-by-step instructions for using a development or staging version of the project
    - what compute infrastructure should be used? (personal laptop, cloud resources)
    - instructions for installing dependencies or preparing the dev environment
    - recommended IDE, if applicable
- instructions for integrating a dev version of the project into the deployment version 
- any services that are commonly used for development (like postman, or a staging environment for a front-end project)

## Testing

- where are tests?
- do tests use a specific framework or 3rd party?
- are test run automatically or manually?
- instructions for running tests manually, if applicable

## Deployment

- step-by-step instructions for compiling or building the project, if applicable
- step-by-step instructions for deploying the project, if applicable
- if deployment happens automatically:
    - what actions trigger deployment?
    - what service or process handles deployment?
- what is the deployment infrastructure. does this use compute instances? databases? lambda functions? other cloud services?
