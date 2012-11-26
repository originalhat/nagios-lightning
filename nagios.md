# nagios lightning

- field catalog monitoring with nagios

## Monitoring the Field Catalog

- large quantities of data
- cannot be checked manually (perfect job for a box)
- increased data quality and reliability
- three categories that 'monitoring' defines here
  - general services
  - incoming file streams
  - whole datasets
- the **catalog nagios** project handles all three

## Features

### 1. general monitoring

- support services relating to the field catalog
- non-products
- required for the "system" to work as a whole
  - checking disks
  - accessibility of machines
  - http requests

### 2. check file-feed(s)

- determines the age of the most recent file in a specified location
- these are specific locations that we wish to check
- highly configurable in terms of 

### 3. check dataset(s)

- determine the age of the most recent file for a 

### 4. configuration

- it's important to have these checking mechanisms
- what we really need is an easy way to configure
- products and contacts are easily configured

## implementation

- (technology involved)
- (fairly straighforward)

## challenges

- all major problems have their origin w/ time
  - quickly checking large file systems
  - dealing with different time zones

## Acknowledgements

- Erik Johnson: building, and guiding vision of app
- Greg Stossmeister: creating test streams
- John Allison: database creation?
- SIG: *Doppler*