+++
title = "{{ replace .Name \"-\" \" \" | title }}"
date = {{ .Date }}
draft = false
description = "Discover {{ replace .Name \"-\" \" \" | title }} - an unforgettable journey through Turkey's most stunning destinations."
tourHighlights = [
  "Highlight 1",
  "Highlight 2",
  "Highlight 3"
]
duration = "X days"
price = "$X,XXX USD"
singleSupplement = "$XXX USD"
location = "Turkey"
destinations = ["Istanbul", "Cappadocia"]
categories = ["Tours"]
tags = ["Adventure", "Cultural", "Historical"]
image = "/images/tours/{{ .File.BaseFileName }}.jpg"
tourIncludes = [
  "Accommodation as per itinerary",
  "Private licensed tour guide",
  "Private touring car",
  "Entrance fees per itinerary",
  "Meals: X breakfast, X lunch, X dinner",
  "Private airport transfers"
]
tourExcludes = [
  "Beverages",
  "Gratuities",
  "Hot air balloon in Cappadocia (optional)"
]

# Optional Activities
optionalActivities = [
  { name = "Hot Air Balloon Ride in Cappadocia", price = "$XXX USD", duration = "1 hour" },
  { name = "Turkish Bath Experience", price = "$XX USD", duration = "2 hours" },
  { name = "Whirling Dervish Ceremony in Cappadocia", price = "$55 USD", duration = "1.5 hours" }
]


# Booking and Availability
nextDepartures = [
  "May 10, 2025",
  "June 20, 2025",
  "July 10, 2025"
]
minimumParticipants = 2
availableSpaces = "Limited"
bookingDeadline = "30 days before departure"
cancellationPolicy = "Full refund 60 days before departure, 50% refund 30-60 days before departure"

featured = false
weight = 100
+++

## Overview

Tour overview here.

## Highlights

- Point 1
- Point 2

## Itinerary

### Day 1: Location
Details about day 1.

### Day 2: Location
Details about day 2.