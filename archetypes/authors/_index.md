---
# Display name
title: "{{ replace .Name "-" " " | title }}"

# Role/position (e.g., (Assistant/Associate/Full) Professor, Postdoctoral Researchers, Ph.D. Candidate)
role:

# The start and end year of being part of this group.
# If the author is an active member, leave member_end empty. Otherwise, fill in.
member_start: {{ now.Format "2006" }}
member_end: 

# Organizations/Affiliations
organizations:
  - name: "Delft University of Technology"
    url: "https://www.tudelft.nl/"
    country: "NL"

# Short bio (displayed in user profile at end of posts)
bio: >
  Example Bio
  Lorem Ipsum

# List each interest with a dash
interests:
  - Interest 1
  - Interest 2

# Social/Academic Networking
# For available icons, see: https://wowchemy.com/docs/page-builder/#icons
# For an email link, use "fas" icon pack, "envelope" icon, and a link in the
# form "mailto:your-email@example.com" or "#contact" for contact widget.
social:
  - icon: globe
    icon_pack: fas
    link: LINK-TO-PERSONAL-WEBSITE
  - icon: envelope
    icon_pack: fas
    link: '#contact'
  - icon: twitter
    icon_pack: fab
    link: https://twitter.com/USERNAME
  - icon: github
    icon_pack: fab
    link: https://github.com/USERNAME
  - icon: linkedin-in
    icon_pack: fab
    link: https://www.linkedin.com/in/USERNAME/
  - icon: google-scholar
    icon_pack: ai
    link: https://scholar.google.com/citations?user=PERSON-ID
  - icon: orcid
    icon_pack: ai
    link: https://orcid.org/ORCID-ID

# Highlight the author in author lists? (true/false)
highlight_name: true

# Organizational groups that you belong to (for People widget)
# Use one of the following values: 
#   - Full Professors
#   - Associate Professors
#   - Assistant Professors
#   - Postdoctoral Researchers
#   - Ph.D. Candidates
#   - Lecturers
#   - Scientific Developers
#   - Guests
#   - Support
user_groups:
  - Group 1
  - Group 2
---
