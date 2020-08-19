.. LOFAR FAQ documentation master file, created by
   sphinx-quickstart on Wed Aug 19 09:13:49 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to LOFAR FAQ's documentation!
=====================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:

1. General information and enquiry
==================================

1. 1. How do I communicate with the LOFAR observatory?
------------------------------------------------------
Communication with the LOFAR observatory is done through the RO helpdesk (i.e., JIRA ticketing system which is hosted `here <https://support.astron.nl/rohelpdesk>`_). Information about the JIRA ticketing system and a step-by-step guide on how to create and manage tickets on the RO helpdesk is explained `here <http://old.astron.nl/radio-observatory/submit-support-request/jira-ro-helpdesk-ticketing-system>`_.

1. 2. How do I receive regular updates on the LOFAR telescope?
--------------------------------------------------------------
To receive regular updates, you should subscribe to the lofar-news mailing list. Information on how to do so is found at this `link <https://old.astron.nl/radio-observatory/news/subscribe-lofar-news-mailing-list/subscribe-lofar-news-mailing-list>`_.

2. LOFAR User Account and LTA Access
====================================

2. 1. How do I access, stage and download data from the LTA?
------------------------------------------------------------
The web interface to the LTA is located at this `link <https://lta.lofar.eu/Lofar>`_. Information on how to search for and retrieve data from the LTA is in the LOFAR `wiki <https://www.astron.nl/lofarwiki/doku.php?id=public:lta_howto>`_. A LOFAR user account is not needed to browse or search for any public and proprietary data on the LTA. However, in order to be able to stage and subsequently download data from the LTA, you need a LOFAR user account with the right privileges. To set this up, you should follow the steps below:

+ First create a LOFAR user account via this `link <https://lofar.astron.nl/useradministration/public/setUpUserAccount.do>`_ 
+ Send the LOFAR observatory a request for LTA user privileges via the `RO helpdesk <https://support.astron.nl/rohelpdesk>`_. In the mail, provide the username of your account (the one you just created) and the email address used in creating the account.
+ The helpdesk will grant you the needed privileges to access the LTA and notify you via the created JIRA ticket

2. 2. What do I do when I login to the LTA for the first time?
--------------------------------------------------------------
When you login to the LTA for the first time after being granted access, you may need to reset your password. To reset your password, follow the procedure stated below:

+ Go to the LTA `webpage <https://lta.lofar.eu/Lofar>`_
+ Click on the LOGIN button at the top-right corner of the page
+ Click on Change Password
+ Then click on Forgotten Password 
+ And reset your Password

This procedure is necessary to properly couple the permissions of your LOFAR (MoM and Northstar) account to your LTA account.

2. 3. I already have a LOFAR user account, so how come I am unable to retrieve data from the LTA?
-------------------------------------------------------------------------------------------------
Note that you don't get automatic access to the data on the LTA when you create a LOFAR user account. The Observatory first needs to grant you LTA user privileges. If you already have a LOFAR user account, send us a request for LTA user privileges via the `RO helpdesk <https://support.astron.nl/rohelpdesk>`_. Make sure you provide your full name, email address and the username of your account.

2. 4. Once I have been granted the needed privileges to the LTA, do I now have permission to stage and download data from any project on the LTA?
-------------------------------------------------------------------------------------------------------------------------------------------------
No, with the LTA access privileges granted, you will be able to stage and download only publicly available data in the archives as well as datasets from the projects of which you are either PI or Co-I.

2. 5. How do I access data from projects that have not become public yet, of which I am neither a PI or Co-I?
-------------------------------------------------------------------------------------------------------------
The LOFAR Observatory can only grant you access to the data from such (proprietary or commissioning) projects with written permission from the PI. Hence, you need to seek the consent of the PI. And when the PI agrees, he/she will send an email to the Observatory to request that you should be granted permission to access the data of the particular project(s).

2. 6. I selected the wrong dataset (I checked the wrong boxes) during the staging. Can I cancel the submitted staging requests from the LTA?
--------------------------------------------------------------------------------------------------------------------------------------------
Yes, it is possible to abort staging jobs via the LTA python API. Please refer to the `link <https://www.astron.nl/lofarwiki/doku.php?id=public:lta_tricks>`_ for a guide on how to abort the wrongly-staged tasks. Moreover, you could allow the staging task(s) to continue, but ignore downloading the data ultimately.

2. 7. Can I only find raw data in the LTA or are higher-level data products (e.g. images and catalogues) also available?
------------------------------------------------------------------------------------------------------------------------
For the vast majority of imaging mode or interferometric observations, only the data products from the averaging pipeline (i.e. raw, pre-processed data) are available. The data products from the calibration, imaging and long baseline pipelines are available for a small number of projects. In the case of beamformed observations, science-ready data products from the Pulsar Pipeline (i.e. de-dispersed time series, dynamic spectra and folded pulse profiles) are available.

3. CEP3 Related (General CEP3 access requests)
==============================================
3. 1. How do I access the CEP3 processing cluster for my data processing needs?
-------------------------------------------------------------------------------
To get access to CEP3, a formal request must be submitted to the LOFAR observatory via the `RO helpdesk <https://support.astron.nl/rohelpdesk>`_ or be included in your observing proposal. When submitting a request, users should clearly provide the following information:

+ A brief explanation of why access to CEP3 is required (e.g. you do not have access to suitable computing resources elsewhere)
+ The project to be worked on (i.e. commissioning, cycle, processing of archived data etc.)
+ A description of the kind of processing that is needed
+ A list of collaborators (if any) who should also have access to CEP3
+ A general description of the data to be processed (e.g. data size)
+ An estimate of the processing time required

Users awarded with access to CEP3 will be able to access the cluster for a limited period of time (8 weeks by default). The awarded period starts from the moment the user’s data is copied from CEP4 (after pre-processing of the data by the LOFAR observatory) to CEP3 following the timeline communicated to the user via the observatory notification. You may refer to the `LOFAR wiki <https://www.astron.nl/lofarwiki/doku.php?id=cep3:start>`_ for more information on the CEP3 usage policy.
