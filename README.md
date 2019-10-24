# Retail-Inventory-Control-System

This project aims to model the architecture and behavior of a retail inventory control application. It was designed using
Visual Paradigm v16.0 and uses the Unified Modeling Language (UML)

# Table of Content:

- Problem Domain
- System Structure
- System Behavior
- System Dataflow
- System User Interaction

# Problem Domain:

The architecture is designed to integrate inventory control operations. It includes a perpetual inventory system that keeps track of SKU's quantity on hand, 
and also accounts for the value of the inventory, it requests the transactions updates from the Point of Sales system and models the count assignments for employees.

# Requirements and Rules:

item rules and requirements:

- An item has to be authorized for sales
- Item can be stocked in different format such as boxes, multipack, palet, etc... which need to be accounted for in the system.
- the life of an item includes the following states: new, authorized, active, end-of-life, discontinuated. 

conting operations rules and requirements:

The system allows for:
- direct count assignments by location on the retail floor. Those counts are leading the controller through the store by a path that minimize the time it takes to complete the assignment. 
- Cycle count activities. Each item has to be counted several times a year. 
- POS exception count, when a discrepency between the perpetual record and the counted quantity occurs. Specifically exception count is trigered for Out-Of-Stock items, negative quantity of items.
- Manually requested counts.
- Accuracy counts, which can be requested tion order to monitor the items subject to loss and shrink.

The system also needs to assign priority to each count request, update these priority and also keep the items in a priority queue.

# System Structure:
A class diagram that models the structure of the system. It identifies the persistent elements, their attributes and the relation between the objects.

# System Behavior:
A serie of state diagram that are illustrating how the objects of the system are behaving. 


# System Dataflow:
Through activity diagrams, the message flow/dataflow/ workflow is represented in the system.

# System User Interaction:
Use case diagrams show how the user, whether the controller or the manager interact in the system.










