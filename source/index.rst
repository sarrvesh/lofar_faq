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

How do I communicate with the LOFAR observatory?
------------------------------------------------
Communication with the LOFAR observatory is done through the RO helpdesk (i.e., JIRA ticketing system which is hosted `here <https://support.astron.nl/rohelpdesk>`_). Information about the JIRA ticketing system and a step-by-step guide on how to create and manage tickets on the RO helpdesk is explained `here <http://old.astron.nl/radio-observatory/submit-support-request/jira-ro-helpdesk-ticketing-system>`_.

How do I receive regular updates on the LOFAR telescope?
--------------------------------------------------------
To receive regular updates, you should subscribe to the lofar-news mailing list. Information on how to do so is found at this `link <https://old.astron.nl/radio-observatory/news/subscribe-lofar-news-mailing-list/subscribe-lofar-news-mailing-list>`_.

2. LOFAR User Account and LTA Access
====================================

How do I access, stage and download data from the LTA?
------------------------------------------------------
The web interface to the LTA is located at this `link <https://lta.lofar.eu/Lofar>`_. Information on how to search for and retrieve data from the LTA is in the LOFAR `wiki <https://www.astron.nl/lofarwiki/doku.php?id=public:lta_howto>`_. A LOFAR user account is not needed to browse or search for any public and proprietary data on the LTA. However, in order to be able to stage and subsequently download data from the LTA, you need a LOFAR user account with the right privileges. To set this up, you should follow the steps below:

+ First create a LOFAR user account via this `link <https://lofar.astron.nl/useradministration/public/setUpUserAccount.do>`_ 
+ Send the LOFAR observatory a request for LTA user privileges via the `RO helpdesk <https://support.astron.nl/rohelpdesk>`_. In the mail, provide the username of your account (the one you just created) and the email address used in creating the account.
+ The helpdesk will grant you the needed privileges to access the LTA and notify you via the created JIRA ticket

What do I do when I login to the LTA for the first time?
--------------------------------------------------------
When you login to the LTA for the first time after being granted access, you may need to reset your password. To reset your password, follow the procedure stated below:

+ Go to the LTA `webpage <https://lta.lofar.eu/Lofar>`_
+ Click on the LOGIN button at the top-right corner of the page
+ Click on Change Password
+ Then click on Forgotten Password 
+ And reset your Password

This procedure is necessary to properly couple the permissions of your LOFAR (MoM and Northstar) account to your LTA account.

I already have a LOFAR user account, so how come I am unable to retrieve data from the LTA?
-------------------------------------------------------------------------------------------
Note that you don't get automatic access to the data on the LTA when you create a LOFAR user account. The Observatory first needs to grant you LTA user privileges. If you already have a LOFAR user account, send us a request for LTA user privileges via the `RO helpdesk <https://support.astron.nl/rohelpdesk>`_. Make sure you provide your full name, email address and the username of your account.

Once I have been granted the needed privileges to the LTA, do I now have permission to stage and download data from any project on the LTA?
-------------------------------------------------------------------------------------------------------------------------------------------
No, with the LTA access privileges granted, you will be able to stage and download only publicly available data in the archives as well as datasets from the projects of which you are either PI or Co-I.

How do I access data from projects that have not become public yet, of which I am neither a PI or Co-I?
-------------------------------------------------------------------------------------------------------
The LOFAR Observatory can only grant you access to the data from such (proprietary or commissioning) projects with written permission from the PI. Hence, you need to seek the consent of the PI. And when the PI agrees, he/she will send an email to the Observatory to request that you should be granted permission to access the data of the particular project(s).

I selected the wrong dataset (I checked the wrong boxes) during the staging. Can I cancel the submitted staging requests from the LTA?
--------------------------------------------------------------------------------------------------------------------------------------
Yes, it is possible to abort staging jobs via the LTA python API. Please refer to the `link <https://www.astron.nl/lofarwiki/doku.php?id=public:lta_tricks>`_ for a guide on how to abort the wrongly-staged tasks. Moreover, you could allow the staging task(s) to continue, but ignore downloading the data ultimately.

Can I only find raw data in the LTA or are higher-level data products (e.g. images and catalogues) also available?
------------------------------------------------------------------------------------------------------------------
For the vast majority of imaging mode or interferometric observations, only the data products from the averaging pipeline (i.e. raw, pre-processed data) are available. The data products from the calibration, imaging and long baseline pipelines are available for a small number of projects. In the case of beamformed observations, science-ready data products from the Pulsar Pipeline (i.e. de-dispersed time series, dynamic spectra and folded pulse profiles) are available.

3. CEP3 Related (General CEP3 access requests)
==============================================

How do I access the CEP3 processing cluster for my data processing needs?
-------------------------------------------------------------------------
To get access to CEP3, a formal request must be submitted to the LOFAR observatory via the `RO helpdesk <https://support.astron.nl/rohelpdesk>`_ or be included in your observing proposal. When submitting a request, users should clearly provide the following information:

+ A brief explanation of why access to CEP3 is required (e.g. you do not have access to suitable computing resources elsewhere)
+ The project to be worked on (i.e. commissioning, cycle, processing of archived data etc.)
+ A description of the kind of processing that is needed
+ A list of collaborators (if any) who should also have access to CEP3
+ A general description of the data to be processed (e.g. data size)
+ An estimate of the processing time required

Users awarded with access to CEP3 will be able to access the cluster for a limited period of time (8 weeks by default). The awarded period starts from the moment the user’s data is copied from CEP4 (after pre-processing of the data by the LOFAR observatory) to CEP3 following the timeline communicated to the user via the observatory notification. You may refer to the `LOFAR wiki <https://www.astron.nl/lofarwiki/doku.php?id=cep3:start>`_ for more information on the CEP3 usage policy.

4. Some useful links
====================
1. `LOFAR Quick Guide <http://astron.nl/~moss/lofar/LOFARQuickStartGuide-v1.1.pdf>`_

2. LOFAR System Capabilities

    a. `LOFAR Telescope Overview <https://arxiv.org/abs/1305.3550>`_
    b. `LOFAR Array Map <https://www.astron.nl/lofartools/lofarmap.html>`_
    c. `LOFAR Stations <https://old.astron.nl/radio-observatory/astronomers/users/technical-information/lofar-stations/lofar-stations-description>`_
    d. `LOFAR Array Configuration <https://old.astron.nl/radio-observatory/astronomers/users/technical-information/lofar-array-configuration/lofar-array-conf>`_
    e. `LOFAR Signal Path <https://old.astron.nl/radio-observatory/astronomers/technical-information/lofar-signal-path/lofar-signal-path>`_
    f. `LOFAR Beam Definitions <https://old.astron.nl/radio-observatory/observing-capabilities/depth-technical-information/beam-definitions/beam-definitio>`_
    g. `Major Observing Modes <https://old.astron.nl/radio-observatory/observing-capabilities/depth-technical-information/major-observing-modes/major-obs>`_
    h. `Station Calibration Status <https://old.astron.nl/radio-observatory/astronomers/current-status>`_
    i. `LOFAR Imaging Capabilities and Sensitivity <https://old.astron.nl/radio-observatory/astronomers/lofar-imaging-capabilities-sensitivity/lofar-imaging-capabilities-and>`_
    j. `Timing Delays System History <https://old.astron.nl/radio-observatory/observing-capabilities/depth-technical-information/timing-delays-system-history/ti>`_
    k. `LOFAR Antennas <https://old.astron.nl/radio-observatory/astronomers/technical-information/antennae/antennae-description>`_
    l. `LOFAR Frequency, Subband Selection, and RFI <https://old.astron.nl/radio-observatory/astronomers/users/technical-information/frequency-selection/station-clocks-and-rcu>`_
    m. `Transient Buffer Boards <https://old.astron.nl/radio-observatory/astronomers/users/technical-information/transient-buffer-boards/transient-buffer-b>`_
    n. `LOFAR Data Archive (LTA) <https://old.astron.nl/radio-observatory/system-capabilities/depth-technical-information/lofar-data-archive/lofar-data-arch>`_
    o. `CEP and LTA Computing Facilities <https://old.astron.nl/radio-observatory/observing-capabilities/depth-technical-information/cep-and-lta-computing-facilitie>`_
    p. `Responsive Telescope <https://old.astron.nl/radio-observatory/lofar-system-capabilities/responsive-telescope/responsive-telescope>`_
    q. `Functionality Enhancements <https://old.astron.nl/radio-observatory/observing-capabilities/depth-technical-information/functionality-enhancements/func>`_
    
3. Proposing and observing tools

    a. `LOFAR Northstar Proposal Tool <https://lofar.astron.nl/proposal>`_
    b. `LOFAR Management of Measurements (MoM) <https://lofar.astron.nl/mom3>`_
    c. `Tutorial on the interpretation of system validation plots <https://old.astron.nl/radio-observatory/observing-capabilities/depth-technical-information/data-quality-inspection/data-qu>`_
    d. `XML Generator Usage <https://www.astron.nl/lofarwiki/doku.php?id=operator:xml_generator>`_
    e. `Requesting for Time <https://old.astron.nl/radio-observatory/observing/asking-time/asking-time>`_
    f. `Observing Proposal <https://old.astron.nl/radio-observatory/observing/asking-time/asking-time>`_
    g. `Observing Procedure <https://old.astron.nl/radio-observatory/observing-lofar/observing-procedure/observing-procedure>`_
    h. `Cycles Allocations and Observing Schedules <https://old.astron.nl/radio-observatory/observing/cycles-allocations-and-observing-schedules/cycles-allocations-and-observ>`_
    i. `LOFAR Data Size and Procesing Time Calculator <http://lofar.astron.nl/service/pages/storageCalculator/calculate.jsp>`_
    j. `LOFAR Frequency-to-SB converter <https://proxy.lofar.eu/rtsm/tests/>`_
    k. `LOFAR Unified Calculator for Imaging (LUCI) <https://support.astron.nl/luci/>`_
    
4. LOFAR Data Processing

    a. `Raw Data Quality Inspection <https://old.astron.nl/radio-observatory/observing-capabilities/depth-technical-information/data-quality-inspection/data-qu>`_
    b. `Software Processing Tools <https://old.astron.nl/radio-observatory/lofar-data-processing/software-processing-tools/software-processing-tools>`_
    c. `Dysco Compression <https://old.astron.nl/radio-observatory/lofar-data-processing/dysco-compression/compressing-lofar-measurement-sets-using-d>`_
    d. `Imaging Cookbook <https://support.astron.nl/LOFARImagingCookbook/>`_
    e. `Beamforming Cookbook <https://support.astron.nl/LOFARBeamformedCookbook/>`_
    
5. LOFAR Policies

    a. `The ILT Code of Conduct <https://old.astron.nl/radio-observatory/lofar-policies/ilt-code-conduct/international-lofar-telescope-code-conduct>`_
    b. `LOFAR Data Policy <https://old.astron.nl/radio-observatory/observing-proposals/lofar-data-policy/lofar-data-policy>`_
    c. `Observing and Processing Policies <https://old.astron.nl/radio-observatory/observing-capabilities/depth-technical-information/cycle-1-observing-and-processin>`_
    d. `Publications and Authorship Policy for Commissioning Papers <https://old.astron.nl/radio-observatory/astronomers/publications-and-authorship-policy/publications-and-authorship-policy>`_
    e. `CEP3 Usage Policy <https://www.astron.nl/lofarwiki/doku.php?id=cep3:start>`_
    f. `Data Products, Management, and LTA <https://old.astron.nl/radio-observatory/observing-capabilities/depth-technical-information/data-management/data-management>`_
    
6. LOFAR Science

    a. `LOFAR Science Highlights <https://old.astron.nl/radio-observatory/lofar-science/lofar-science-highlights/lofar-science-highlights>`_
    b. `LOFAR Papers and Statistics <https://old.astron.nl/radio-observatory/lofar-science/lofar-papers/lofar-papers>`_
    c. `LOFAR Slides Repository <https://www.astron.nl/LofarSlides/index.php>`_
    
7. LOFAR System Issues

    a. `LOFAR and Windfarms <https://old.astron.nl/radio-observatory/news/lofar-and-installation-nearby-windfarms-and-solar-parks/lofar-and-installatio>`_
    b. `Station Sensitivity Issue <https://old.astron.nl/radio-observatory/observing-capabilities/depth-technical-information/system-notes/station-sensitivit>`_
    c. `Wrong Information in Antenna Tables <https://old.astron.nl/radio-observatory/observing-capabilities/depth-technical-information/system-notes/wrong-information->`_
    d. `Incorrect Information About Broken Tiles <https://old.astron.nl/radio-observatory/observing-capabilities/depth-technical-information/system-notes/incorrect-informat>`_
    e. `Issue in Skymodels Created with PyBDSF <https://old.astron.nl/radio-observatory/observing-capabilities/depth-technical-information/system-notes/issue-skymodels-cr>`_
    f. `Cobalt Geographical Delay Offset <https://old.astron.nl/radio-observatory/observing-capabilities/depth-technical-information/system-notes/cobalt-geographica>`_
    g. `Faulty LBA Tables <https://old.astron.nl/radio-observatory/observing-capabilities/depth-technical-information/system-notes/faulty-lba-table-0>`_
    h. `Station Adder Correction - LB pipeline <https://old.astron.nl/radio-observatory/observing-capabilities/depth-technical-information/system-notes/station-adder-corr>`_
    i. `Wrong Position DE605 <https://old.astron.nl/radio-observatory/news/system-issues/wrong-position-de605/wrong-position-coordinates-station-de605>`_
    j. `Delay Compensation DE601 <https://old.astron.nl/radio-observatory/news/system-issues/delay-compensation-de601/delay-compensation-de601>`_
    k. `Delay Compensation Issue <https://old.astron.nl/radio-observatory/observing-capabilities/depth-technical-information/system-notes/delay-compensation>`_
    l. `WEIGHT_SPECTRUM Column issue <https://old.astron.nl/radio-observatory/observing-capabilities/depth-technical-information/system-notes/weightspectrum-col>`_
    m. `Polarization Leakage in Beamformed Data <https://old.astron.nl/radio-observatory/observing-capabilities/depth-technical-information/system-notes/polarization-leaka>`_
    n. `CASA Standards Conformity <https://old.astron.nl/radio-observatory/observing-capabilities/depth-technical-information/system-notes/casa-standards-con>`_
    o. `Inaccurate Flagging of LBA Data <https://old.astron.nl/radio-observatory/observing-capabilities/depth-technical-information/system-notes/inaccurate-flaggin>`_
    p. `Wrong Imaging Pipeline Settings <https://old.astron.nl/radio-observatory/observing-capabilities/depth-technical-information/system-notes/wrong-imaging-pipe>`_

8. Other LOFAR Resources and Information

    a. `LOFAR Activities Calendar <https://old.astron.nl/radio-observatory/news/calendar-lofar-activities/calendar-lofar-activities>`_
    b. `LOFAR Mailing List Subscription <https://old.astron.nl/radio-observatory/news/subscribe-lofar-news-mailing-list/subscribe-lofar-news-mailing-list>`_
    c. `LOFAR Newsletters <https://old.astron.nl/radio-observatory/news/lofar-newsletters/lofar-newsletters>`_
    d. `LOFAR Status Meetings (LSM) <https://old.astron.nl/radio-observatory/news/lofar-status-meetings/lofar-status-meetings>`_
    e. `ASTRON/JIVE Traineeship Programme <https://old.astron.nl/radio-observatory/news/astronjive-traineeship/astronjive-traineeship>`_
    f. `RO Helpdesk Ticket Submission Guide <https://old.astron.nl/radio-observatory/submit-support-request/jira-ro-helpdesk-ticketing-system>`_
