# Software Development Process(SDP)

**Authors:** Jake Goodwin,

**DATE:** 2023-11-16


# Principles

# Process

## Steps in software development

1. 

## Goals & Objectives

## Project Scope

- Design of simple UI to display data.
- Design of hardware/schematics for system.
- Firmware for sensor modules in rust.
- SBC with rust software to store/log sensor data over CAN.


# Roles

| ROLE         | PERSON       | RESPONSIBILITIES                                |
| ------------ | ------------ | ----------------------------------             |
| UI           | Blake        |                                                |
| SBC/SW       | Aidian       |                                                |
| FIRMWARE     | Patrick      |                                                |
| HARDWARE     | Jake         | design schematics, wiring diagrams & PCB files |

These are the general outlines for the four different roles in the project. We 
have a verbal agreement at the moment that we will help out with parts of the
project outside our roles as needed.

# Tooling

| Purpose            | Name                |
| ------------------ | -------------       |
| Version Control    | Git                 |
| Project Management   | GitHub Projects     |
| Documentation      | Rustdocs & MD       |
| Test framework     | Rust & Cmocka       |
| Editor             | ANY                 |
| Schematics & PCB   | KiCAD               |
| Communication       | Discord/Teams/Email |
|                    |                     |

## Version Control

Git will allow our team to track changes in the projects files over time. Also
prevents the loss of work from hardware failures.

## Project Management

GitHub projects is integrated into github organizations as well as git. The 
project management software makes the collaboration between developers easy and
will make tracking milestones and issues  for the entire project across
multiple repositories a possibility.

## Documentation

Documentation will primaily be done through the built-in rust-docs feature. 
This is accesiable via the CLI(command line interface) tooling. This will 
encapsulate how the code itself and any interfaces are documented.

Because the documentation is genreated as part of the code this will ensure 
that up to date and accurate documentatio is always availble.

Secondary documentation meant for non-developers will be done using a combination
of markdown and LaTex where needed. This will be availble usally in a PDF format.



## Test Frameworks

## Schematics & PCB

The KiCAD program gives access to the schematics and PCB designs to all team 
members due to the software begin free and open-source.

It will allow us to comment, label and design the needed circuits for the
physical hardware of the system; providing a good troubleshooting resource as
well.

## Communication



# Definition of Done(DOD)

## TESTING

**Rust:**

The testing for all code repositories will be done using a testing harness
or framework. For rust this takes the form of the `cargo test` command, which
is part of the package managment system(tool-chain).

These tests will be used as one of acceptance critera for a branch to be pulled
into the main branch.

**C:**

Some libraries or areas where the use of C code is needed we plan to use 
cmocka as the unit testing framework. This combined with Cmake as the build 
system will give us a host agnostic development cycle.


### Quality Assurance

Quality assurance will mostly be handled by adhearance to style standards
enforced by the lanuages LSP(language server protocol) servers. The two that
will see extensive use in this project being:

1. Rust-analyzer
2. clangd

### Feedback

Feedback on the work done will take place in the github projects. The issues
and discussion boards are the main locations for this, with the weekly meetings
and discord being a secondary and informal medium for minor feedback.


# Release Cycle

For the moment we will used semantic versioning with the standard
Major.minor.patch format. This will help when it comes to dealing
with any major changes that break APIs.

## Contingency Plans


# Timeline



# Environments