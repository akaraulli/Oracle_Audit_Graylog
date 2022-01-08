Oracle Audit Content Pack for Graylog visualizes Oracle unified audit events in Graylog. 
These events are delivered to Graylog from Oracle DB, via Oracle Audit Add-On for Graylog, installed on the Oracle DB.

Oracle-side requirement:
https://github.com/akaraulli/Oracle_Audit_Add_on_for_Graylog

Components:

1. GELF TCP Input
Oracle Audit TCP Input - will ingest records pushed by Oracle Audit Add-On for Graylog 

2. Stream

Oracle Audit - data from Oracle Audit Add-On for Graylog deployments

3. Dashboards

Oracle Audit Events Summary 
Oracle Audit Events Records

4. Saved-Searches 

named by respective SEO (Extra Search Options) fields - as described in Oracle Audit Add-On for Graylog User_Guide


Oracle Audit Events Summary dashboard

![Screenshot 2022-01-08 at 00-59-45 Oracle Audit Graylog SUmmary](https://user-images.githubusercontent.com/94201903/148621953-f348b963-6a9e-4035-8737-aae01b825a05.png)

