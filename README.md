# Playground for Keystone (js)

This is a place to learn and play with Keystone.

Follow this process to start the Keystone App for the first time:

```
# Open the directory
cd playground-keystone

# Install Node.js dependencies
npm install

# Build and serve the App at localhost:3000
node keystone
```

## What is Keystone?

Keystone is a declarative, data driven JavaScript application framework for building content management systems.

## Prerequisites

### Skill

  * Able to read Markdown (this document is written in Markdown :smile:).
  * Understand how to execute terminal commands.
  * Experience with a package manager such as Homebrew: https://brew.sh/

### Environment

  * Git
  * Node.js (0.10+): https://nodejs.org/en/
  * NPM: (installed with Node)
  * MongoDB (2.4+) server such as Community Server: https://www.mongodb.com/download-center#community
  * Text editor such as Atom: https://atom.io/

## Get started

Follow this process to start from scratch with the Keystone Generator:

```
# Install the Yeoman generator tool
npm install -g yo

# Install the Keystone generator
npm install -g generator-keystone

# Create a directory
mkdir playground-keystone

# Open directory
cd playground-keystone

# Generate project
yo keystone

# Select options:
? What is the name of your project? Playground Keystone
? Would you like to use Pug, Nunjucks, Twig or Handlebars for templates? [pug | nunjucks | twig | hbs] hbs
? Which CSS pre-processor would you like? [less | sass | stylus] sass
? Would you like to include a Blog? No
? Would you like to include an Image Gallery? No
? Would you like to include a Contact Form? No
? What would you like to call the User model? User
? Enter an email address for the first Admin user: user@keystonejs.com
? Enter a password for the first Admin user:
 Please use a temporary password as it will be saved in plain text and change it after the first login. admin
? Would you like to create a new directory for your project? No
? ------------------------------------------------
    Would you like to include Email configuration in your project?
    We will set you up with an email template for enquiries as well
    as optional mailgun integration No
? ------------------------------------------------
    Finally, would you like to include extra code comments in
    your project? If you're new to Keystone, these may be helpful. Yes
```

## Learn more

  * Official website: http://keystonejs.com/
  * Guides: http://keystonejs.com/docs/
  * Source: https://github.com/keystonejs/keystone
