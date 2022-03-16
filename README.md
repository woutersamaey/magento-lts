# NextMagento - A fork of OpenMage that aims to be what Magento 2 should have been
This project is a fork of OpenMage and follows what is done there, except that our aim is NOT to be a drop-in replacement for Magento 1, but a forward thinking new eCommerce platform taking the best of Magento 1 CE + the best of Magento 2 and what we have learned over +12 years of eCommerce development.

## Who is this project for?
- Developers who like Magento 1 & OpenMage, but don't like Magento 2
- Developers who want to innovate and move forward without regard for backwards-compatibility
- Developers who code everything themselves and don't need to stay compatible with module vendor X, Y and Z
- Developers who can manage the (small) changes needed to their old modules so they can keep functional
- Businesses who regret switching to Magento 2 and want the speed and lightweight nature of Magento 1 back

## Goals
- Add new, unique features that simply were never possible before because of backwards compatibility and huge impact to the module ecosystem.
- Fix a lot of the illogical things Varien / Magento did over the years.
- Over time, this project should be able to run on top of an existing Magento 2 database, making the switch easier for those who have regrets switching from Magento 1 to 2.
- Keep rebasing against OpenMage so fixes and improvements are not lost in this project.
- A new frontend and backend using the latest technologies

## Why did we fork OpenMage?
We love building on Magento 1 / OpenMage for its speed and excellent architecture, but we could not do the things we wanted to do in OpenMage as there would simply be too many breaking changes to get consensus on.
OpenMage is great as a drop-in for Magento 1, but we wanted to do much more.

## Roadmap
We have an internal roadmap with bullet points that is over 3 pages long, but we are keeping this a little secret for now.

If you have any ideas you want to share, please let us know via an issue or discussion in GitHub.

## Requirements
- PHP 7.4+
- MySQL 5.7+ (8.0+ recommended)
- Optional but recommended: Redis 6

WARNING: Please be aware that this repo is NOT a drop in replacement like OpenMage was for Magento 1. This repo will be refactored and gain new features beyond what Magento ever did.

## Installation

### Using Composer
Download the latest archive and extract it, clone the repo, or add a composer dependency to your existing project like so:

```bash
composer require "storefrontbvba/nextmage":"dev-master"
```

### Using Git

If you want to contribute to the project:

```bash
git init
git remote add origin https://github.com/<YOUR GIT USERNAME>/nextmage
git pull origin master
git remote add upstream https://github.com/storefrontbvba/nextmage
git pull upstream master
git add -A && git commit
```

## Changes
Most important changes will be listed here:

## License
- [OSL v3.0](http://opensource.org/licenses/OSL-3.0)
- [AFL v3.0](http://opensource.org/licenses/AFL-3.0)

## Contributors
This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!
