---
# Project Title
title: 
# Project name (shorthand)
name: "{{ upper .Name }}"

# The start and end year of this project.
# If the project is active, leave project_end empty. Otherwise, it becomes a past project.
project_start: {{ now.Format "2006" }}
project_end: 

# Research lines under which this project belongs
research_lines: []

# List of authors 
# Generates list on the associated research line
authors: []

# Responsible authors
responsible_authors: []

# Collaborators of this project
collaborators: []

# Funding of this project
funding: []
---
