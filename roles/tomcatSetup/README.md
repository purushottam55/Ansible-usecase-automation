
                          # ! Still i am work is going on it
# Tomcat Role

## Description

This role installs and configures Apache Tomcat on target hosts.

## Requirements

Ensure the target system has the necessary pre-requisites, including:
- A supported version of Java (JDK 8 or higher).
- Sufficient disk space for the Tomcat installation.

## Role Variables

The following variables can be set to customize the Tomcat installation and configuration:

- `http_port`: Port for HTTP connections (default: 8080)
- `https_port`: Port for HTTPS connections (default: 8443)
- `admin_username`: Username for Tomcat admin (default: admin)
- `admin_password`: Password for Tomcat admin (default: admin)
- `tomcat_version`: Version of Tomcat to install (default: 9.0.54)
- `tomcat_download_url`: URL to download Tomcat (default: https://archive.apache.org/dist/tomcat/tomcat-9/v9.0.54/bin/apache-tomcat-9.0.54.tar.gz)

These variables can be defined in `defaults/main.yml`, `vars/main.yml`, or set via parameters to the role.


