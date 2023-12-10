# Adobe Sign Commons module for Mendix

This module is an extension to the [Adobe Sign Connector](https://github.com/arkani20/AdobeSignConnector) module which serves as a connector module on a rather abstract level. This module therefore provides convenient to use import and export mappings as well as plug-and-play microflows for some of the mostly used operations of the Adobe Sign API.

## Typical usage scenario

For Mendix developers seeking to enhance their Mendix applications with automated document handling and electronic signature capabilities, the Mendix connector for Adobe Sign offers a valuable solution. Note that his extension covers only covers some of the operations of the Adobe Sign API. However, you can always fall back on the Adobe Sign Connector module and make you own personalized requests using the generic microflows provided there.

## Features

- Upload transient documents
- Create and retrieve agreements
- Place form fields on agreements

## Preparation

For preparation instructions visit the [Github repository of the Adobe Sign Connector module](https://github.com/arkani20/AdobeSignConnector#preparation). This module does not require any preparation besides the one of the Adobe Sign Connector module.

## Installation

1. Install the Dependencies from the Mendix Marketplace:
   - [Adobe Sign Connector](https://marketplace.mendix.com/link/component/215590)
2. Follow the [installation instructions of the Adobe Sign Connector module](https://github.com/arkani20/AdobeSignConnector#installation)
3. Install the [Adobe Sign Commons](https://marketplace.mendix.com/link/component/215664) from the Mendix Marketplace
4. Assign the module roles to your projects user roles. Users can use the microflows provided in the USE_ME folder.

## Configuration

For configuration instructions visit the [Github repository of the Adobe Sign Connector module](https://github.com/arkani20/AdobeSignConnector#configuration). This module does not require any configuration besides the one of the Adobe Sign Connector module.

## Usage

After [preparation](#preparation), [installation](#installation) and [configuration](#configuration) you can now use the micrflows from the USE_ME package of the Adobe Sign Commons module by passing the required parameters to it.

## Help improving this package

I built this module based on my own usage of the Adobe Sign API. Please let me know if you are missing any commonly used operations of the API so I can consider adding them in a later version.
