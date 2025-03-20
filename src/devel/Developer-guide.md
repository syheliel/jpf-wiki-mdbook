# Developer Guide

From the previous two sections, you have learned that JPF has one recurring, major theme: it is not a monolithic system, but rather a configured collection of components that implement different functions like state space search strategies, report generation and much more. Being adaptive is JPF's answer to the scalability problem of software model checking.

This not only makes JPF a suitable system for research, but chances are that if are you serious enough about JPF application, you sooner or later end up extending it. This section includes the following topics which describe the different mechanisms that can be used to extend JPF.

 * [Top-level design](Search-Strategies.md)
 * Key mechanisms, such as 
     - [ChoiceGenerators](ChoiceGenerators.md)
     - [Partial order reduction](Partial-Order-Reduction.md)
     - [Slot and field attributes](Slot-and-field-attributes.md)
 * Extension mechanisms, such as
     - [Listeners](Listeners.md)
     - [Search Strategies](Search-Strategies.md)
     - [Model Java Interface (MJI)](Model-Java-Interface.md)
     - [Bytecode Factories](Bytecode-Factories.md)
 * Common utility infrastructures, such as
     - [Logging system](Logging-system.md)
     - [Reporting system](Reporting-System.md)
 * [Running JPF from within your application](Running-JPF-from-application.md)
 * [Writing JPF tests](Writing-JPF-tests.md)
 * [Coding conventions](./Coding-convention.md)
 * [Hosting an Eclipse plugin update site](Host-Eclipse-plugin-update-site.md) 

