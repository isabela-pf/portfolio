# JupyterLab Design System
###### Design System, UI

![header]()

[JupyterLab](https://blog.jupyter.org/jupyterlab-is-ready-for-users-5a6f039b8906) is an open source web app made by [Project Jupyter](https://jupyter.org/) that is typically used by people practicing data science, scientific computing, and machine learning.
This is a living, interactive design system currently based on the organizing principles of [Brad Frost's *Atomic Design*](https://atomicdesign.bradfrost.com/) developed by myself and [Javier Garcia](https://javiergarcia.io/). It is constantly being used and further developed in the form of documentation and [Figma team libraries](https://www.figma.com/blog/team-libraries-in-figma/) by JupyterLab designers today.
Working on this project was also an opportunity for us to reflect on and update the existing UI, such as following appropriate [WCAG color contrast ratios](https://webaim.org/articles/contrast/) as a part of improving JupyterLab's accessibility.
![]()
## Motivation 
Even though JupyterLab is widely used, its lack of a human-readable design system was a barrier for design and development teams to work together at their best. The existing workflow required either wading through CSS and several layers of external documentation, or for the designer to disregard design system accuracy at the risk of making technically unfeasible designs.
Instead of continuing this workflow, we wanted to create a living link between JupyterLab's existing (and obscured) CSS and design tools while providing a common language that allows designers and developers to more easily collaborate.
## Improved Design Experience
![]()
The easiest way to understand the direct impact of the system is to see how quick it is to make a rough mockup from scratch using the drag-and-drop Figma components and styles our team now works with. Not only is it easy for designers to access, it still labels all elements with their appropriate CSS identifiers so that accurate information can be passed directly to the development team in the form they need to use.

![DesignFlow]()

This benefits designers because they can access the design system easier, make more accurate designs, and design faster.
This benefits developers because they are given technically feasible designs rooted in the CSS they need, can more easily follow good/existing coding practices in JupyterLab's front end, and can complete design implementation faster.This ultimately benefits JupyterLab users, as a stronger collaboration between design and development teams means that each team can spend more time doing their job well. All of this creates a better user experience.
## System in Action
The following is a sample of how the current system appears and can be used via Figma team libraries.
![gif]()

![gif]()

Below is a selection of pages from the master documents the current libraries are based on. This also serves as the place for giving designers an overview of each element's details.

![page]()
![page]()
![page]()
![page]()
![page]()
![page]()