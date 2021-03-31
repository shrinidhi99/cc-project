# Different VM Migration Techniques
## Introduction
Datacenter virtualization technologies have attracted a lot of attention to enable various cloud computing services and to facilitate virtual machine (VM) migration. In order to ensure the Quality of Service, the migration time and the downtime of VM should be considered while implementing the VM migration. VM migration mechanisms can be divided into two categories. One is the traditional offline migration mechanism. This migration mechanism has to first stop the currently running VMs, and then migrate the virtual machine’s memory and status, and finally restart the virtual machine at the new destination server. The other is online or live migration mechanism. In the offline migration process, the services being provided will be terminated while migrating the VM. Whereas the live migration mechanism can keep the services running without interruption during most of the migration process.
The main contribution of the paper under consideration is that it proposes two new migration strategies for multiple live VM migrations. This paper proposes an improved serial migration strategy and introduces the post-copy migration scheme into it. We then propose the ‘m-mixed migration strategy’ that is based on the improved serial migration strategy and the parallel migration strategy.


## Features

- Ability to run serial migration 
- Ability to run improved serial migration 
- Ability to run parallel migration 
- Ability to run m-mixed migration 
- Ability to compute downtime and migration time of the above migration methods
- Ability to vary parameter such as percentage of memory to migrate, dirtying rate etc. 

## Tech
- CloudSimplus
- Matplotlib to create graphs
- VScode

## Installation

- Our project requires [CloudSimPlus](https://github.com/manoelcampos/cloudsim-plus) to run. Refer the CloudSimplus README to install the required Dependencies
- Install VScode 
- Unzip the folder
- Copy `SerialMigration.java`,`ImprovedSerialMigration.java`,`ParallelMigration.java`,`mMixedMigration.java` into `/cloudsim-plus-examples/src/main/java/org/cloudsimplus/examples/migration/`

- Copy 

    `DatacenterParallel` into `/cloudsim-plus/src/main/java/org/cloudbus/cloudsim/datacenters/`
- Open the modified cloudsimplus directory using VScode
- To run serial migration run `SerialMigration.java` 
- To run improved serial migration run `ImprovedSerialMigration.java` 
- To run parallel migration run `ParallelMigration.java` 
- To run m-mixed migration run `mMixedMigration.java` 

## GitHub Project Repository

[GitHub Repository](https://github.com/shrinidhi99/cc-project.git)

## Authors
* Avakash Bhat 171CO110

* Akshit Patel 171CO129

* Shrinidhi Anil Varna 171CO145

* Vybhav Pai 171CO252
