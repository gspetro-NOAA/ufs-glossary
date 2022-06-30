.. _Glossary:

Glossary
*************************

.. glossary::

   advect
      To transport substances in the atmostphere by :term:`advection`.

   advection
      According to the American Meteorological Society (AMS) `definition <https://glossary.ametsoc.org/wiki/Advection>`__, advection is "The process of transport of an atmospheric property solely by the mass motion (velocity field) of the atmosphere." In common parlance, advection is movement of atmospheric substances that are carried around by the wind.

   Authoritative Repository
      A :term:`repository` defined by the presence of a governance group and well-defined processes to manage development and periodic releases of reference versions. It exists as a definitive source for a given software development project and must contain a regression suite and documentation.

   CAPE
      Convective Available Potential Energy. 

   CCPA
      Climatology-Calibrated Precipitation Analysis (CCPA) data. This data is required for METplus precipitation verification tasks within the SRW App. The most recent 8 days worth of data are publicly available and can be accessed `here <https://ftp.ncep.noaa.gov/data/nccf/com/ccpa/prod/>`__. 

   CCPP
      The `Common Community Physics Package <https://dtcenter.org/community-code/common-community-physics-package-ccpp>`__ is a forecast-model agnostic, vetted collection of code containing atmospheric physical parameterizations and suites of parameterizations for use in Numerical Weather Prediction (NWP) along with a framework that connects the physics to the host forecast model.

   CESM
      The `Community Earth System Model <https://www.cesm.ucar.edu/>`__ is a community climate model centered at the National Center for Atmospheric Research (:term:`NCAR`). 

   chgres_cube
      The preprocessing software used to create initial and boundary condition files to "coldstart" the forecast model.

   CIME (Common Infrastructure for Modeling Earth)
      The `Common Infrastructure for Modeling Earth <https://github.com/ESMCI/cime>`__ (CIME - pronounced “SEAM”) primarily consists of a Case Control System (CCS) that supports the configuration, compilation, execution, system testing, and unit testing of an Earth System Model. The CIME CCS is used in :term:`CESM` and in the Medium-Range Weather (MRW) Application. View the CIME documentation `here <https://esmci.github.io/cime/versions/master/html/index.html>`__. 

   CIN
      Convective Inhibition.

   Code Manager
      Person responsible for managing processes and policies related to code (e.g, code reviews and updates, code tagging and releases, and documentation policies) in a component repository.

   compiler
      A program that converts instructions into a machine-code or lower-level form so that they can be read and executed by a computer.
      A compiler is a special program that translates a high-level programming language's source code into machine code, bytecode or another programming language. The source code is typically written in a high-level, human-readable language such as Java or C++. 

   Coupler
      See :term:`Mediator`.

   cron
   crontab
   cron table
      Cron is a job scheduler accessed through the command-line on UNIX-like operating systems. It is useful for automating tasks such as the ``rocotorun`` command, which launches each workflow task in the SRW App. Cron periodically checks a cron table (aka crontab) to see if any tasks are are ready to execute. If so, it runs them. 

   CRTM
      `Community Radiative Transfer Model <https://www.jcsda.org/jcsda-project-community-radiative-transfer-model>`__. CRTM is a fast and accurate radiative transfer model developed at the `Joint Center for Satellite Data Assimilation <https://www.jcsda.org/>`__ (JCSDA) in the United States. It is a sensor-based radiative transfer model and supports more than 100 sensors, including sensors on most meteorological satellites and some from other remote sensing satellites. 

   Component
      A software element that has a clear function and interface. In Earth system models, components are often single portions of the Earth system (e.g. atmosphere, ocean, or land surface) that are assembled to form a whole.

   Component Repository
      A :term:`repository` that contains, at a minimum, source code for a single component.

   Composable
      With respect to :term:`components`, capable of being assembled into a multi-component system.

   Compset
   Component set
      A component set, or compset, is group of components that together form a coupled model configuration. The term originated from the :term:`CESM` project, and it includes a list of the components in the configuration and other information.

   ..
      COMMENT: What other information?!

   Connector
      A connector is a :term:`NUOPC` Layer software component that performs one-way data communications and simple transformations, including redistribution and grid remapping.
   
   .. 
      COMMENT: Clarify/expand connector definition

   Container
      `Docker <https://www.docker.com/resources/what-container>`__ describes a container as "a standard unit of software that packages up code and all its dependencies so the application runs quickly and reliably from one computing environment to another."

   CONUS
      Continental United States

   CAM
   convection-allowing models
      Convection-allowing models (CAMs) are models that run on high-resolution grids (usually with grid spacing at 4km or less). They are able to resolve the effects of small-scale convective processes. They typically run several times a day to provide frequent forecasts (e.g., hourly or subhourly). 

   cycle
   cycles
      An hour of the day on which a forecast is started. 

   cycle-dependent 
      Describes a workflow task that needs to be run at the start of each :term:`cycle` of an experiment.
   
   cycle-independent
      Describes a workflow task that only needs to be run once per experiment, regardless of the number of cycles in the experiment.
   
   cycling
      A forecast model and data assimilation system work together to form a repeatedly "cycling" analysis and forecast system. Cycling conveys earlier information through time to the present in a model-consistent manner.
   
   ..
      COMMENT: Run cycling def by someone

   DA
   Data Assimilation
      Data assimilation is the combining of diverse data, possibly sampled at different times and intervals and different locations, into a unified and consistent description of a physical system, such as the state of the atmosphere or the Earth system.

   dycore
   dynamical core
      Global atmospheric model based on fluid dynamics principles, including Euler's equations of motion.

   ecFlow
      One of the :term:`Workflow Management System` packages used to implement scientific workflows in operational :term:`NWP` models. See the `EcFlow <https://confluence.ecmwf.int/display/ECFLOW>`__ Confluence page for more information.

   echo top
      The radar-indicated top of an area of precipitation. Specifically, it contains the height of the 18 dBZ reflectivity value.

   EMC
      The `Environmental Modeling Center <https://www.emc.ncep.noaa.gov/emc_new.php>`__ is one of :term:`NCEP`'s nine centers and leads the :term:`National Weather Service`'s modeling efforts.

   EnKF
   Ensemble Kalman Filter
      The Ensemble Kalman Filter utilizes an ensemble of forecasts to provide estimates of the background error distribution.

   ..
      COMMENT: Improve EnKF and Ensemble definitions

   Ensemble
      A collection of forecasts that are reasonably viewed as parts of a whole, e.g., by virtue of being equally probable by construction.

   ..
      COMMENT: Improve EnKF and Ensemble definitions

   EPIC
      The `Earth Prediction Innovation Center <https://epic.noaa.gov/>`__ seeks to accelerate scientific research and modeling contributions through continuous and sustained community engagement in order to produce the most accurate and reliable operational modeling system in the world. 

   ESG
      Extended Schmidt Gnomonic (ESG) grid. The ESG grid uses the map projection developed by Jim Purser of NOAA :term:`EMC` (:cite:t:`Purser_2020`). 

   ESMF
      `Earth System Modeling Framework <https://earthsystemmodeling.org/docs/release/latest/ESMF_usrdoc/>`__. The ESMF defines itself as “a suite of software tools for developing high-performance, multi-component Earth science modeling applications.” It is a community-developed software infrastructure for building and coupling models. 

   External component
      A component with a development team and authoritative code repository that is not located at NCEP/EMC.

   ..
      COMMENT: This is the UFS Comminuty definition... is it accurate for our purposes...?

   FV3
   FV3 dycore
   FV3 dynamical core
      The Finite-Volume Cubed-Sphere :term:`dynamical core` (dycore). Developed at NOAA's `Geophysical 
      Fluid Dynamics Laboratory <https://www.gfdl.noaa.gov/>`__ (GFDL), it is a scalable and flexible dycore capable of both hydrostatic and non-hydrostatic atmospheric simulations. It is the dycore used in the UFS Weather Model.

   FVCOM
      `Finite Volume Community Ocean Model <http://fvcom.smast.umassd.edu/fvcom/>`__. FVCOM is used in modeling work for the `Great Lakes Coastal Forecasting System (next-gen FVCOM) <https://www.glerl.noaa.gov/res/glcfs/>`__ conducted by the `Great Lakes Environmental Research Laboratory <https://www.glerl.noaa.gov/>`__. 

   GFS
      `Global Forecast System <https://www.ncei.noaa.gov/products/weather-climate-models/global-forecast>`__. The GFS is a National Centers for Environmental Prediction (:term:`NCEP`) weather forecast model that generates data for dozens of atmospheric and land-soil variables, including temperatures, winds, precipitation, soil moisture, and atmospheric ozone concentration. The system couples four separate models (atmosphere, ocean, land/soil, and sea ice) that work together to accurately depict weather conditions.

   GRIB2 
      The second version of the World Meterological Organization's (WMO) standard for distributing gridded data.  

   halo
      A strip of cells on the edge of the regional grid. The :ref:`wide halo <WideHalo>` surrounds the regional grid and is used to feed the lateral boundary conditions into the grid. The :ref:`HALO_BLEND <HaloBlend>` parameter refers to a strip of cells *inside* the boundary of the native grid. This halo smooths out mismatches between the external and internal solutions. 

   HPC
   HPCs
      High-Performance Computing.

   HPC-Stack
      The `HPC-Stack <https://github.com/NOAA-EMC/hpc-stack>`__ is a repository that provides a unified, shell script-based build system for building the software stack required for numerical weather prediction (NWP) tools such as the `Unified Forecast System (UFS) <https://ufscommunity.org/>`__ and the `Joint Effort for Data assimilation Integration (JEDI) <https://jointcenterforsatellitedataassimilation-jedi-docs.readthedocs-hosted.com/en/latest/>`__ framework.

   HPSS
      High Performance Storage System (HPSS).

   HRRR
      `High Resolution Rapid Refresh <https://rapidrefresh.noaa.gov/hrrr/>`__. The HRRR is a NOAA real-time 3-km resolution, hourly updated, cloud-resolving, convection-allowing atmospheric model initialized by 3km grids with 3km radar assimilation. Radar data is assimilated in the HRRR every 15 min over a 1-h period adding further detail to that provided by the hourly data assimilation from the 13km radar-enhanced Rapid Refresh.

   IC/LBC
   IC/LBCs
      Initial conditions/lateral boundary conditions

   IC
   ICs
      Initial conditions

   LAM
      Limited Area Model (grid type), formerly known as the "Stand-Alone Regional Model," or SAR. LAM grids use a regional (rather than global) configuration of the :term:`FV3` :term:`dynamical core`. 

   LBC
   LBCs
      Lateral boundary conditions

   MERRA2
      The `Modern-Era Retrospective analysis for Research and Applications, Version 2 <https://gmao.gsfc.nasa.gov/reanalysis/MERRA-2/>`__ provides satellite observation data back to 1980. According to NASA, "It was introduced to replace the original MERRA dataset because of the advances made in the assimilation system that enable assimilation of modern hyperspectral radiance and microwave observations, along with GPS-Radio Occultation datasets. It also uses NASA's ozone profile observations that began in late 2004. Additional advances in both the GEOS model and the GSI assimilation system are included in MERRA-2. Spatial resolution remains about the same (about 50 km in the latitudinal direction) as in MERRA."

   Mediator
      A mediator, sometimes called a coupler, is a software component that includes code for representing component interactions. Typical operations include merging data fields, ensuring consistent treatment of coastlines, computing fluxes, and temporal averaging.

   ..
      COMMENT: Clarify mediator definition!

   MPI
      MPI stands for Message Passing Interface. An MPI is a standardized communication system used in parallel programming. It establishes portable and efficient syntax for the exchange of messages and data between multiple processors that are used by a single computer program. An MPI is required for high-performance computing (HPC).

   MRMS
      Multi-Radar/Multi-Sensor (MRMS) System Analysis data. This data is required for METplus composite reflectivity or :term:`echo top` verification tasks within the SRW App. A two-day archive of precipitation, radar, and aviation and severe weather fields is publicly available and can be accessed `here <https://mrms.ncep.noaa.gov/data/>`__.

   NWS
   National Weather Service
      The `National Weather Service <https://www.weather.gov/>`__ (NWS) is an agency of the United States government that is tasked with providing weather forecasts, warnings of hazardous weather, and other weather-related products to organizations and the public for the purposes of protection, safety, and general information. It is a part of the National Oceanic and Atmospheric Administration (NOAA) branch of the Department of Commerce.

   NAM
   North American Mesoscale Forecast System
      `North American Mesoscale Forecast System <https://www.ncei.noaa.gov/products/weather-climate-models/north-american-mesoscale>`_. NAM generates multiple grids (or domains) of weather forecasts over the North American continent at various horizontal resolutions. Each grid contains data for dozens of weather parameters, including temperature, precipitation, lightning, and turbulent kinetic energy. NAM uses additional numerical weather models to generate high-resolution forecasts over fixed regions, and occasionally to follow significant weather events like hurricanes.

   namelist
      A namelist defines a group of variables or arrays. Namelists are an I/O feature for format-free input and output of variables by key-value assignments in FORTRAN compilers. Fortran variables can be read from and written to plain-text files in a standardised format, usually with a ``.nml`` file ending.

   NCAR
      The `National Center for Atmospheric Research <https://ncar.ucar.edu/>`__. 

   NCEP
      National Centers for Environmental Prediction (NCEP) is a branch of the :term: `National Weather Service` and consists of nine centers, including the :term:`Environmental Modeling Center`. More information can be found at https://www.ncep.noaa.gov.

   NCEPLIBS
      The software libraries created and maintained by :term:`NCEP` that are required for running 
      :term:`chgres_cube`, the UFS Weather Model, and the :term:`UPP`. They are included in the `HPC-Stack <https://github.com/NOAA-EMC/hpc-stack>`__ and in `spack-stack <https://github.com/NOAA-EMC/spack-stack>`__. 

   NCEPLIBS-external
      A collection of third-party libraries required to build :term:`NCEPLIBS`, :term:`chgres_cube`, 
      the UFS Weather Model, and the :term:`UPP`. They are included in the :term:`HPC-Stack` and in :term:`spack-stack`.  

   NCL
      An interpreted programming language designed specifically for scientific data analysis and 
      visualization. Stands for NCAR Command Language. More information can be found at https://www.ncl.ucar.edu.

   NDAS
      :term:`NAM` Data Assimilation System (NDAS) data. This data is required for METplus surface and upper-air verification tasks within the SRW App. The most recent 1-2 days worth of data are publicly available in PrepBufr format and can be accessed `here <ftp://ftpprd.ncep.noaa.gov/pub/data/nccf/com/rap/prod>`__. The most recent 8 days of data can be accessed `here <https://nomads.ncep.noaa.gov/pub/data/nccf/com/nam/prod/>`__.

   NEMS
      The NOAA Environmental Modeling System is a common modeling framework whose purpose is 
      to streamline components of operational modeling suites at :term:`NCEP`.

   NEMSIO
      A binary format for atmospheric model output from :term:`NCEP`'s Global Forecast System (:term:`GFS`).

   netCDF
      NetCDF (`Network Common Data Form <https://www.unidata.ucar.edu/software/netcdf/>`__) is a file format and community standard for storing multidimensional scientific data. It includes a set of software libraries and machine-independent data formats that support the creation, access, and sharing of array-oriented scientific data.

   NUOPC
      The `National Unified Operational Prediction Capability <https://earthsystemmodeling.org/nuopc/>`__ Layer "defines conventions and a set of generic components for building coupled models using the Earth System Modeling Framework (:term:`ESMF`)." 

   NWP
      Numerical Weather Prediction (NWP) takes current observations of weather and processes them with computer models to forecast the future state of the weather. 

   Orography
      The branch of physical geography dealing with mountains.

   Parameterization
   Parameterizations
      Simplified functions that approximate the effects of small-scale processes (e.g., microphysics, gravity wave drag) that cannot be explicitly resolved by a model grid's representation of the earth. Common categories of parameterizations include radiation, surface layer, planetary boundary layer and vertical mixing, deep and shallow cumulus, and microphysics. Parameterizations can be grouped together into physics suites (such as the :term:`CCPP` physics suites), which are sets of parameterizations known to work well together. 

   Post-processor
      Software that enhances the value of the raw forecasts produced by the modeling application to make them more useful. At :term:`NCEP`, the :term:`UPP` (Unified Post Processor) software is used to convert data from spectral to gridded format, de-stagger grids, interpolate data vertically (e.g., to isobaric levels) and horizontally (to various predefined grids), and to compute derived variables. Some types of post-processors, such as statistical post-processors, use historical information of previous runs and observations to de-bias and calibrate its output.

   RAP
      `Rapid Refresh <https://rapidrefresh.noaa.gov/>`__. The continental-scale NOAA hourly-updated assimilation/modeling system operational at NCEP. RAP covers North America and is comprised primarily of a numerical forecast model and an analysis/assimilation system to initialize that model. RAP is complemented by the higher-resolution 3km High-Resolution Rapid Refresh (:term:`HRRR`) model.

   Repository
      A central location in which files (e.g., data, code, documentation) are stored and managed. 

   Rocoto
      One of the :term:`Workflow Management System` packages used to implement scientific workflows at NOAA. Rocoto is a Ruby program that communicates with the batch system on an HPC system to run and manage dependencies between the tasks. Rocoto submits jobs to the HPC batch system as the task dependencies allow and runs one instance of the workflow for a set of user-defined cycles. See the `Rocoto Wiki <https://github.com/christopherwharrop/rocoto/wiki/documentation>` for more information.

   SDF
      Suite Definition File. An external file containing information about the construction of a physics suite. It describes the schemes that are called, in which order they are called, whether they are subcycled, and whether they are assembled into groups to be called together.

   spack-stack
      The `spack-stack <https://github.com/NOAA-EMC/spack-stack>`__ is a collaborative effort between the NOAA Environmental Modeling Center (EMC), the UCAR Joint Center for Satellite Data Assimilation (JCSDA), and the Earth Prediction Innovation Center (EPIC). *spack-stack* is a repository that provides a Spack-based method for building the software stack required for numerical weather prediction (NWP) tools such as the `Unified Forecast System (UFS) <https://ufscommunity.org/>`__ and the `Joint Effort for Data assimilation Integration (JEDI) <https://jointcenterforsatellitedataassimilation-jedi-docs.readthedocs-hosted.com/en/latest/>`__ framework. spack-stack uses the Spack package manager along with custom Spack configuration files and Python scripts to simplify installation of the libraries required to run various applications. The *spack-stack* can be installed on a range of platforms and comes pre-configured for many systems. Users can install the necessary packages for a particular application and later add the missing packages for another application without having to rebuild the entire stack.

   tracer
   tracers
      According to the American Meteorological Society (AMS) `definition <https://glossary.ametsoc.org/wiki/Tracer>`__, a tracer is "Any substance in the atmosphere that can be used to track the history [i.e., movement] of an air mass." Tracers are carried around by the motion of the atmosphere (i.e., by :term:`advection`). These substances are usually gases (e.g., water vapor, CO2), but they can also be non-gaseous (e.g., rain drops in microphysics parameterizations). In weather models, temperature (or potential temperature), absolute humidity, and radioactivity are also usually treated as tracers. According to AMS, "The main requirement for a tracer is that its lifetime be substantially longer than the transport process under study."

   UFS
   Unified Forecast System
      The Unified Forecast System (UFS) is a community-based, coupled, comprehensive Earth modeling 
      system consisting of several applications (apps). These apps span regional to global 
      domains and sub-hourly to seasonal predictive time scales. The UFS is designed to support the :term:`Weather Enterprise` and to be the source system for NOAA's operational numerical weather prediction applications. For more information, visit https://ufscommunity.org/.

   UFS App
   UFS Application
      UFS configurations that support specific predictive targets (e.g. Medium-Range Weather, Subseasonal-to-Seasonal, Space Weather) are called applications. Each application combines a numerical model, post-processing, workflow, and other elements (e.g., data assimilation). 
      
   ..
      COMMENT: UFS also adds: "Application outputs include fields of model parameters with a given spatial and temporal resolution, cadence (how often the model is run), and accuracy." But how can the output include a model parameter, which is an input? Needs clarification. 


   UFS_UTILS
      A collection of code used by multiple :term:`UFS` apps (e.g., the UFS Short-Range Weather App,
      the UFS Medium-Range Weather App). The grid, orography, surface climatology, and initial 
      and boundary condition generation code used by the UFS Short-Range Weather App is all 
      part of this collection.

   Umbrella repository
      A repository that houses external code, or "externals," which are pulled in from additional repositories during a "build" process.

   UPP
      The `Unified Post Processor <https://dtcenter.org/community-code/unified-post-processor-upp>`__ is the :term:`post processor` software developed at :term:`NCEP`. It is used operationally to 
      convert the raw output from a variety of :term:`NCEP`'s :term:`NWP` models, including the :term:`FV3 dycore`, to a more useful form.

   
   Verification
      The process of comparing forecasts to relevant observations and analyses to measure the forecast goodness.
   
   ..
      COMMENT: What does "goodness" refer to here? Statistical goodness of fit? Is there a more layman's way of explaining this?

   Weather Enterprise
      Individuals and organizations from public, private, and academic sectors that contribute to the research, development, and production of weather forecast products; primary consumers of these weather forecast products.

   Weather Model
      A prognostic model that can be used for short- and medium-range research and operational forecasts. It can be an atmosphere-only model or an atmospheric model coupled with one or more additional components, such as a wave or ocean model. 

   Workflow
      The sequence of steps required to run an experiment from start to finish. 

   Workflow component
      One of the major executables used in a prediction package such as the Short-Range Weather Application. For example, the pre-processor, data assimilation, modeling application, and post-processor executables are all workflow components.

   WMS
   Workflow Management System
      A piece of software that sets up, executes, and monitors scientific workflows. Scientific workflows are usually comprised of a set of computations, or tasks, that are driven by the availability of input data. Each task is triggered by the availability of appropriate data, and a task's result often consists of output data that is fed as input to another task in the workflow. Therefore, some tasks are dependent on the completion of others. A WMS manages these dependencies between tasks and submits new workflow tasks as the prerequisite data from previous tasks becomes available. There are two WMSs in use at NOAA, `EcFlow <https://confluence.ecmwf.int/display/ECFLOW>`__ and `Rocoto <https://github.com/christopherwharrop/rocoto>`__.
   
   




To Edit:
--------------------------------------------------

    


    mosaic files
    
    CONFIG
        An input set that fully represents an execution of an experiment. It includes the various coupled components defined in compsets and their parameterisations. This representation for running an experiment can also be used by the Front End to deliver a Job Spec for a particular experiment to run within the Workflow Environment.

    
    CROW
        The Community, Research, and Operational Workflows framework is a toolset for the new unified workflow system designed to consolidate the current multitude of different workflow systems being used at NCEP.

    Cylc
        Cylc is a general purpose workflow engine that orchestrates cycling workflows very efficiently. It was designed for production weather, climate, and environmental forecasting systems but is not specialized for those domains. It is widely used, and is the workflow engine included in CIME. See the Cylc home page.

   DA solver
      An iterative mathematical solver to compute the solution of a large-size data assimilation problem. Variational solvers use computationally efficient minimizers, while ensemble filters reduce the dimensionality of the problem through spatial localization. The output of the DA solver is an analysis increment to the model background.

    
    Forward operator
        Set of operators to simulate observations from the model fields. The forward operator may contain interpolation, radiative transfer modeling, and various other calculations. Quality control procedures involving observations and model simulated values (e.g. bias correction, cloud detection) are also involved.

    Front end
        User script that instantiates a workflow instance for execution of a specific experiment for a particular Workflow Management System (ie. Rocoto, ecFlow) for a given set of configuration inputs.

    Gatekeeper
        Person responsible for managing releases in operational and implementation branches within a UFS application umbrella repository. This person is also responsible for enforcing documentation policies and tagging the updates to the trunk of the umbrella repository during a development cycle (e.g. new microphysics).

    Hierarchical Test Framework (HTF)
        Software that supports testing of a full forecasting system like UFS from simple through complex configurations.

    Initializations
        In data assimilation, application of the analysis increment to the model background in order to produce the best initial conditions for a model forecast. This stage may involve spatial interpolation from low-resolution to high-resolution grids, 3D or 4D Incremental Analysis Update (IAU), and other techniques aiming at preserving the model internal balance.

    Job specs
        The instance of a workflow with the prescribed steps to be executed and resources to be used for a given high performance computing batch system.

    
    Model background
        Model fields, usually originating from a short-term forecast, providing the best estimate of the state of the Earth system component prior to assimilating the observations.

    Model component
        A forecast component that represents a physical domain or process, for example sea ice.

    Modeling application
        A NEMS modeling application is software that is designed for a particular forecasting purpose. It is comprised of a set of model components and NEMS coupling infrastructure, and is associated with a range of valid configurations.

    Model solver
        Dycore-specific part of the atmospheric model code that calls the dynamics and the physics driver to advance a given domain by a time step.


    NCEP Production Suite
        All codes that run in operations.

    NEMS (NOAA Environmental Modeling System)
        Software infrastructure that supports NCEP/EMC forecast products. The coupling software is based on ESMF and the NUOPC layer.

    NEMS.x
        A NEMS executable.

    NEMSIO
        A package developed at EMC to support the input/output for NEMS projects. It was designed to read and write data sets for all the NEMS atmosphere models, and supports serial and parallel I/O. The current version handles binary and GRIB1 data. There are questions about whether to add more data formats such as GRIB2 or NETCDF, or to discontinue use and move to a more widely used I/O format. See the NEMSIO User Guide for more information.

    NUOPC Layer
        The National Unified Operational Prediction Capability (NUOPC) Layer is an addition to ESMF that increases the interoperability and usability of coupled modeling systems by adding rules for how ESMF components behave. It adds to ESMF pre-fabricated modeling system components including Models for wrapping components, Drivers for sequencing them, Connectors for simple data transfers, and Mediators for more complex coupling operations such as merging fields and computing fluxes. These basic elements can be arranged in multiple ways and specialized.

    NUOPC Layer cap
        A cap is the wrapper that is written to adapt a native component interface to the NUOPC Layer interface. It includes a mapping of native data structures to ESMF data structures.

    

    Operational
        Functioning routinely with a fixed schedule and a well-defined set of deliverables, products or services .

    Physics driver
        Software used to communicate variables between an atmospheric model solver and physical parameterizations. The physics driver can be used to call a variety of physical suites, as long as all necessary variables are supplied by the solver. A physics driver is termed Interoperable when it is agnostic of the other aspects of the model and can therefore be used with a variety of dynamic cores and physics suites.

    Physical parameterization
        Code that represents one or more physical processes that force or close model dynamics. It is defined by the code implementation of the mathematical functions comprising the scheme, and not by a particular set of parameters or coefficients that could be set externally.

    Physics suite
        A set of non-redundant atmospheric physical parameterizations that have been designed or modified to work together to meet the forcing and closure requirements of a dynamical core used for a weather or climate prediction application. A set of physical parameterizations chosen to be identified as a suite results from the needs and judgment of a particular user, developer, or group of either. In some cases, a suite may be identified as a benchmark or reference set of physical parameterizations, against which variations can be tested. Since a suite can be configured in different ways for different applications by modifying its tunable parameters, an accompanying set of tunable parameters should be specified when defining a reference implementation or configuration of a physics suite.

    
    Prediction Package
        A Prediction Package consists of a sequence of jobs that together form an end-to-end forecast. rediction Packages are one of the layers described in the Unified Modeling System Architecture Overview.

    Repository
        A specific location referenced via URL or other identifier that acts as an archive with tracking capability managed through some version control system (e.g. SVN or git). A software development repository may contain source code, an integrated regression test suite/system, documentation, etc.


    Scheduler
        An HPC application service that allocates resources and manages execution of individual batch jobs in a scheduled and prioritized fashion.

    Software infrastructure
        Software infrastructure is a set of technical building blocks. The software infrastructure should be distinguished from the system architecture – the latter defines what is built; the former is a set of tools for building it.

    Stakeholders
        The collection of interested individuals and institutions that have an interest in the outcome; for coupled prediction, stakeholders include either those who have the wherewithal to contribute to system advancement, have a mandate to produce forecasts in an operational manner or have requirements for the forecasts or forecast system.

    System architecture
        The fundamental organization of a system, embodied in its components, their relationships to each other and the environment, and the principles governing its design and evolution.

   

    UFS Chemistry Transport App
        Global model for prediction of air quality and related phenomena.

    UFS Regional App
        Limited-area model based on the FV3 dynamical core, combined with suitable physical parameterizations, for undertaking detailed studies of a particular region or phenomena.

    UFS-SC (UFS Steering Committee)
        The primary governance body of the UFS.

    UFS Seasonal Prediction App
        Global coupled model, specific to the seasonal timeframes, composed of FV3 dynamical core, with appropriate physical parameterizations, coupled to MOM6, CICE5, and WaveWatch III.

    UFS system architecture
        A layered structure that is expected to encompass a workflow environment that includes a user interface and database of previous runs and verifying analyses, a prediction suite with a sequence of pre-processing, data assimilation, forecast, and post-processing components, a model application layer with a coupling framework, a prescribed interface between atmospheric physics and dynamics, model components, and scripting, and a layer of utilities and numerical libraries.

    UFS Working Group
        A group charged with advancing a particular topic area within the UFS.

    Umbrella code
        One or more configuration files that define a composite application through externals.

   