# Awesome Golem [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Welcome to **Awesome Golem**, a community-curated list of resources, links, projects, tools and apps on Golem!
Note: this guide and it's contents is specific to New Golem and it's current implementation, Yagna. For Legacy (Clay) Golem, you can find the documentation [here](https://docs.golem.network/) and [comms archive](https://trello.com/b/95eZBUfT/golem-comms-archive).

</p>
<p align="center">
    <a href="https://twitter.com/golemproject" alt="Twitter">
        <img src="https://img.shields.io/twitter/follow/golemproject?style=social" />
    </a>
    <a href="https://discord.gg/y29dtcM" alt="Discord">
        <img src="https://img.shields.io/discord/684703559954333727?logo=discord" />
    </a>  
    <a href="https://reddit.com/GolemProject" alt="Reddit">
        <img src="https://img.shields.io/reddit/subreddit-subscribers/GolemProject?style=social" />
    </a>
</p>

### Contents

- [Golem](#golem)
- [Apps](#%EF%B8%8F-apps)
  - [Monitoring](#Monitoring)
  - [Orchestration](#Orchestration)
  - [Docker](#Docker)
  - [Testing](#Testing)
  - [Games](#Games)
  - [Data Analysis](#Data-Analysis)
  - [Data Simulation](#Data-Simulation)
  - [Data Optimization](#Data-Optimization)
  - [Machine Learning](#Machine-learning)
  - [Deep Learning](#Deep-Learning)
  - [RNG](#RNG)
  - [Password Cracking](#Password-Cracking)
  - [DeFi](#DeFi)
  - [User Interfaces](#User-Interfaces)
  - [Miscellaneous](#Miscellaneous)
  - [Bounties and Hackathons](#bounties-and-hackathons)
- [Developer Resources](#-developer-resources)
  - [Docs and Releases](#docs-and-releases)
  - [Running a node on New Golem](#running-a-node-on-new-golem)
  - [Testnet NGNT and Ether](#testnet-ngnt-and-ether)
- [Learning Resources](#-learning-resources)
  - [Unraveling Golem’s The Next Milestone series](#unraveling-golems-the-next-milestone-series)
  - [Videos and presentations](#videos-and-presentations)
  - [GitHub Digest](#github-digest)
- [Community](#community)

# Golem

- [Golem.Network Website](https://golem.network/) - The official Golem Network website.
- [Golem Factory GitHub](https://github.com/golemfactory) - Where you can find the open source code of all things Golem!
- [Yagna GitHub](https://github.com/golemfactory/yagna) - The implementation of New Golem [![Watch on GitHub](https://img.shields.io/github/watchers/golemfactory/yagna.svg?style=social)](https://github.com/golemfactory/yagna/watchers)
[![Star on GitHub](https://img.shields.io/github/stars/golemfactory/yagna.svg?style=social)](https://github.com/golemfactory/yagna/stargazers)
- [Golem Community Chat](https://chat.golem.network/) - Join the community and team open discussion on Discord.
- [Reddit](https://reddit.com/r/GolemProject) - Golem Network discussion on the Reddit platform.
- [Twitter](https://twitter.com/golemproject) - The Golem Project Twitter.
- [Blog](http://blog.golemproject.net/) - The official blog where you can find the most reliable information on announcements, summaries and updates.

# 🖥️ Apps
- [Golem Network Video Transcoder](https://github.com/Doc-Saintly/golem-video) - This is sample app that uses golem.network to transcode videos. Please select your transcoding profile and then upload your videos.
    * **Compatibility: Alpha 2**
- [Golem Transcoding requestor](https://github.com/Edhendil/golem-transcoding) - A React + Spring based webapp accepting video files as input and transcoding these files into different formats using Golem.
    * **Compatibility: Alpha 2**
- [Golem Slate](https://github.com/deutschklub/golem-slate) - SLATE is a code pen SPA for writing a requester script to have work computed by the golem network. It utilizes dockerized yagna environments to communicate with the Golem Network in the background.
    * **Compatibility: Alpha 3**
- [Go le' Machin](https://github.com/DEUTSCHKLUB/go-le-m) - Go le’ M. is a web based bulk image editor that uses the golem network for computation. It allows users to upload multiple images and apply bulk actions to them.
    * **Compatibility: Alpha 3**
- [No more COFUD](https://github.com/DEUTSCHKLUB/no-more-COFUD) - A tool that calculates how to fit the most people into a space while keeping 2 meters distance between each other.
    * **Compatibility: Alpha 3**

## Monitoring
- [Golem Provider Terraform](https://github.com/nemani/golem-provider-terraform) - A terraform script to automatically deploy a Golem Provider on a cloud provider and setup monitoring using prometheus.
    * **Compatibility: Alpha 3**

## Orchestration
- [Golem Provider Terraform](https://github.com/nemani/golem-provider-terraform) - A terraform script to automatically deploy a Golem Provider on a cloud provider and setup monitoring using prometheus.
    * **Compatibility: Alpha 3**

## Docker
- [Golem Provider Node](https://github.com/alexandre-abrioux/golem-node) - A Docker version of a node to help you get started running as a provider in a Docker container quick. Before you start please check that `ARG YA_CORE_VERSION`, `ARG YA_WASI_VERSION` and `ARG YA_VM_VERSION` in the [Dockerfile](https://github.com/alexandre-abrioux/golem-node/blob/master/docker/Dockerfile) are the correct versions.
    * **Compatibility: Alpha 3**
- [Golem Requestor Node](https://github.com/DerekJarvis/general-golem) - A dockerized requestor environment. You can just pass in the py script  (example uses the blender demo) and it sets up the daemon and runs it
    * **Compatibility: Alpha 3**

## Testing
- [Golem Test Harness (Goth)](https://github.com/golemfactory/goth) - A tool with the purpose of speeding up your development process and making it more enjoyable for Golem app creators ([intro+demo video](https://youtu.be/HP6VVBUdkm8)).
    * **Compatibility: Alpha 3**
- [Golem Cargo Test](https://github.com/sladecek/golem_cargo_test) - Golem Cargo Test is an adaptive distributed test executor for rust projects running on the Golem network.
    * **Compatibility: Alpha 3**
- [Golem CI](https://github.com/hhio618/golem-ci) - Decentralized Task pipeline on top of the Golem Network
    * **Compatibility: Alpha 3**

## Games
- [Chess on Golem](https://github.com/broadcastmonkey/ChessOnGolem) - A react frontend for the 2 AI's playing against each other through the Golem backend, that computes each others next move.
    * **Compatibility: Alpha 3**
- [Golem Sudoku](https://github.com/Dodecane/golem-sudoku) - Game of Sudoku with size variants, powered by Golem.
    * **Compatibility: Alpha 3**
- [Magic-doll](https://github.com/bakaoh/magic-doll) - Sumer is a DeFi application that people may delegate their Splinterland card to earn passive income. It's core is [Kyle](https://github.com/bakaoh/magic-doll/tree/master/kyle), a Golem application that do all the computation to pick the best team to play for each match.
    * **Compatibility: Alpha 3**

## Data Analysis
-   [Coacervate](https://github.com/pryce-turner/coacervate/) - Coacervate is a free and open-source public good that lets you easily run genomic analyses on an extremely low-cost global supercomputer; democratizing access to the knowledge and infrastructure required to carry out groundbreaking research
- [Flan](https://github.com/nestorbonilla/flan) - A tool for entrepreneurs that provide customized analysis of millions of worldwide trade value records giving them a bold guideline about what sectors they would need to take more attention to. All computed on top of the Golem Network.
    * **Compatibility: Alpha 3**
- [Golem Lorenz-attractor](https://github.com/hhio618/golem-lorenz-attractor) - The Lorenz Equations are a system of three coupled, first-order, nonlinear differential equations which describe the trajectory of a particle through time.
    * **Compatibility: Alpha 2**
- [Golem Geomandel](https://github.com/Edhendil/golem-geomandel) - Geomandel requestor is a python script for generating sequences of Mandelbrot images centered on a single point and with zoom increasing in each image ([example](https://youtu.be/vKH7x2SrkEo)).
    * **Compatibility: Alpha 2**
- [Golem COVID](https://github.com/iRhonin/golem-covid) - This program get a parameter from data/owid-covid-data.csv file (like new_cases_per_million) and plot every day data on the world map. After all images generated (in outputs), it will gather them and create a gif ([example](https://i.imgur.com/0wtVDgx.mp4)).
    * **Compatibility: Alpha 2**
- [Golem Parallel Matplotlib](https://github.com/CoeJoder/golem-parallel-matplotlib) - Various statistical analyses are performed on circadian rhythm measurements in human test subjects.
    * **Compatibility: Alpha 2**



## Data Simulation
- [cadCAD Golem](https://github.com/rogervs/cadcadgolem) - This package is a wrapper for cadCAD to dispatch the simulation workload to multiple Golem nodes. Supports Jupyter Notebook.
    * **Compatibility: Alpha 3**
- [Golem Array](https://github.com/johngrantuk/golem-array) - Antenna Array Design & Simulation - Powered By Golem
    * **Compatibility: Alpha 3**
- [Limit visualization](https://github.com/vporton/limit-visualization) - Plot graphs on Golem with various limits. 
[Discontinous example](https://i.imgur.com/mxRDe5G.gif).
    * **Compatibility: Alpha 2**
- [golemGraphWavePair](https://github.com/smiley1983/golemGraphWavePair) - Use the Golem Network to generate graph frames, then combine them into an animation.
    * **Compatibility: Alpha 2**
- [Golemized strong-gravitational-lense](https://github.com/rezahsnz/golemized-strong-gravitational-lense) - a simple distributed computing hack that tries to simulate some physical phenomena called gravitional lensing and is based on the work of Prof. Adam Bolton.
    * **Compatibility: Alpha 2**

## Data Optimization
- [Golem or-tools](https://github.com/Doc-Saintly/golem-ortools) - Uses the or-tools Constraint Programming library to solve problems on the golem network.
    * **Compatibility: Alpha 1**
- [No more COFUD](https://github.com/DEUTSCHKLUB/no-more-COFUD) - A tool that calculates how to fit the most people into a space while keeping 2 meters distance between each other.
    * **Compatibility: Alpha 3**

## Machine Learning
- [DeML-Golem](https://github.com/anshuman73/DeML-Golem) - A Proof Of Concept of DEcentralised Machine Learning. It uses Federated Learning to combine the sub-step models it trains on different provider nodes into a full fleged model.
    * **Compatibility: Alpha 3**

## Deep Learning
- [Deepart Golem](https://github.com/echinocacti/deepart_golem) - Make art using distributed computing, running a tensorflow app and uploading your content and style picture and make the golem network process your image, doing beautiful art with style transfer and deeplearning. (POC)
    * **Compatibility: Alpha 3 (PoC)**

## RNG
- [Gandom](https://github.com/rezahsnz/gandom) - A tool that tries to extract random streams from providers on the Golem Network. It supports two PRNGs, one based on [Chaos machines](https://github.com/maciejczyzewski/libchaos) and the other that makes use of [Sodium](https://libsodium.org/).
    * **Compatibility: Alpha 3**

## Password Cracking
- [Golem-JTR](https://github.com/hhio618/golem-jtr) - Run John The Ripper on Golem Nodes to recover a password.
    * **Compatibility: Alpha 2**
- [Yacat](https://handbook.golem.network/requestor-tutorials/create-your-own-application-on-golem/the-steps-to-do) - Hashcat password-recovery example, this tutorial is designed to inspire you to create your own Golem applications, we will explain all the needed details of Golem application implementation.
    * **Compatibility: Alpha 3**

## DeFi

- [Golem Staking Pool incentivize system for GLM holders](https://github.com/masaun/GLM-stake-pool) - is a smart contract in order to provide the opportunity of yield farming for Golem's GLM token holders. (By staking uniswap-LP tokens that is a pair between GLM and ETH into the stake pool).
    * **Compatibility: Alpha 3**
- [Magic-doll](https://github.com/bakaoh/magic-doll) - Sumer is a DeFi application that people may delegate their Splinterland card to earn passive income. It's core is [Kyle](https://github.com/bakaoh/magic-doll/tree/master/kyle), a Golem application that do all the computation to pick the best team to play for each match.
    * **Compatibility: Alpha 3**

## User Interfaces

- [Golem UI](https://github.com/shri4net/golem-hackathon-2020) - A electron user interface for the Golem Network
    * **Compatibility: Alpha 3**

## Miscellaneous

- [gvm-vim](https://github.com/canokaue/gvm-vim) - A golemized docker image for compiling the most loved vim editor.
    * **Compatibility: Alpha 2**
- [YaJSapi fork with greeting example](https://github.com/rezahsnz/yajsapi) - A simple nodejs requestor app that greets you. It writes some important message to a file and then downloads it for you, the basic eskeleton of a requestor app. Look in `examples/greetings`.
    * **Compatibility: Alpha 3**
- [Golem Image Sharpening](https://github.com/visualNext/golem) - Using golem to sharpen your images
    * **Compatibility: Alpha 3**

## Bounties and Hackathons

> Details on Golem bounties and their submissions.

[Gitcoin Hackathon 2020 Winners](https://blog.golemproject.net/meet-the-winners-golem-gitcoin-hackathon-2020/)

Compile VIM On Single Golem Node - [Gitcoin link](https://gitcoin.co/issue/golemfactory/yagna/702/100023963)
 1. https://github.com/canokaue/gvm-vim - [[Demo](https://www.youtube.com/watch?v=_Of5vnffJJ0&)]
 2. https://github.com/rezahsnz/golemized-vim - [[Demo](https://youtu.be/ougeYENjLbs)]
 3. https://github.com/iRhonin/golem-vim - [[Demo](https://youtu.be/3FBqp2IiP2E)]
 4. https://github.com/thomgabriel/golem-compile-VIM - [[Demo](https://www.youtube.com/watch?v=jwXyiccyaWE)]
 5. https://github.com/molecula451/gvim - [[Demo](https://github.com/molecula451/gvim#building-docker-image)]

Process And Visualize Interesting Computations In Matplotlib On Multiple Golem Nodes - [Gitcoin link](https://gitcoin.co/issue/golemfactory/yagna/703/100023964)
 1. https://github.com/smiley1983/golemGraphWavePair - [[Demo](https://youtu.be/h_MQKBRYTPw)]
 2. https://github.com/rezahsnz/golemized-strong-gravitational-lense - [[Demo](https://youtu.be/IQ0Xz0PEWoY)]
 3. https://github.com/CoeJoder/golem-parallel-matplotlib - [[Demo](https://youtu.be/hflrBq2OXwA)]
 4. https://github.com/iRhonin/golem-covid - [[Demo](https://github.com/iRhonin/golem-covid#result])]
 5. https://github.com/hhio618/golem-lorenz-attractor - [[Demo](https://youtu.be/SPCUOPL6gqs)]
 6. https://github.com/vporton/limit-visualization - [[Demo](https://youtu.be/9mgdz6I9xHM)]

Run John The Ripper On Multiple Golem Nodes To Crack A Password - [Gitcoin link](https://gitcoin.co/issue/golemfactory/yagna/704/100023965)
 1. https://github.com/rezahsnz/golemized-john - [[Demo](https://youtu.be/L1ht9E93I_0)]
 2. https://github.com/Doc-Saintly/golem-john-jumbo - [[Demo](https://discord.com/channels/684703559954333727/756161015493951600/766647702514958366)]
 3. https://github.com/iRhonin/golem-john - [[Demo](https://youtu.be/fgBIoS9t158)]
 4. https://github.com/hhio618/golem-jtr - [[Demo](https://youtu.be/d6UIb0i9ePI)]
 5. https://github.com/molecula451/jtrg - [[Demo](https://github.com/molecula451/jtrg#building-golem-image-locally)]

Create A Video Transcoding Web Application Using Golem As A Backend - [Gitcoin link](https://gitcoin.co/issue/golemfactory/yagna/705/100023966)
 1. https://github.com/Doc-Saintly/golem-video - [[Demo](https://golem-video.jarvispowered.com:5000/static/demo.mkv)]
 2. https://github.com/Edhendil/golem-transcoding - [[Demo](https://www.youtube.com/watch?v=3koNyPvQdxA)]

# 👷 Developer Resources

### Docs and releases

- [Yagna handbook](https://handbook.golem.network/) - Handbook for the New Golem implementation, Yanga.
- [Releases List](https://github.com/golemfactory/yagna/releases) - Github releases of Yagna.

## Running a node on New Golem
> New Golem is currently running on on Rinkeby testnet.

### Requestor:
Get started quick and make your first request with the [Requestor flash tutorial](https://handbook.golem.network/requestor-tutorials/flash-tutorial-of-requestor-development).

### Provider:
Follow the [Provider section](https://handbook.golem.network/provider-tutorials/provider-tutorial) of the handbook.

## Testnet NGNT and Ether

If for any reason the faucet was unsuccessful, grab some testnet Ether via the [Rinkeby faucet](https://faucet.rinkeby.io/), send it to your node address (can be found with `yagna app-key list`, starts with "0x...") and run the payment setup command again `yagna payment init -r`.

If you have the MetaMask browser extension installed you can also try the [MetaMask faucets](https://faucet.metamask.io). Change to Rinkeby test network by clicking at the top on 'Main Ethereum Network' and select Rinkeby.

# 📝 Learning Resources

### Unraveling Golem’s The Next Milestone series

- [Unraveling Golem’s The Next Milestone](https://blog.golemproject.net/next-milestone)
- [Unraveling Golem’s The Next Milestone, Part II](https://blog.golemproject.net/next-milestone-part-ii/)
- [Unraveling Golem’s The Next Milestone, Part III](https://blog.golemproject.net/next-milestone-part-iii/)


### Videos and presentations

- [Golem x Gitcoin - Hackathon 101 (December 2020) + Alpha 3 limitations](https://www.youtube.com/watch?v=P6D5ziYcDy0&t=481s)
- [Golem Loves Layer 2 presentations and panel](https://youtu.be/B8Qu-Nofbaw) - Kuba & Mikolaj (Golem) + Panel: Jay Zhou (Loopring Protocol), Kasima Tharnpipitchai (OMG Network), Alex Gluchowski (MatterLabs), Kelvin Fichter (Optimism), Kuba Kucharski (Golem)
- [New Golem - Alpha 2 Release - Quick intro](https://youtu.be/TenOjOql5vA) - Kuba
- [New Golem - Alpha II Requestor Primer Tutorial](https://youtu.be/UHL-5QfoWmo) - Mattias
- [EDCON - Building New Golem: Where We're at and Where We're Heading](https://www.youtube.com/watch?v=FVzn1G9wtUg&feature=youtu.be&t=901) - Kuba
- [ReadyLayerOne - A Golem (R)evolution](https://youtu.be/s9WdFqLyLFo) - Piotr Janiuk


### GitHub Digest

- [Golem GitHub Digest #1](https://blog.golemproject.net/golem-github-digest-1/): Understanding the Golem Repositories
- [Golem GitHub Digest #2](https://blog.golemproject.net/golem-github-digest-2/): Diving into the Golem Repositories
- [Golem GitHub Digest #3](https://blog.golemproject.net/golem-github-digest-3/): Diving into Pull Requests of the Golem repositories
- [Golem GitHub Digest #4](https://blog.golemproject.net/golem-github-digest-4/): Diving into latest releases in the Golem repositories
- [Golem GitHub Digest #5](https://blog.golemproject.net/golem-github-digest-5/): Diving into the New Golem alpha testnet
- [Golem GitHub Digest #6](https://blog.golemproject.net/golem-github-digest-6/): SGX proof-of-concept for New Golem
- [Golem GitHub Digest #7](https://blog.golemproject.net/golem-github-digest-7/): Decentralization of the New Golem marketplace
- [Golem GitHub Digest #8](https://blog.golemproject.net/golem-github-digest-8/): Awesome Golem and next steps to Alpha 3
- [Golem GitHub Digest #9](https://blog.golemproject.net/golem-github-digest-9/): AMD provider support, network metrics and improved proposal handling
- [Golem GitHub Digest #10](https://blog.golemproject.net/golem-github-digest-10/): Improvements from community feedback
- [Golem GitHub Digest #11](https://blog.golemproject.net/golem-github-digest-11/): Easy log collection


## Community

- [Golem Community Incentives Program](https://blog.golemproject.net/community-incentives-program/) - Participate in the community and get rewarded for it in GNT!
- Community driven [Golem Network Discussion Group](https://t.me/GolemProject) Telegram channel.
