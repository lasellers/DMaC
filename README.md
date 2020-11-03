## DMaC
# Database Migrations as Code

A Python-based project that is Language neutral for doing Database Migrations as Code.
Uses YAML configuation files. SQL is in hybrid-YAML files. As a seperate repo add a module for Ansible.

The issue is this addresses is that database migrations do not fit well into the emerging gitops way of doing things.
Changes to DB schema or read-only seed data can not easily be reflected into a DB by a git commit through CI/CD.

This project flats things so that through CI changes can be make in sync to the related DBs.

# todo - under construction
