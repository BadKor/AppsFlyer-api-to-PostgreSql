# AppsFlyer-api-to-PosgreSql

Script for load AppsFlyer Data via api to PostgreSql

Before start you can create table in you PostgreSql:

Table for loads_installs function:

create table table_name_for_installs
(
    "Attributed Touch Type" text,
    "Attributed Touch Time" timestamp,
    "Install Time"          timestamp,
    "Event Time"            timestamp,
    "Event Name"            text,
    "Event Source"          text,
    "Partner"               text,
    "Media Source"          text,
    "Campaign"              text,
    "Campaign ID"           text,
    "Adset"                 text,
    "Adset ID"              text,
    "Ad"                    text,
    "Ad ID"                 text,
    "Site ID"               text,
    "Region"                text,
    "Country Code"          text,
    "State"                 text,
    "City"                  text,
    "Postal Code"           text,
    "DMA"                   text,
    "IP"                    text,
    "WIFI"                  boolean,
    "AppsFlyer ID"          text,
    "IDFA"                  text,
    "IDFV"                  text,
    "Platform"              text,
    "Device Type"           text,
    "OS Version"            text,
    "App Version"           text,
    "SDK Version"           text,
    "App ID"                text,
    "App Name"              text,
    "Bundle ID"             text,
    "Is Retargeting"        boolean,
    "Attribution Lookback"  text,
    "User Agent"            text,
    "HTTP Referrer"         text,
    "Original URL"          text,
    "Conversion Type"       text,
    "Match Type"            text,
    "Campaign Type"         text,
    "Device Download Time"  timestamp,
    "Device Model"          text,
    "Is LAT"                boolean,
    "Device Category"       text,
    "App Type"              text,
    "ATT"                   text
);


Table for loads_protect360 function:

create table table_name_for_protect360
(
    "Attributed Touch Type" text,
    "Attributed Touch Time" timestamp,
    "Install Time"          timestamp,
    "Event Time"            timestamp,
    "Event Name"            text,
    "Event Source"          text,
    "Partner"               text,
    "Media Source"          text,
    "Campaign"              text,
    "Campaign ID"           text,
    "Adset"                 text,
    "Adset ID"              integer,
    "Ad"                    text,
    "Ad ID"                 integer,
    "Site ID"               text,
    "Cost Value"            real,
    "Cost Currency"         text,
    "Region"                text,
    "Country Code"          text,
    "State"                 text,
    "City"                  text,
    "Postal Code"           text,
    "DMA"                   text,
    "IP"                    text,
    "WIFI"                  boolean,
    "AppsFlyer ID"          text,
    "IDFA"                  text,
    "IDFV"                  text,
    "Platform"              text,
    "Device Type"           text,
    "OS Version"            text,
    "App Version"           text,
    "SDK Version"           text,
    "App ID"                text,
    "App Name"              text,
    "Bundle ID"             text,
    "Is Retargeting"        boolean,
    "Attribution Lookback"  text,
    "User Agent"            text,
    "Original URL"          text,
    "Detection Date"        date,
    "Match Type"            text,
    "Fraud Reason"          text,
    "Device Download Time"  timestamp,
    "Device Model"          text,
    "Fraud Reasons"         text,
    "Fraud Sub Reason"      text,
    "Install Time TZ"       timestamp,
    "Device Category"       text,
    "ATT"                   text
);



Table for loads_events function:

create table table_name_for_events
(
    "Attributed Touch Type"  text,
    "Attributed Touch Time"  timestamp,
    "Install Time"           timestamp,
    "Event Time"             timestamp,
    "Event Name"             text,
    "Event Value"            text,
    "Event Revenue"          integer,
    "Event Revenue Currency" text,
    "Event Revenue USD"      real,
    "Event Source"           text,
    "Partner"                text,
    "Media Source"           text,
    "Campaign"               text,
    "Campaign ID"            text,
    "Adset"                  text,
    "Adset ID"               integer,
    "Ad"                     text,
    "Ad ID"                  integer,
    "Site ID"                text,
    "Region"                 text,
    "Country Code"           text,
    "State"                  text,
    "City"                   text,
    "Postal Code"            text,
    "DMA"                    text,
    "IP"                     text,
    "WIFI"                   boolean,
    "AppsFlyer ID"           text,
    "IDFA"                   text,
    "Customer User ID"       text,
    "IDFV"                   text,
    "Platform"               text,
    "Device Type"            text,
    "OS Version"             text,
    "App Version"            text,
    "SDK Version"            text,
    "App ID"                 text,
    "App Name"               text,
    "Bundle ID"              text,
    "Is Retargeting"         boolean,
    "Attribution Lookback"   text,
    "Is Primary Attribution" boolean,
    "User Agent"             text,
    "HTTP Referrer"          text,
    "Original URL"           text,
    "Conversion Type"        text,
    "Match Type"             text,
    "Blocked Reason"         text,
    "Blocked Sub Reason"     text,
    "Campaign Type"          text,
    "Rejected Reason"        text,
    "Device Download Time"   timestamp,
    "Device Model"           text,
    "Is LAT"                 boolean,
    "Device Category"        text,
    "App Type"               text,
    "ATT"                    text
);
