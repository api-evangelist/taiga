---
title: "New Docker patch release (6.7.1)"
url: "https://community.taiga.io/t/new-docker-patch-release-6-7-1/1626"
date: "2023-08-09"
author: "daniel.herrero"
feed_url: "https://community.taiga.io/c/announcements/5.rss"
---
This patch affects the Taiga docker repository , and it improves the performance in the RabbitMQ-related services. By avoiding periodic healthchecks services for taiga-async-rabbitmq and taiga-events-rabbitmq , we hope to prevent high CPU usage peaks in execution time. Thanks for the issues reported!
