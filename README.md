# Introduction to the Struts 2 Framework Through Examples (2012)

🔗 **Online Course:**
[https://stahe.github.io/en-struts2-janv-2012/](https://stahe.github.io/en-struts2-janv-2012/)

---

## Overview

This document provides an **introduction to the Struts 2 framework** through a step-by-step approach based on examples.

Struts 2 is a Java web framework that provides:

* a set of libraries distributed as **JAR** files
* a development framework that structures the way a web application is designed

The goal is to understand the fundamental concepts of Struts 2 through hands-on practice.

---

## Prerequisites

To follow the examples, you need:

* basic knowledge of **Java**
* basic knowledge of **web development**, particularly **HTML**

Additional resources are available at:

* [http://developpez.com](http://developpez.com)
* [http://tahe.developpez.com](http://tahe.developpez.com)

---

## Further Reading

To learn more:

* **[ref1]** Official Struts 2 Documentation (official project website)
* **[ref2]** *Struts 2 in Action*
  Donald Brown – Chad Michael Davis – Scott Stanlick
  Manning Publications

The document occasionally references *Struts 2 in Action* to explore certain technical aspects in greater depth.

---

## Educational Objective

This document has been written so that it can be read without a computer.
Numerous screenshots are included to aid understanding.

---

## Struts 2’s Role in a Web Application

Struts 2 operates **exclusively within the web layer** of a typical multi-layer architecture.

### General Architecture

A typical web application can be structured as follows:

### 1️⃣ Web Layer

* User interface (browser)
* Handling HTTP requests
* Generating responses
* **Struts 2 resides exclusively in this layer**

### 2️⃣ Business Layer

* Implements business rules
* Example: calculating a salary, generating an invoice
* Uses:

  * data from the web layer
  * data from the database via the DAO layer

### 3️⃣ DAO / JPA / JDBC Layer

* Data access management
* DAO: Data Access Objects
* JPA: Java Persistence API
* JDBC: low-level database access
* JPA acts as an ORM (Object Relational Mapper)

### 4️⃣ Layer Integration

Can be provided by:

* **Spring**
* **EJB3 (Enterprise Java Bean)**

---

## Organization of Examples

Most of the examples in this document use **only the Web layer** to focus on Struts 2.

At the end of the document, a **complete multi-layer web application** is built:

* Web layer
* Business layer
* DAO layer
* JPA / Hibernate layer
* Database access via JDBC

The business and persistence layers are provided as JAR archives so that the reader can focus primarily on the Web layer.

---

## Target Audience

* Java developers wishing to learn Struts 2
* Students of Java web development
* Anyone wishing to understand the integration of Struts 2 into a multi-layer architecture

---

## Author

Serge Tahé: Course originally published on developpez.com
2012 version

---
