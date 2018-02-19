# Milo IDE

The Milo IDE is a web based platform targetted at students who wish to learn concepts of Machine Learning and Linear Algebra, with no prior programming experience. The IDE is designed to support introductory level Data Science, ML and Linear Algebra courses typically taught at undergraduate programs. 

# Authors
* Arjun Rao [Github](github.com/arjun-rao)
* Ayush Bihani [Github](github.com/ayushbihani)

# License
All code related to this project will eventually be released under the Apache 2.0 License - see respective repositories for details.

# Project Structure

The entire project is split across the repositories described below. We will be updating this page shortly with more details.

# [Milo Blocks](https://github.com/4and4/milo-blocks)

Milo Blocks is a fork of Google's Blockly that has been modified to work as a node-module. Milo Blocks consists of custom block implementations for the Milo IDE. 

See issues [here](https://github.com/4and4/milo-blocks/issues)


# [Milo Server](https://github.com/4and4/MiloServer)

Milo Server is the main ExpressJS backend server that will be hosting the Milo IDE and the associated backend for managing interactions to the Milo Server from the IDE. 

## Features
* Host Client Side IDE that will be accessible at <insert.domain.tld>/editor
* Support backend API for XML storage - GET/POST to <insert.domain.tld>/api/storage
* Online Gallery view of stored projects with public and private projects


## Road Map
* Exercise Builder - for faculty to create exercises on Milo
* Collaborative Editing - for multiple users to login and work on the same project
* Classroom mode for monitoring progress of multiple students.

See issues [here](https://github.com/4and4/MiloServer/issues)
