# Tourism Knowledge Graph Schema

## Core Entity Types

- Attraction
- Heritage Site
- Religious Site
- Event
- Restaurant
- Hotel
- Transport Node
- Tourism Circuit
- District

## Core Relationships

- Located In
- Near
- Part Of
- Connected To
- Recommended With
## Entity Schema

Required Fields:

- Entity ID
- Name
- Category
- Subcategory
- District
- Latitude
- Longitude
- Verification Status
- Source

---

## Relationship Schema

Required Fields:

- Relationship ID
- Source Entity
- Target Entity
- Relationship Type
- Confidence Score
- Verification Status

---

## Circuit Schema

Required Fields:

- Circuit ID
- Circuit Name
- Theme
- District
- Included Entities

---

## Confidence Score Framework

100 = Official Government Source

90 = Government Verified

80 = Industry Verified

70 = Community Verified

Below 70 = Requires Review

---

## Verification Status

Allowed Values:

- Verified
- Pending
- Rejected
- Under Review
