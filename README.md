<p>
  <img align="left" src="https://github.com/herasymj/Health-Esteem/raw/Milestone1/assets/uofr_logo.jpg" alt="U of R logo" width="39.055%"/>
  <img align="right" src="https://github.com/herasymj/Health-Esteem/raw/Milestone1/assets/ehealth_logo.png" alt="eHealth logo" width="27.5%"/>
</p>

<br/><br/><br/><br/>

# Health-Esteem
Based on https://github.com/rstancu/braintrust

Health-Esteem provides an idea mangagement system for interorganizational improvement.

### Contributors: 
* Quinn Bast
* Shawn Clake
* Tristan Heisler
* Jennifer Herasymuik
* Chengyu Lou
* Wilson Nie

### Documentation
* [User Manual](https://github.com/herasymj/Health-Esteem/blob/master/documentation/User%20Manual.pdf)
* [Anonymized Usability Report](https://github.com/herasymj/Health-Esteem/blob/master/documentation/Usability%20Analysis%20Report.pdf)
* [Google Drive (Planning, Presentations in progress, Meeting notes)](https://drive.google.com/drive/folders/1xXZoQ2bTMq2rhHzLl4sXl5ZG7T7oY1FZ?usp=sharing)
* [Requirements](https://github.com/herasymj/Health-Esteem/blob/master/documentation/requirements.md)
* [Discussion](https://github.com/herasymj/Health-Esteem/blob/master/documentation/discussions.md)

### Setup Guide
1. Clone down this repository and modify any configurations necessary
    * ie. The database the app will talk to
    * ie. Production vs Development environment
2. Run a `upgrade-database` command using .NET CLI
3. Login with the default administrator account and change the password. By default it is: `Abc123!`
    * Use this account to set other users roles in the future

## Archived Readme from Braintrust's repository

### Braintrust

**Contributors:** Reid Stancu, Simranjeet Kaur, Susmita Patel

Repository for Team Braintrust's eIDEAS project (ENSE 885AS Spring/Summer 2018).

Documents:

* [Requirements](https://github.com/rstancu/braintrust/blob/master/requirements.md)
* [Discussion](https://github.com/rstancu/braintrust/blob/master/discussions.md)
* [Usability Report](https://github.com/rstancu/braintrust/raw/master/Lo-Fi%20Usability%20Evaluation/milestone3_usability_report.pdf)
* Latest Mockups: \[[Balsamiq File (.bmpr)](https://github.com/rstancu/braintrust/raw/master/mockups/eideas.bmpr)\], \[[PDF - clean](https://github.com/rstancu/braintrust/raw/master/mockups/eideas.pdf)\] , \[[PDF - with linking hints](https://github.com/rstancu/braintrust/raw/master/mockups/eideas_with_link_hints.pdf)\]

**About this Project**

The eIDEAS project was requested by eHealth with the goal to improve the quality of healthcare across the province of Saskatchewan. This follows the organization's ongoing efforts to foster an internal culture of innovation. Using Plan, Do, Evaluate, Adapt (PDEA) cycles the goal is to improve quality, cost, delivery, safety, and engagement (QCDSE).

These goals are accomplished by providing an application for employees to submit ideas for improving existing organizational processes. This increases visibility of individual and collaborative work.

This project has been signed/approved by eHealth Saskatchewan and the University of Regina.

**Info for Newcomers**

The discussion document is a good place to start in order to become familiar with the project. We recommend flipping between both the [discussion](./discussions.md) and [requirements](./requirements.md) documents as needed, since they frequently reference each other.

For usability analysis, readers can browse the various documents inside the [`Lo-Fi Usability Evaluation`](./Lo-Fi%20Usability%20Evaluation/) folder. Alternatively, the [Usability Report](./Lo-Fi%20Usability%20Evaluation/milestone3_usability_report.pdf) provides a good summary of our findings. Please note that the usability evaluation took place on June 6th, 2018 and we have made significant updates since then. To see the repository as it was during the evaluation click [here](https://github.com/rstancu/braintrust/tree/7920cbf20be68881166602534009c68aa3ea995a).

In order to achieve a good understanding of the application flow, we recommend using the Balsamiq project file. Open [`eideas.bmpr`](./mockups/eideas.bmpr) in Balsamiq and select Full Screen Presentation (or press `CTRL+F`). Balsamiq can be used via the [cloud](https://balsamiq.cloud/), or it can be downloaded [here](https://balsamiq.com/download/).

Alternatively, we provide two PDF options. Both are fully interactive with clickable elements:

* [PDF - clean](./mockups/eideas.pdf) (no hints --- use this option to view the application as intended)
* [PDF - with linking hints](./mockups/eideas_with_link_hints.pdf) (hints --- this option displays all clickable elements and links in red)

We recommend going through the PDF with hints first, then switch to the clean (no hints) version once the interface is familiar.

