# IWXXM
IWXXM (the ICAO Meteorological Information Exchange Model) is a data format for reporting aviation weather information
in XML/GML, and is specified in both XML Schema and Schematron.

[![Build Status](https://travis-ci.org/wmo-im/iwxxm.svg?branch=master)](https://travis-ci.org/wmo-im/iwxxm)

# Summary
IWXXM includes XML/GML-based representations for products standardized in International Civil Aviation Organization (ICAO) Annex III and World Meteorological Organization (WMO) No.49, Vol II, such as METAR/SPECI, TAF, SIGMET, AIRMET, Tropical Cyclone Advisory, Volcanic Ash Advisory and Space Weather Advisory. IWXXM products are used for operational exchanges of meteorological information for use in aviation.

Unlike the traditional forms of the ICAO Annex III / WMO No. 49 products (referred to as Traditional Alphanumeric Codes, or TAC), IWXXM is not intended to be directly used by pilots. IWXXM is designed to be consumed by software acting on behalf of pilots, such as display software.

# Want to provide feedback or raise a question?
Please provide feedback to or raise your question in Google group [cbs-tt-avxml@wmo.int](https://groups.google.com/a/wmo.int/forum/?hl=en&fromgroups#!forum/cbs-tt-avxml).

# References
* IWXXM on WMO Community Platform
* [WMO No.306 Volume I.3, _Manual on Codes. Part D - Representations derived from data models_](https://library.wmo.int/index.php?lvl=notice_display&id=19508)
* [ICAO Doc 10003, _Manual on the Digital Exchange of Aeronautical Meteorological Information_](https://store.icao.int/en/manual-on-the-icao-meteorological-information-exchange-model-doc-10003)

# See also
* The [IWXXM modelling repository](https://github.com/wmo-im/iwxxm-modelling) contains UML model of IWXXM and tools that were used for preparing schemas, schematron rules and associated files in this repository. 
* The [IWXXM translation repository](https://github.com/wmo-im/iwxxm-translation) has resources related to Traditional Alphanumeric Code (TAC) to IWXXM translation, including equivalent TAC/IWXXM pairs and a list of translation software.
