# Awesome-Infrastructure <!-- omit in toc -->

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list for awesome **Infrastructure as Data(IaD)** tools and resources inspired by [@sindresorhus' awesome](https://github.com/sindresorhus/awesome)

## What is Infrastructure as Data? <!-- omit in toc -->

**Infrastructure as Data(IaD)** is the concept of declaring the entire infrastructure of an organisation with data(i.e normally in YAML, sometimes also in JSON).
Declaring the infrastructure in a known format such as YAML helps to reduce unexpected behaviours of a system, because that file doesn't contain any specific programing language logic - you just declare what you want the infrastructure to be and you let the software do its job to ensure that what you specified becomes the actual state of the system.

Long story short - IaD is a way to declare the desired state, so the operators can make it the actual state.

## Why is this important ?

It's important because, if you keep the declaration of the infrastructure simple, engineers from different backgrounds can collaborate effectivly.
All of those declaration files, could be reviewed using a pull request.
By using this approach(also known as GitOps) everything is versioned and changes are predictable.

If you declare all the Infrastructure as Data, it would also help in Disaster Recovery(DR) and would improve the Recovery Time Objective(RTO).
The infrastructure is much more resilient, when you can simply replicate everything from the ground up - you don't need to memorise how your co-worker clicked on all of those buttons to get to the desired state.

## Tools

Here is a collection of IaD, vendor neutral and open source tools:

- [Kubernetes](https://kubernetes.io/) - Also known as K8s, is an open-source system for automating deployment, scaling, and management of containerized applications
- [Crossplane](https://crossplane.io/) - Crossplane is an open source Kubernetes add-on that enables platform teams to assemble infrastructure from multiple vendors
- ...
