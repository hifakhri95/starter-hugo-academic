---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Hardware Developer
    company: PT Lattice Teknologi Mandiri
    company_url: 'https://www.latticeman.com/'
    company_logo: ''
    location: Bandung, Indonesia
    date_start: '2020-08-20'
    date_end: '2021-08-31'
    description: |2-
        1. Developing embedded software for mechanical ventilator using eps32 micro-controller, free RTOS, and C++ language.
        2. Developing PLC software to acquire data from industrial machines/sensors, process the data, and send the data to the internet using MQTT/OPCUA protocol.
        
  - title: Embedded Software Engineer
    company: Keihin RnD Center
    company_url: ''
    company_logo: ''
    location: Tochigi, Japan
    date_start: '2018-07-01'
    date_end: '2019-12-31'
    description: 
        Part of software team which develop various BMS (battery management system) ECU function such as security function, CAN-FD communication function, and hardware check function

design:
  columns: '2'
---
