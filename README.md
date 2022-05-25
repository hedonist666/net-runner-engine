# Net-runner-engine


<p align="center">
  <img alt="Net-runner" src="https://raw.githubusercontent.com/hedonist666/net-runner-engine/main/logo.svg" height="420" width="620"/>
</p>


## About
This is the [NS-3](https://www.nsnam.org/) based [node-addon-api](https://github.com/nodejs/node-addon-api) module used for the [Net-runner](https://net-runner.xyz) website. 
It's core functionality is to launch the NS-3 functions according to JSON config specified in argument and dump the results. Example config and usage from Node.js can be found at [test](https://github.com/hedonist666/net-runner-engine/blob/main/test/test_binding.js) folder
## Goal
The goal of this project is to provide the web-based platform who those who are learning the inner workings of computer networks. Although the project is up and running, this project is very young and has **many** work to do. So I decided to do this with the NS-3 community all together!
If you are an NS-3 expert, or Node.js enthusiast, or just want to commit to this project, feel free to contact me (see contacts below) and ask any questions!
## Running
The code is designed to run inside the Docker container, but if you want to use this module without Docker contact me and I'll add appropriate node-gyp configs to this repo. The example scripts for running the module can be found at [scripts](https://github.com/hedonist666/net-runner-engine/blob/main/scripts) folder.
## Architecture
The structure of input config is show below:
```
{
  nodes: [{ id, title, x, y, type, applications }],
  edges: [{ source, target, type, sourceIP, targetIP }],
  options: { animeLen: 10, popuplateIP: true }
}
```
A network is represented as a graph, containing information about nodes and connections in a network. The module's work is to handle this graph and call the approptiate NS-3 functions.
## TODO's
Will be added soon.
## Contacts
Email: little_scamp@yahoo.com
Feel free to ask any questions!
<style type="text/css">
img {
  width: 64px;
  height: 64px;
}
</style>
