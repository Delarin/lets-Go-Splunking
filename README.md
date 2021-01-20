# lets-Go-Splunking

## Scenario

You have just been hired as an SOC Analyst by Vandalay Industries, an importing and exporting company.


Vandalay Industries uses Splunk for their security monitoring and have been experiencing a variety of security issues against their online systems over the past few months.


You are tasked with developing searches, custom reports and alerts to monitor Vandalay's security environment in order to protect them from future attacks.


## Vandalay Industries Monitoring Activity Instructions

### Step 1: The Need for Speed
Background: As the worldwide leader of importing and exporting, Vandalay Industries has been the target of many adversaries attempting to disrupt their online business. Recently, Vandaly has been experiencing DDOS attacks against their web servers.
Not only were web servers taken offline by a DDOS attack, but upload and download speed were also significantly impacted after the outage. Your networking team provided results of a network speed run around the time of the latest DDOS attack.


#### Task Use To Complete The Project: 
* Create a report to determine the impact that the DDOS attack had on download and upload speed. Additionally, create an additional field to calculate the ratio of the upload speed to the download speed.


* Upload the following file of the system speeds around the time of the attack.

 ![Speed Test File](./SIEMs_resources_server_speedtest.csv)



* create a field called ratio that shows the ratio between the upload and download speeds.

* Create a report to display the following fields in a statistics report:

  * _time
  * IP_ADDRESS
  * DOWNLOAD_MEGABITS
  * UPLOAD_MEGABITS
  * ratio

#### Answer the following questions:

Based on the report created, what is the approximate date and time of the attack?
How long did it take your systems to recover?


###  Step 1: Solution

![Upload file 1](lets-Go-Splunking/Step1/pic1-1.png)
