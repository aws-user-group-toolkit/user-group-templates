# AWS User Group Name Tag System

Welcome to the guide for implementing the AWS User Group Name Tag System at your events. This system plays a crucial role in facilitating interactions, making networking smoother, and helping everyone remember names and affiliations. This README is designed to help you, as a User Group Leader, navigate the setup and utilization of the name tag system effectively.

## Overview

The name tag system uses a specifically designed template to create uniform name tags for attendees. These tags include the AWS User Group Logo, the attendee's name, and static text indicating the meetup name. The professional look of these name tags contributes significantly to the networking experience.

### Name Tag Template

In the ```templates``` directory, you'll find the "Label-Simple.lbx" file. This template is made for DK-22205 labels, which are 62mm wide, ensuring clarity and readability.

### Printer Compatibility

Though tested with the Brother QL-720NW label printer, this template should work with any Brother label printer compatible with DK-22205 labels.

## Implementing the Name Tag System

### Preparing Name Tags

Utilizing Meetup.com CSV Export

Meetup.com offers a convenient feature to export the list of event attendees as a CSV file. This file can be directly imported into the Brother P-Touch software, allowing you to print name tags for all registered attendees efficiently.

1. **Export Attendees List:** Before your event, log in to your Meetup.com account, navigate to your event page, and export the list of attendees as a CSV file.
2. **Import to P-Touch Software:** Open the Brother P-Touch software, load the "Label-Simple.lbx" template, and import the CSV file. The software will map attendee names to the name field on the template, automating the label creation process.
3. **Customization and Printing:** Ensure the printer settings and label sizes are correctly configured in the software. Customize the template if necessary, then print a test label to verify everything looks good. Proceed to print the name tags for all attendees, preparing some extras for last-minute registrations.

### Printing and Distribution

* After preparing the name tags, set up a distribution point at the event registration area.
* Hand out the name tags as attendees arrive, encouraging them to wear them visibly.

## Additional Tips

* **Template Updates:** Keep the template current with the AWS User Group Logo and ensure the meetup name reflects the specific event.
* **Feedback Loop:** Invite feedback on the name tag system from attendees to gather suggestions for improvements.

## Feedback and Collaboration

We are always looking to improve the AWS User Group Name Tag System. Please share your experiences, suggestions, or any compatibility issues you encounter. Open an issue on our GitHub project page for any feedback you have. This collaborative effort will help us refine and perfect the name tag system for all user group leaders and attendees.

## Community Project Acknowledgment

This document is part of a suite of resources developed under a community project initiated by the AWS Meetup Vienna, Austria. It's important to note that this project is not officially affiliated with or endorsed by Amazon Web Services (AWS). This initiative represents a grassroots effort by AWS enthusiasts and community members to share knowledge, enhance meetup experiences, and foster a supportive environment for learning and networking within the AWS ecosystem. 