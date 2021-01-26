# Welcome to an online guide and tutorial on BitCurator.
This guide will provide resources and instructions to walk you through the installation, use, and customization of the BitCurator environment. 

The Installation page will point you to the software you need, and the steps to take to install BitCurator as a virtual machine on your computer.

The BitCurator Environment page will show you how to use various tools pre-installed in the BitCurator environment.

The Customization page will walk you through how to install new tools and software in your BitCurator environment using the Terminal.

# Running locally
- [install docker](https://docs.docker.com/engine/install/) 
- Run `docker run -i -t --rm -u 1000:1000 -p 4000:4000 -v `pwd`:/opt/app -v `pwd`/.bundler/:/opt/bundler -e BUNDLE_PATH=~/opt/bundler -w /opt/app ruby:2.7 bash -c "bundle install && bundle exec jekyll serve --watch -H 0.0.0.0"`

---
Tutorial was created using the Course-in-a-Box template, built by [Peer 2 Peer University](https://www.p2pu.org) using the [P2PU Jekyll course template](https://github.com/p2pu/jekyll-course-template) and shared under an MIT License.

Course content ("Modules") are shared under a [CC BY-SA 4.0 license](https://creativecommons.org/licenses/by-sa/4.0/).
