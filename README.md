![Logo of the project](./images/el-logo.png)

# Blog for http://elabio (not yet setup)
> Additional information or tag line

A brief description of your project, what it is used for.

## Installing / Getting started

A quick introduction of the minimal setup you need to get a hello world up &
running.

```shell
commands here
```

Here you should say what actually happens when you execute the code above.

## Developing

### Built With
Drupal 8
PHP 7
Mysql 5.5

### Prerequisites
Docksal (https://docksal.io/) - For development environment

```shell
# Install dosksal
curl -fsSL get.docksal.io | sh
```


### Setting up Dev

```shell

git clone git@github.com:leoman730/blog-elabio.git
cd blog-elabio

# Start doskal as local dev environment
fin vm start
fin up

# Set up local development host address (blog.elab.dev)
fin hosts add blog.elab.dev
fin restart
```

Once dosksal restart properly, refer to .docksal/docksal.env for credentials set up. (subject to change locally)


Additional php, mysql setting could be made under .docksal/etc. You may need to restart docksal thereafter.
```shell
fin restart
```

### Building

If your project needs some additional steps for the developer to build the
project after some code changes, state them here. for example:

```shell
./configure
make
make install
```

Here again you should state what actually happens when the code above gets
executed.

### Deploying / Publishing
give instructions on how to build and release a new version
In case there's some step you have to take that publishes this project to a
server, this is the right time to state it.

```shell
packagemanager deploy your-project -s server.com -u username -p password
```

And again you'd need to tell what the previous code actually does.

## Versioning

We can maybe use [SemVer](http://semver.org/) for versioning. For the versions available, see the [link to tags on this repository](/tags).


## Configuration

Here you should write what are all of the configurations a user can enter when
using the project.

## Tests

Describe and show how to run the tests with code examples.
Explain what these tests test and why.

```shell
Give an example
```

## Style guide

Explain your code style and show how to check it.

## Api Reference

If the api is external, link to api documentation. If not describe your api including authentication methods as well as explaining all the endpoints with their required parameters.


## Database

Explaining what database (and version) has been used. Provide download links.
Documents your database design and schemas, relations etc... 

## Licensing

State what the license is and how to find the text version of the license.
