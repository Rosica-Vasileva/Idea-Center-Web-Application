## Part I - Idea Center Web Application

### Software Requirements

#### 1. Introduction

##### 1.1. Purpose

The purpose of this document is to describe the Idea Center application, presenting an overview of its key functionalities.

##### 1.2. Scope

This document covers high-level descriptions of the basic functionalities of the Idea Center, including user registration, login, profile editing, and idea creation and management. It excludes any special user (Administrator) functionalities.

#### 2. Overall Description

##### 2.1. System Environment

The Idea Center accommodates two primary actors: unregistered/non-logged users and registered/logged users. Both can access their respective parts of the application via the internet using the following URL:

[http://softuni-qa-loadbalancer-2137572849.eu-north-1.elb.amazonaws.com:83/](http://softuni-qa-loadbalancer-2137572849.eu-north-1.elb.amazonaws .com:83/)

##### 2.2. Key Features

- **Unregistered/Non-logged Users:**
  - Have access only to the Home page.
  - Options to "SIGN UP FOR FREE" or "SIGN IN."

- **Registered/Logged Users:**
  - Access to main functionalities, including Profile editing, Idea creation, and Idea management.

###### 2.2.1. Home Page for Unregistered/Non-Logged Users

The Home page is the main gateway into the Idea Center.

- Contains a Navigation Menu (Navbar) with "SIGN IN" and "SIGN UP FOR FREE" buttons on the left and a link back to the Home page on the right.
- Features a Carousel with three slides:
  1. "Be part of our community"
  2. "Already have an account?"
  3. "Enjoy our site!"

The slides change at random intervals, and users can manually cycle through them. Two of the slides contain call-to-action buttons prompting users to "SIGN UP FOR FREE" or "SIGN IN."

---

