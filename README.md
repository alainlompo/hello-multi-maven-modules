# hello-multi-maven-modules

Sample multi-module spring-boot maven project configuration

## Structure

The structure looks like the following:

multi-modules
   --module-B
   --module-C
   
Which means that the parent module is called **multi-modules** and it contains two children modules: module-B and module-C. The physical structure is made to match the logical one, so that the multi-modules directory contains two sub-directories, one for each child module.

module-C contains a dependency to module-B
