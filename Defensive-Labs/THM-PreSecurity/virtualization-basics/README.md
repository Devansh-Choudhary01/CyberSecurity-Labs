Scalable systems that power the modern internet through a concept known as virtualization

**Task 2: Vitualization over**

rule of thumb in IT was: "one server = one application"

earlier, if a company wanted to run a website, a database, an email service they would need seperate physical servers for each one.

 - High Cost
 - Low utilization
 - slow deployment
 - hard to scale

A virtualization layer, called a **hypervisor** was introduced to act as a referee between lab machines and allow each virtual computer to behave independently, like a physical computer.


the analogy is that if the 10 floor building is there and a single person is living there and maintaining it which was costing him twice so he rented  different floors of the building which is exactly like Virtualization sharing the server with multiple ones which helps it making it cheaper and efficient 

This is virtualization:

• The building = the physical server

• The apartments = lab machines

• The tenants = applications or operating systems

• The building manager = the hypervisor (the software that divides the building safely)




**Task 3: Virtualization components**

A hypervisor is the core technology behind virtualization. It's the software that creates and manages lab machines.

It is a special piece of software that:

• Divides a physical computer into multiple virtual ones

• Gives each lab machine its own share of CPU, memory, and storage

• Keeps everything isolated and safe

• Manages the lifecycle of lab machines (start, stop, pause, clone, delete)



Hypervisors are of two type basically:
**Type 1**: Which directly runs on the physical hardware, making them fast, efficient, and ideal for servers

**Type 2**: which directly run within an existing operating systems, making them easier to install and ideal for learning, testing or small setups

**Lab Machines:* 

A lab machines (VM) is a virtual computer created by the hypervisor

- it has its own virtual cpu,ram,storage and network
- 
- it can run any operating system (windows, linux,etc)
- 
- its completely isolated from other VMs this means that if one vm breaks the other still continue to work
- 

**Containers:*

Container is a lightweight, isolated environment that runs a single applications and all the components to support it, basically container is where for running an application which all dependencies required its all are bundled already 

It uses hosts computer kernel to run


Containers behave like small, self-contained spaces because:

• They package the application and its dependencies (libraries, tools, versions)

• They share the host’s operating system, so they start almost instantly

• They remain isolated from each other, so a misbehaving container doesn’t affect the others

• They can run consistently on any machine, making them perfect for development, testing, and scalable deployments



The easiest way to deploy containers in a VM is using **Docker**.
Docker is an open-source software platform that simplifies the process of building, deploying, and running applications using containerization.


**Task 4: Managing Virtual Machines**

Analyzing Lab Machine StatesIn the home screen, you should see three main sections:

• Summary: Provides a generic view of the state of the environment

• Lab Machines: Provides details of each VM and enables you to run actions on them

• Hosts: Displays usage and performance details for each physical server



