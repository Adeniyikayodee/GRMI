# Community collaboration in the context of Disaster Risk Preparedness and Response.

This solution was created for Geohazards Risk Mapping Initiative

## Author(s)

- Kayode Adeniyi

## Contents

1. [Overview](#overview)
2. [The idea](#the-idea)
3. [How it works](#how-it-works)
4. [Diagrams](#diagrams)
5. [Technology](#technology)

## Overview

### What's the problem?

There is a growing interest in enabling communities to cooperate among themselves to solve disaster risk issues, whether it be to advertise where supplies are held, offer assistance for collections, or other local services like volunteer deliveries.

In times of crisis, such as the flood, while federal and local governments may be rolling out broad programs, cooperation at the local level is usually the most effective way of getting help to where it is most needed as quickly as possible. Traditional social media is one way of communicating within a community, but this is (by its very design) not locally focused, and often not sufficiently structured to enable rapid discovery of help needed.

In the October 2022 flood crisis, we have already seen shortages of local food, medical equipment, and other supplies. In addition, the road blocks, camps and other measures to reduce people from easily getting to locations with the best stocks of supplies.

What is needed is a solution that empowers communities to easily connect and provide this information to each other.

### How can technology help?

Mobile, web, and cloud services enable rapid deployment of applications that can empower cooperation in the community.

Creating a chatbot using A.I can help address the issues that your users may face while trying to gather the necessary information. Embedding location/routing services can enhance such applications, giving optimum guidance so that they are outside of their isolation location for the minimum amount of time.

## The idea

The goal is to provide a mobile application, along with server-side components, that serves as a community cooperation application that addresses local needs for food, equipment, and resources.
It would allow both "Suppliers" (such as a store or a community member who has produce they can sell or distribute) to make people aware of what the have; and consumers ("Recipients") to locate where these supplies are, and, if necessary, guide them to the appropriate locations to pick them up.

## How it works

A Supplier (who may be a regular resident, a small business, a voluntary organization, etc.) that has food, supplies, resources, or other essentials they can provide opens the mobile application and fills out a brief form that indicates what they have. This information is then stored in a database in the Cloud.

A Recipient, who is in need of food, supplies, resources, or other essentials, opens the mobile application and can use the chat interface to locate supplies near them. For instance, they might type "Where can I find bread?" or "Can someone collect my shopping for me?" The mobile application then accesses the database (after first understanding the question via Watson Assistant) and then displays a map showing locally where they can find what they are looking for.

## Diagrams (mental for now) WIP.

This solution starter idea combines a chat interface, data storage to hold the status of supplies available, and location services with real-time information to get users the information they need.

1. The Recipient launches the mobile app and can access information across multiple services.
1. The Recipient can ask questions to A.I, and get answers on food/service availability questions.
1. The Supplier can post the availability of stock or services they can provide, as well as locate the items they need.
1. The Recipient can obtain geolocation data to plot routes to collect (or drop off) supplies using Geospatial Location Services.

## Technology

WIP...
Cloud services:
1. 
2. 
3. 

location services:
1.
2.
3.