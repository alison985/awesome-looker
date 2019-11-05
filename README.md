# awesome-looker
A list/directory of awesome/helpful Looker and LookML work.

Currently the criteria to be "awesome" is to be public on Github or Gitlab, or on Looker's discourse or Looker.com, maintained, and not deprecated. Individual LookML project repos do not qualify but specific file(s) highlighting cool design patterns or code hacks may be featured. 

The following tags are included throughout the page to make it easy to search.

* _Language_ #python | #CICD | #PHP | #json | #node (yes technically it's javascript, but it's a specific type of javascript)
* _Creator_ #fromlooker | #frompipeline | #fromheap | #fromsegment | #fromsnowplow | #fromgdxanalytics | #frombrechtv | #fromheyjobs | #fromdatarobot | #fromleighajarett | #fromcaura
* _Database Dialect_ #dialectredshift | #dialectsnowflake | #dialecctbigquery
* _Modeling_ #EAV
* Forks are indicated with (fork).

## Table of Contents
* [Blocks by Data Source](#blocks-by-data-source)
* [Custom Visualizations](#custom-visualizations)
* [Integrations](#integrations)
* [Internal Applications](#internal-applications)
* [External Applications](#external-applications)
* [Dev Tools](#dev-tools)

## Blocks by Data Source
### AWS
* [GDX Analytics Looker AWS Cost and Usage](https://github.com/bcgov/GDX-Analytics-Looker-AWS-Cost-And-Usage)  The GDX Analytics LookML project to monitor cost and usage of AWS #fromgdxanalytics
* [AWS DataLake Quickstart Looker ISV integration](https://github.com/pogaku9/aws-datalake-quickstart-looker-isv-integration) AWS data Lake Quick Start - ISV partner Looker Integration 
### Facebook Ads
* [pipeline-looker-blocks/facebooksads](https://github.com/pipeline-looker-blocks/facebookads) LookML files for a Facebook block compatible with Pipeline's schema #frompipeline
### Google Adwords
* [google adwords](https://github.com/heyjobs/google_adwords) (fork) #fromheyjobs
### Heap
* [looker_user_journey_map](https://github.com/heap/looker_user_journey_map) lookML block for user journeys based on events #fromheap
* [heap-looker-block-merchandising](https://github.com/heap/heap-looker-block-merchandising)  #fromheap
* [heap-looker-block-overview](https://github.com/heap/heap-looker-block-overview)  #fromheap
* [heap-looker-user-journey-map](https://github.com/heap/looker_user_journey_map) #fromheap
### Mixpanel
* [Mixpanel block](https://github.com/caura/mixpanel) #fromcaura
### Redshift
* [Looker_SystemStats](https://github.com/dovicn/Looker_SystemStats) Lookml definition for System Stats retrieval from Redshift.
* [GDX Analytics Looker Redshift Admin by AWS](https://github.com/bcgov/GDX-Analytics-Looker-Redshift_Admin_By_AWS) The GDX Analytics LookML project for Redshift Admin by AWS  #fromgdxanalytics
* [blocks_redshift_admin](https://github.com/heyjobs/blocks_redshift_admin) (fork) #fromheyjobs
### Salesforce
* [Salesforce by Segment](https://github.com/llooker/salesforce_by_segment) A LookML block for Salesforce data ETL'd by Segment #fromsegment
* [pipeline-looker-blocks/salesforce](https://github.com/pipeline-looker-blocks/salesforce)  LookML files for a Salesforce block compatible with Pipeline's schema #frompipeline
* [causa salesforce](https://github.com/caura/salesforce) generic LookML model for salesforce dataset #fromcaura
* [Salesforce block](https://github.com/seanlhiggins/salesforce_block) Salesforce Block Converted to New LookML and for BigQuery #dialectbigquery
### Snowflake
* [Zero to Snowflake](https://github.com/DecisiveData/ZeroToSnowflake) Code repository for Zero to Snowflake events  
### Snowplow
* [snowplow-looker-demo](https://github.com/snowplow/snowplow-looker-demo) LookML for the Snowplow Looker demo #fromsnowplow
* [snowplow-basic-demo-lookml](https://github.com/snowplow/snowplow-basic-demo-lookml) LookML for the basic Snowplow Looker demo #fromsnowplow
* [snowplow-full-demo-lookml](https://github.com/snowplow/snowplow-full-demo-lookml) #fromsnowplow
* [GDX Analytics Looker Snowplow Web Block](https://github.com/bcgov/GDX-Analytics-Looker-Snowplow-Web-Block) The GDX Analytics LookML project for Snowplow derived analytics #fromgdxanalytics
* [snowplow-web-data-model](https://github.com/snowplow/snowplow-web-data-model) SQL data model for working with Snowplow web data. Supports Redshift and Looker. Snowflake and BigQuery coming soon #dialectredshift
### Stripe
* [Stripe](https://github.com/pipeline-looker-blocks/stripe) LookML files for a Stripe block compatible with Pipeline's schema #frompipeline 
### Zendesk
* [zendesk](https://github.com/pipeline-looker-blocks/zendesk) LookML files for a Zendesk block compatible with Pipeline's schema #frompipeline

## Custom Visualizations
* [looker_custom_viz](https://github.com/epschroeder/looker_custom_viz) Custom visualizations for Looker

## Integrations
### Slack
* [lookerbot](https://github.com/looker/lookerbot) Lookerbot lets you access all your Looker data from Slack! Super fun! https://looker.com/lookerbot #fromlooker

## Internal Applications

## External Applications
* [LookML Python Data Dictionary](https://github.com/leighajarett/LookML_Python_Data_Dictionary) This repo has the Python and LookML code for generating a data dictionary in your Looker Instance #python #fromleighajarett

### Dev Tools
#### API
* [Looker > lookml](https://github.com/llooker/lookml) This is a pythonic api for creating LookML objects. #python #fromlooker
* [pylooker](https://github.com/bufferapp/pylooker) A Python interface to Looker API 
* [looker google sheets](https://github.com/brechtv/looker_google_sheets) Custom Google Spreadsheet functions using the Looker API  #frombrechtv

#### Housekeeping
* [Gazetteer](https://github.com/mathilda0902/gazetteer) Looker Dependency Graphs: getting around business queries as easily as your backyard.  #dialect-snowflake
* [LookML Dependencies Tracer](https://github.com/leighajarett/LookML-Dependencies-Tracer) Contains a Python3 Jupyter Notebook which uses the LookerAPI to parse through the specified LookML model and results in a relational CSV file. #python #fromleighajarett

#### Linter
* [lookml-tools](https://github.com/ww-tech/lookml-tools) Tools to handle best practices for LookML dev. Contains three tools: LookML updater, linter, and grapher #python
* [lookmllint](https://github.com/WarbyParker/lookmlint) Linting tool for LookML #python
* [look-at-me-sideways](https://github.com/looker-open-source/look-at-me-sideways) A judgmental little LookML linter >_>  #fromlooker

### Looker Actions
* [looker-data-actions](https://github.com/bufferapp/looker-data-actions) Set of Looker Data Actions to perform tasks in other tools from directly within Looker. 
* [Action Hub fork](https://github.com/datarobot/actions) A public fork of the official Looker Action Hub. (fork) #fromdatarobot

### LookML Generator
* [lookml-gen](https://github.com/symphonyrm/lookml-gen) Generate LookML with Python code #python
* [lookmlscript](https://github.com/llooker/lookmlscript) LookML Generator for Python  #python #fromlooker
* [lookmlphp](https://github.com/ethosce/lookmlphp) Write LookML with PHP #PHP
* [JSON to LookML](https://github.com/leighajarett/JSON_to_LookML) This script creates a LookML view file, and pushes it to production, that parses JSON fields into separate dimensions  #python #json #fromleighajarett
* [j2v](https://github.com/Cimpress-MCP/j2v) Creates Looker Views and Explore based on provided JSON(s).  #python #json
* [Blockwork](https://github.com/fabio-looker/blockwork) A tool for working with Looker blocks. #node

### LookML Editting
* [dbtdocs-to-lookml](https://github.com/fishtown-analytics/dbtdocs-to-lookml) [WIP) A script to add descriptions from dbt schema files to your lookml project #python

#### Mapping
* [looker_map_layers](https://github.com/brechtv/looker_map_layers) Looker map_layers base model containing multiple topojson map layers #frombrechtv

#### Parser
* [lkml](https://github.com/joshtemple/lkml) A speedy LookML parser & serializer implemented in pure Python. #python
* [JSON to LookML](https://github.com/leighajarett/JSON_to_LookML) This script creates a LookML view file, and pushes it to production, that parses JSON fields into separate dimensions  #python #json #fromleighajarett
* [j2v](https://github.com/Cimpress-MCP/j2v) Creates Looker Views and Explore based on provided JSON(s).  #python #json
* [Look4j](https://github.com/githoov/look4j) Look4j is LookML parser that relies on ANTLR4 and Java.
* [LookMLParser](https://github.com/JakeColtman/LookMLParser) Looker is a great tool for BI, but it has quite limited tooling.
* [Looker Architecture Helper WIP](https://github.com/linyaru/lookml_helper) Looker Architecture Helper WIP 
* [lkmlprsr](https://github.com/drapadubok/lkmlprsr) PEG grammar for lookML, in Python #python

#### SSO
* [SSO Embed Tool](https://fabio-looker.github.io/looker_sso_tool/#) Test SSO link creation #fromlooker

#### Style Guide
* [lookml-style-guide](https://github.com/mattm/lookml-style-guide) A style guide for LookML wranglers 

#### Syntax Highlighting
* [lkml.vim](https://github.com/thalesmello/lkml.vim) A LookML syntax for vim. 
* [vscode-looker](https://github.com/Ladvien/vscode-looker) A Visual Studio Code extension to assist with developing LookML. 

#### Testing and CI/CD
* [lookml-test-runner](https://github.com/looker/lookml-test-runner) An experimental test runner for LookML models. #CICD #fromlooker
* [spectacles](https://github.com/spectacles-ci/spectacles) A continuous integration tool for Looker and LookML. https://spectacles.dev #CICD

#### Other
* [node-lookml-parser](https://github.com/fabio-looker/node-lookml-parser) Parse LookML in Node #node
* [GDX Analytics](https://github.com/bcgov/GDX-Analytics) GDX-Analytics working space: microservices, tests, POCs, and other scripts #fromgdxanalytics
* [lookml-eav-transformer](https://github.com/fabio-looker/lookml-eav-transformer) LookML EAV transformer #fromlooker #EAV
* [eav-builder](https://github.com/fabio-looker/eav-builder) Build LookML models for EAV schema 
* [LookML Parameter Option Generator](https://github.com/drewgillson/lookml-parameter-option-generator) Use a scheduled look to provide parameter option values to a Google Cloud Function, which will automatically maintain corresponding parameter option values specified in a LookML file. #python


