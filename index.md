---
layout: default
title: 
---  


* TOC  
{:toc}  

## Project Description

Written in C, records radio stations 24/7. The backend machine records several local over-the-internet stations, keeping 34 minute chunks of overlapping chunks of audio and text archived locally on an 8T hard drive. Each machine also sends a copy of the text in smaller overlapping chunks to the database server for searching by the SE app.


[Repository](https://github.com/MrElectrify/cs495-website)

## Project Goals

1.	Make sure the C compiler and all dependencies are up to date, documented and put on github in a timely manner.
2.	Add a new process to monitor all processes and restart them if any of them fail.
3.	When the archive disk is purged of old records, make the DB move the purged record data of the corresponding closed captions records to a new archive table.
4.	Improve speech-to-text.
5.	Add successful & unsuccessful table/s to capture information about what did/didn't record properly.
6.	Add over-the-air stations.
7.	Add Satellite Radio.
