# Scheduler
    
> see https://aka.ms/autorest

This is the AutoRest configuration file for Scheduler.



---
## Getting Started 
To build the SDK for Scheduler, simply [Install AutoRest](https://aka.ms/autorest/install) and in this folder, run:

> `autorest`

To see additional help and options, run:

> `autorest --help`
---

## Configuration for generating APIs


---
#### Basic Information 
These are the global settings for the Scheduler API.

``` yaml
# common 
title: Scheduler
description: Scheduler Client
api-version: 2016-03-01

```


# API Version: 2016-03-01

These settings apply only when `--api-version=2016-03-01` is specified on the command line.

``` yaml $(api-version) == '2016-03-01'
input-file:
- Microsoft.Scheduler/2016-03-01/scheduler.json

```
 
# API Version: 2016-01-01

These settings apply only when `--api-version=2016-01-01` is specified on the command line.

``` yaml $(api-version) == '2016-01-01'
input-file:
- Microsoft.Scheduler/2016-01-01/scheduler.json

```
 
# API Version: 2014-08-01-preview

These settings apply only when `--api-version=2014-08-01-preview` is specified on the command line.

``` yaml $(api-version) == '2014-08-01-preview'
input-file:
- Microsoft.Scheduler/2014-08-01-preview/scheduler.json

```


---
#### Language-specific settings: CSharp

These settings apply only when `--csharp` is specified on the command line.

``` yaml $(csharp)
csharp:
  # override the default output folder
  output-folder: $(output-folder)/csharp
```
