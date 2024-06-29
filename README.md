# Whatnot Requirements
 - The Kubernetes files should be designed with production quality, high availability,
and scalability in mind.
 - This solution should build and run.
 - Reproducibility.
 - Reusability. Use the most efficient cloud cost management approach when
creating your manifests in case the company decides to create 20 additional
similar applications.
 - Treat this as introducing a new application into an existing Kubernetes cluster that
already has a number of other web applications deployed.
 - Do not affix the application pod to a static port on the host.

# Instructions

## Do the following:
1. Write a Dockerfile to package this flask Application as a container.
2. Write the necessary Kubernetes manifests to deploy this container as a web
application.
3. Incorporate a dummy URL this application would respond on.

Then, provide a document with the answers to the following questions in no more than
two short paragraphs:
1. In a few words, describe how you provision cloud infrastructure from scratch to
host this application with High Availability in mind. (Output should not be code, but
a description in your own words). Some topics you might want to include:
    1. Cloud of choice
    2. Infrastructure design and components
    3. Automation and deployment tools
2. In a few words, describe how you would create a continuous delivery pipeline to
automatically build and deploy this application to dev --> int --> uat --> prod
environments with every Git push. (Output should not be code, but a description in
your own words). Some topics you might want to include:
    1. CI/CD tool of choice and setup
    2. Procedural build steps
    3. Procedural deployment steps