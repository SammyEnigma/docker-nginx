## 5.16.0 2021-12-04 <dave at tiredofit dot ca>

   ### Added
      - Add Patch to subtract Connection request value from stub_status for accurate reporting


## 5.15.3 2021-11-30 <dave at tiredofit dot ca>

   ### Changed
      - Fix for building with GCC 11.2


## 5.15.2 2021-11-02 <dave at tiredofit dot ca>

   ### Added
      - Nginx 1.21.4


## 5.15.1 2021-09-25 <dave at tiredofit dot ca>

   ### Added
      - Nginx 1.21.3


## 5.15.0 2021-09-24 <dave at tiredofit dot ca>

   ### Changed
      - Pin nginx user to '80' from a randomly generated UID during build process


## 5.14.7 2021-09-06 <dave at tiredofit dot ca>

   ### Changed
      - For for NGINX_AUTHENTICATION_TYPE


## 5.14.6 2021-09-05 <dave at tiredofit dot ca>

   ### Changed
      - Fix for Error Logs
      - Fix for Fluent-bit Log Parsers


## 5.14.5 2021-09-05 <dave at tiredofit dot ca>

   ### Changed
      - Blocked logs configuration fix


## 5.14.4 2021-09-04 <dave at tiredofit dot ca>

   ### Changed
      - Customizable Blocked file and further parsing of logrotation files


## 5.14.3 2021-09-04 <dave at tiredofit dot ca>

   ### Changed
      - Change the way that logrotat files are utilized


## 5.14.2 2021-09-03 <dave at tiredofit dot ca>

   ### Added
      - Nginx 1.21.2


## 5.14.1 2021-08-30 <dave at tiredofit dot ca>

   ### Changed
      - Add two new logformats to support LLNG Authentication


## 5.14.0 2021-08-29 <dave at tiredofit dot ca>

   ### Added
      - Option to output json for access log

   ### Changed
      - Reworked fluent bit log parsing regex
      - Changed output format of access logs
      - Split logging into its own configuration file
      - Reworked "blocked" log_format
      - Renamed "Zabbix" functionality to "Monitoring"


## 5.13.7 2021-08-25 <dave at tiredofit dot ca>

   ### Added
      - Add parsers for fluent-bit log shipping


## 5.13.6 2021-08-04 <dave at tiredofit dot ca>

   ### Added
      - Change the way logrotate operates


## 5.13.5 2021-07-12 <dave at tiredofit dot ca>

   ### Changed
      - Skip LLNG authentication routines if it detects downstream php-fpm image being used


## 5.13.4 2021-07-11 <dave at tiredofit dot ca>

   ### Added
      - Nginx 1.21.1


## 5.13.3 2021-07-05 <dave at tiredofit dot ca>

   ### Changed
      - Support upstream image changes


## 5.13.2 2021-06-17 <dave at tiredofit dot ca>

   ### Changed
      - Fix issues with Alpine 3.14 and Edge builds


## 5.13.1 2021-05-25 <dave at tiredofit dot ca>

   ### Added
      - Nginx 1.21.0


## 5.13.0 2021-05-08 <dave at tiredofit dot ca>

   ### Added
      - Nginx 1.20.0


## 5.12.10 2021-04-20 <dave at tiredofit dot ca>

   ### Added
      - Update LemonLDAP:NG configuration to suppoprt CDA domains


## 5.12.9 2021-04-07 <dave at tiredofit dot ca>

   ### Added
      - Nginx 1.19.9


## 5.12.8 2021-03-11 <dave at tiredofit dot ca>

   ### Added
      - Update Brotli to 1.09
      - Nginx 1.19.8


## 5.12.7 2021-02-22 <dave at tiredofit dot ca>

   ### Added
      - Nginx 1.19.7


## 5.12.6 2021-01-15 <dave at tiredofit dot ca>

      - Switch main base to alpine 3.13

## 5.12.5 2021-01-03 <jesper at github>

   ### Fixed
      - LDAP Configuration was generating bad configuration files. Fix whitespace and Carriage Returns


## 5.12.4 2020-12-22 <dave at tiredofit dot ca>

   ### Added
      - Nginx 1.19.6


## 5.12.3 2020-11-30 <dave at tiredofit dot ca>

   ### Added
      - Nginx 1.19.5


## 5.12.2 2020-11-14 <dave at tiredofit dot ca>

   ### Added
      - Nginx 1.19.4


## 5.12.1 2020-10-26 <dave at tiredofit dot ca>

   ### Changed
      - Fix when NGINX_ENABLE_BLOCK_BOTS=FALSE throws errors


## 5.12.0 2020-10-25 <dave at tiredofit dot ca>

   ### Added
      - Add Nginx Ultimate Bad Bot Blocker to issue 444s to crawlers and bad referrers


## 5.11.7 2020-10-01 <dave at tiredofit dot ca>

   ### Added
      - Nginx 1.19.3


## 5.11.6 2020-09-07 <dave at tiredofit dot ca>

   ### Changed
      - Change to LLNG Authentication method to address CVE


## 5.11.5 2020-08-29 <dave at tiredofit dot ca>

   ### Added
      - Add ENABLE_NGINX variable


## 5.11.4 2020-08-18 <dave at tiredofit dot ca>

   ### Added
      - Nginx 1.19.2


## 5.11.3 2020-08-12 <dave at tiredofit dot ca>

   ### Added
      - Add NGINX_CLIENT_BODY_BUFFER_SIZE environment variable


## 5.11.2 2020-07-15 <dave at tiredofit dot ca>

   ### Added
      - Nginx 1.19.1

   ### Changed
      - Code cleanup as per bash shellcheck warnings


## 5.11.1 2020-06-11 <dave at tiredofit dot ca>

   ### Changed
      - Fix for logrotate if Access Logs and Error Logs are in same location


## 5.11.0 2020-06-09 <dave at tiredofit dot ca>

   ### Added
      - Update to support tiredofit/alpine 5.0.0 base image

## 5.10.1 2020-05-17 <dave at tiredofit dot ca>

   ### Changed
      - Remove Site Optimizations when using PROXY mode


## 5.10.0 2020-05-17 <dave at tiredofit dot ca>

   ### Added
      - Introduced Reverse Proxy Feature set by NGINX_MODE=PROXY and NGINX_PROXY_URL


## 5.9.4 2020-05-09 <dave at tiredofit dot ca>

   ### Changed
      - Remove faulty access log statement in site_optimization.conf


## 5.9.3 2020-04-22 <dave at tiredofit dot ca>

   ### Added
      - Nginx 1.18.0


## 5.9.2 2020-04-18 <dave at tiredofit dot ca>

   ### Added
      - Update to support tiredofit/alpine 4.5.1 release


## 5.9.1 2020-04-15 <dave at tiredofit dot ca>

   ### Added
      - Nginx 1.17.10


## 5.9.0 2020-03-09 <dave at tiredofit dot ca>

   ### Added
      - Add NGINX_RELOAD_ON_CONFIG_CHANGE environment variable to automatically reload nginx configuration if main configuration files are changed or the value of NGINX_INCLUDE_CONFIGURATION

   ### Changed
      - Fixed `NGINX_ENABLE_FASTCGI_HTTPS` that didn't do anything

## 5.8.3 2020-03-04 <dave at tiredofit dot ca>

   ### Added
      - Nginx 1.17.9


## 5.8.2 2020-02-25 <dave at tiredofit dot ca>

   ### Changed
      - Fix extra semicolon in default environment variable


## 5.8.1 2020-02-25 <dave at tiredofit dot ca>

   ### Changed
      - Spelling mistake for fastcgi_buffer_size


## 5.8.0 2020-02-25 <dave at tiredofit dot ca>

   ### Added
      - Add FastCGI Buffers and FastCGI Buffer Size environment variables


## 5.7.2 2020-01-22 <dave at tiredofit dot ca>

   ### Added
      - Nginx 1.17.8


## 5.7.1 2020-01-03 <dave at tiredofit dot ca>

   ### Changed
      - Cleanup LLNG Authentication routines


## 5.7.1 2020-01-02 <dave at tiredofit dot ca>

   ### Changed
      - Additional Changes to support new tiredofit/alpine base image


## 5.7.0 2019-12-31 <dave at tiredofit dot ca>

   ### Added
      - Split defaults to /assets/functions

   ### Changed
      - Change Warnings to Notices


## 5.6.1 2019-12-29 <dave at tiredofit dot ca>

   ### Added
      - Nginx 1.17.7


## 5.6.0 2019-12-29 <dave at tiredofit dot ca>

   ### Added
      - Refactored image to support new tiredofit/alpine base image
      - Added FORCE_RESET_PERMISSIONS env variable (credit juanluisbaptiste@github)


## 5.5.0 2019-12-20 <dave at tiredofit dot ca>

   ### Added
      - Alpine 3.11 Base Image


## 5.4.4 2019-12-16 <dave at tiredofit dot ca>

   ### Changed
      - Change Sed Command to properly escape slashes


## 5.4.3 2019-12-16 <dave at tiredofit dot ca>

   ### Added
      - Add Default Variable to pass for LLNG


## 5.4.2 2019-12-16 <dave at tiredofit dot ca>

   ### Changed
      - Tweaks to LLNG Authentication


## 5.4.1 2019-12-12 <dave at tiredofit dot ca>

   ### Changed
      - Fix Basic Authentication Passwords


## 5.4.0 2019-12-12 <dave at tiredofit dot ca>

   ### Added
      - Add default `NGINX_USER` and `NGINX_GROUP` variables


## 5.3.0 2019-12-09 <dave at tiredofit dot ca>

   ### Added
      - Add functionality to set fastcgi_param HTTPS 'on' or 'off'


## 5.2.0 2019-12-09 <dave at tiredofit dot ca>

   ### Added
      - Add `NGINX_INCLUDE_CONFIGURATION` to include additional .conf files from the filesystem for applications

## 5.1.0 2019-12-09 <dave at tiredofit dot ca>

   ### Added
      - Added NGINX_MODE environment variable to allow Redirection to remote URLs

   ### Changed
      - Moved around maintenance functionality
      - Minor cleanup to code


## 5.0.0 2019-12-04 <dave at tiredofit dot ca>

   ### Added
      - Nginx 1.17.6
      - Rewrote entire image
      - Added many new environment variables for customization
      - Enabled Brotli Compression
      - Enabled Gzip Compression
      - Broke out configuration into seperate files
      - Integrated tiredofit/nginx-ldap functionality
      - Cleaned up code
      - Tuned for performance

## 4.2.1 2019-11-18 <dave at tiredofit dot ca>

   ### Added
      - Update to Nginx 1.17.5


## 4.2 2019-06-30 <dave at tiredofit dot ca>

* Nginx 1.17.0
* Cleanup Build Process

## 4.1 2019-06-19 <dave at tiredofit dot ca>

* Change Alpine Base Image to 3.10

## 4.0.5 2019-04-28 <dave at tiredofit dot ca>

* Bump to Nginx 1.16.0

## 4.0.4 2019-03-26 <dave at tiredofit dot ca>

* Bump to Nginx 1.15.10

## 4.0.3 2019-02-08 <dave at tiredofit dot ca>

* Bump to Nginx 1.15.8 

## 4.0.2 2018-12-10 <dave at tiredofit dot ca>

* Bump to Nginx 1.15.7

## 4.0.2 2018-10-23 <dave at tiredofit dot ca>

* Bump to Nginx 1.15.5

## 4.0.1 2018-09-24 <dave at tiredofit dot ca>

* Bump to Nginx 1.15.3

## 4.0 2018-04-28 <dave at tiredofit dot ca>

* Ability to protect service via basic authentication or using LemonLDAP:NG Handlers

## 3.8 2018-04-14 <dave at tiredofit dot ca>

* Bump Version, Clean Code

## 3.7 2018-04-02 <dave at tiredofit dot ca>

* Added MAINTENANCE environment variable to move system to maintenance mode. Also maintenance script (off/on/sleep 60) inside container.

## 2018-02-20 3.6 <dave at tiredofit dot ca>

* Fix startup Issues with Logfiles

## 2018-02-20 3.5 <dave at tiredofit dot ca>
	
* Add Reverse Proxy Detection

## 2018-01-29 3.4 <dave at tiredofit dot ca>

* Rebase

## 2018-01-29 3.3 <dave at tiredofit dot ca>

* Nginx 1.13.8
* Update Zabbix Scripts

## 2017-12-01 3.2 <dave at tiredofit dot ca>

* Update Base to Alpine 3.7
* Nginx 1.13.7

## 3.1 2017-09-27 <dave at tiredofit dot ca>

* Fix Build Issues
* Nginx 1.13.5

## 3.0 2017-08-27 <dave at tiredofit dot ca>

* Major Version Bump to support Base Image Changes

## 2.3 2017-07-13 <dave at tiredofit dot ca>

* Cleaned up Initialization Routes with cont-init.d

## 2.2 2017-07-03 <dave at tiredofit dot ca>

* Added Logrotate

## 2.1 2017-07-02 <dave at tiredofit dot ca>

* S6 Init Script Sanity Check

## 2.0 2017-06-23 <dave at tiredofit dot ca>

* New S6 Container Processes
* Implemented conf.d folder
* Changed Zabbix run process
* Moved Status Checks to Port 73

## 1.3 2017-05-20 <dave at tiredofit dot ca>

* Nginx 1.13.0
* Enabled Extra Modules to Match Upstream nginx image

## 1.2 2017-04-07 <dave at tiredofit dot ca>

* Rebase
* Nginx 1.1.13

## 1.1 2017-03-11 <dave at tiredofit dot ca>

* Move Data Directory to follow SelfDesign Paths
* Simplify nginx.conf

## 1.0 2017-02-20 <dave at tiredofit dot ca>

* Initial Release - Nginx Mainline w/Alpine 3.4
* Zabbix Status Monitoring Included
