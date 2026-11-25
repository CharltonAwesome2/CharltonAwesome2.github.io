# Project D: Camera-Based Identification and Tracking Application

## Overview

Development of an application using facial recognition and camera feeds to identify and track individuals within designated areas.

## User stories and tasks

### D-01: Configure and connect cameras

**User story:** As an authorised operator, I want to configure cameras so that the application can use available camera equipment for identification and tracking.

**Tasks:**
- Investigate camera compatibility.
- Integrate camera feeds.
- Implement camera configuration functionality.
- Test camera operation.

**Status:** Partially completed.

**Outcome:** Three different camera types operated successfully in parallel during system testing.

### D-02: Associate cameras with designated areas

**User story:** As an authorised operator, I want cameras to be associated with designated areas so that camera activity can be organised by location.

**Tasks:**
- Implement area-related data structures.
- Develop camera-to-area relationships.
- Implement the relevant backend operations.
- Test camera and area associations.

**Status:** Partially completed. Camera-to-area relationships were implemented, while broader area-management functionality remained incomplete.

### D-03: Identify and track individuals

**User story:** As an authorised operator, I want the application to identify and track individuals captured by cameras so that their movement within monitored areas can be observed.

**Tasks:**
- Implement facial-recognition functionality.
- Integrate recognition with camera feeds.
- Develop tracking functionality.
- Test recognition and tracking.
- Investigate and address recognition-related issues.

**Status:** Implemented and tested, with further integration and testing required.

### D-04: Record recognition events

**User story:** As an authorised operator, I want recognition events to be recorded so that relevant system activity can be reviewed.

**Tasks:**
- Design recognition-event data structures.
- Implement event logging.
- Store recognition events.
- Test event creation and retrieval.

**Status:** Completed.

### D-05: Manage users and system access

**User story:** As an administrator, I want user accounts and authentication to be implemented so that access to the application can be controlled.

**Tasks:**
- Identify user-management requirements.
- Implement authentication functionality.
- Develop user-management functionality.
- Test access-control functionality.

**Status:** Not started.

## Project outcome

The identification and tracking functionality was demonstrated using three different camera types operating in parallel. Camera configuration and area-management functionality remained partially complete.

User management, authentication and audit functionality had not been implemented. A dedicated production frontend had also not been developed. Development was paused.