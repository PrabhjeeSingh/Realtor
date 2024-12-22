# Realtor Property Management System

## Overview
A comprehensive real estate management system built with Spring Boot that handles various types of properties including residential properties, apartments, houses, and commercial spaces. The system provides robust property management features with a flexible and extensible architecture.

## Architecture
The system follows a domain-driven design approach with the following key components:

### Core Entities
- **Land**: Base entity containing common property attributes
- **Property Types**:
  - Residential
  - Apartment
  - House
  - Multifamily
  - TripeDecker
  - Townhouse
  - Mobile
  - Detach
  - SemiDetach
- **Builder**: Manages property construction and development
- **Facilities**: 
  - LockersAndStorage
  - ParkingLot


## Setup and Installation

### Prerequisites
- JDK 17 or higher
- Maven 3.6+ or Gradle 7+
- Your preferred IDE (IntelliJ IDEA recommended)
- MySQL/PostgreSQL database

## Key Features

### Property Management
- Multi-type property support with inheritance-based architecture
- Comprehensive property attributes management
- Advanced search and filtering capabilities
- Property status tracking

### Builder Management
- Builder registration and profile management
- Construction progress tracking
- Project portfolio management
- Builder-property association

### Facility Management
- Parking lot management
- Storage space allocation
- Unit capacity tracking
- Amenity management


## Database Schema
The system uses a hierarchical database design with inheritance mapping. Key relationships include:
- One-to-Many between Builder and Properties
- One-to-One between Property and Facilities
- Inheritance mapping for different property types

  
## System Architecture UML Diagram
[![System Architecture UML Diagram](https://github.com/PrabhjeeSingh/Realtor/blob/main/ModelUMLDiagram.png)]((https://github.com/PrabhjeeSingh/Realtor/blob/main/ModelUMLDiagram.png))
