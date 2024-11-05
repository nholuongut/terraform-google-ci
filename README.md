### Terraform Google CI

![](https://i.imgur.com/waxVImv.png)
### [View all Roadmaps](https://github.com/nholuongut/all-roadmaps) &nbsp;&middot;&nbsp; [Best Practices](https://github.com/nholuongut/all-roadmaps/blob/main/public/best-practices/) &nbsp;&middot;&nbsp; [Questions](https://www.linkedin.com/in/nholuong/)
<br/>


We believe there is an opportunity to create a truly outstanding developer experience for deploying to the cloud, however developing this vision requires that we temporarily limit our focus to just one cloud. nholuongut has hundreds of customers currently using AWS, so we have temporarily suspended our maintenance efforts on this repo. Once we have implemented and validated our vision for the developer experience on the cloud, we look forward to picking this up. In the meantime, you are welcome to use this code in accordance with the open source license, however we will not be responding to GitHub Issues or Pull Requests.

If you wish to be the maintainer for this project, we are open to considering that. Please contact us at support@nholuongut.io

# Google CI/CD Modules

This repo contains modules and examples to deploy CI/CD pipelines on Google Cloud Platform using [Google Cloud Build](https://cloud.google.com/cloud-build/).

## Quickstart

If you want to quickly deploy an automated CI/CD pipeline using Google Cloud Build and a Google Kubernetes Engine (GKE) cluster that is triggered from a Google Cloud Source Repository, check out the [cloud-build-csr-gke example documentation](https://github.com/nholuongut/terraform-google-ci/tree/n/examples/cloud-build-csr-gke)
for instructions.

## What's in this repo

This repo has the following folder structure:

- [root](https://github.com/nholuongut/terraform-google-ci/tree/main): The root folder contains various documentation and licenses.

- [modules](https://github.com/nholuongut/terraform-google-ci/tree/main/modules): This folder contains the
  main implementation code for this Module, broken down into multiple standalone submodules.

  The primary module is:

  - [gcr-registry](https://github.com/nholuongut/terraform-google-ci/tree/main/modules/gcr-registry): The GCR Registry module is used to
    setup and configure [Google Container Registry](https://cloud.google.com/container-registry/).

- [examples](https://github.com/nholuongut/terraform-google-ci/tree/main/examples): This folder contains
  examples of how to use the submodules.

- [test](https://github.com/nholuongut/terraform-google-ci/tree/main/test): Automated tests for the submodules
  and examples.

## What is Google Cloud Build?

Cloud Build lets you build software quickly across all languages. Get complete control over defining custom workflows
for building, testing, and deploying across multiple environments such as VMs, serverless, Kubernetes, or Firebase.

## What's a Module?

A Module is a canonical, reusable, best-practices definition for how to run a single piece of infrastructure, such
as a database or server cluster. Each Module is written using a combination of [Terraform](https://www.terraform.io/)
and scripts (mostly bash) and include automated tests, documentation, and examples. It is maintained both by the open
source community and companies that provide commercial support.

Instead of figuring out the details of how to run a piece of infrastructure from scratch, you can reuse
existing code that has been proven in production. And instead of maintaining all that infrastructure code yourself,
you can leverage the work of the Module community to pick up infrastructure improvements through
a version number bump.

## Who maintains this Module?

This Module and its Submodules are maintained by [nholuongut](https://github.com/nholuongut). If you are looking for help or
commercial support, send an email to
[luongutnho@hotmail.com](mailto:luongutnho@hotmail.com).

nholuongut can help with:

- Setup, customization, and support for this Module.
- Modules and submodules for other types of infrastructure, such as VPCs, Docker clusters, databases, and continuous
  integration.
- Modules and Submodules that meet compliance requirements, such as HIPAA.
- Consulting & Training on AWS, Terraform, and DevOps.

## How do I contribute to this Module?

Contributions are very welcome! Check out the [Contribution Guidelines](https://github.com/nholuongut/terraform-google-ci/blob/main/CONTRIBUTING.md)
for instructions.

## How is this Module versioned?

This Module follows the principles of [Semantic Versioning](http://semver.org/). You can find each new release, along
with the changelog, in the [Releases Page](https://github.com/nholuongut/terraform-google-ci/releases).

During initial development, the major version will be 0 (e.g., `0.x.y`), which indicates the code does not yet have a
stable API. Once we hit `1.0.0`, we will make every effort to maintain a backwards compatible API and use the MAJOR,
MINOR, and PATCH versions on each release to indicate any incompatibilities.

![](https://i.imgur.com/waxVImv.png)
# 🚀 I'm are always open to your feedback.  Please contact as bellow information:
### [Contact Me]
* [Name: Nho Luong]
* [Skype](luongutnho_skype)
* [Github](https://github.com/nholuongut/)
* [Linkedin](https://www.linkedin.com/in/nholuong/)
* [Email Address](luongutnho@hotmail.com)
* [PayPal.me](https://www.paypal.com/paypalme/nholuongut)

![](https://i.imgur.com/waxVImv.png)
![](Donate.png)
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/nholuong)

# License
* Nho Luong (c). All Rights Reserved.🌟
