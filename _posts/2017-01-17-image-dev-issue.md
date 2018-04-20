---
layout: post
title: Fixing Image Errors In SQL
author: Michael Williams
date: 2017-01-17 13:36:51 -0500
---
# Fixing A bug

Right now I am working on:
> TSS-74 'correct improper named image files in database'.

## Image Not Found

**Problem**:
> **Random** images but always the same ones in different categories are not showing up, they are only showing alt text. <br>
Find out why these images are not showing up and correct their specific issue.

## Probable Cause

As of now I have most of the basic design of the site 'Tools-site' complete. but some images are failing, coming from the database to the php query showing up the images as just the alt text. So I am using firefox developer tools 'inspect element' to check the source of the images. While the path to the image folder is correct, the file names so far have been wrong for those images I have checked that are not showing up.

## Solution 

Solution: 
> Run through all images that are not working, and rename them in the database with correct names including folder structure needed for particular design.