# Awesome-Conference-Room-Scheduling

# Top Conference Room Scheduling Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Meeting Room Booking, Desk Reservations, Workspace Utilization & Resource Scheduling*
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Conference Room Scheduling**. These tools help organizations manage meeting room bookings, optimize desk utilization in hybrid offices, and provide visibility into workspace availability across locations.

**Examples** include Robin, Condeco, Skedda, Joan, Teem by iOFFICE, OfficeSpace, YArooms, Nexudus, Resource Central, and MeetingRoomApp (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom booking workflows, and transparent workspace data — ideal for organizations that need full control over their scheduling infrastructure without per-room SaaS fees or vendor lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Robin](https://robinpowered.com/)**  
  Workplace experience platform for hybrid teams. Provides room and desk booking, workplace analytics, and integrations with Google Calendar and Microsoft 365.

- **[Condeco](https://www.condeco.com/)**  
  Workplace management platform with desk booking, meeting room scheduling, and occupancy analytics. Used by enterprises worldwide for hybrid workplace optimization.

- **[Skedda](https://www.skedda.com/)**  
  Cloud-based space scheduling platform for meeting rooms, desks, and shared resources. Known for ease of use and flexible booking rules.

- **[Joan](https://www.getjoan.com/)**  
  Meeting room booking system with dedicated hardware displays (Joan devices) mounted outside rooms. Provides real-time availability, on-device booking, and calendar sync.

- **[Teem by iOFFICE](https://www.iofficecorp.com/)**  
  Workplace experience platform (now part of Eptura) for room and desk scheduling, visitor management, and workplace analytics. Integrates with calendar systems and provides utilization insights .

- **[OfficeSpace](https://www.officespacesoftware.com/)**  
  Workplace management platform with desk booking, room scheduling, and space utilization analytics. Helps organizations optimize office footprint.

- **[YArooms](https://www.yarooms.com/)**  
  Cloud-based meeting room booking software. Provides room availability, booking management, and calendar integration for small to mid-sized organizations.

- **[Nexudus](https://www.nexudus.com/)**  
  Coworking and flex space management platform. Includes meeting room booking, desk reservations, and member management for shared workspaces.

- **[Resource Central](https://www.resourcecentral.com/)**  
  Resource scheduling and hoteling software. Manages meeting rooms, desks, and equipment bookings with analytics.

- **[MeetingRoomApp](https://www.meetingroomapp.com/)**  
  Meeting room booking system for offices. Provides room displays, calendar sync, and booking management.

## Open-Source GitHub Projects

### Room & Resource Booking Systems

- **[Booked Scheduler / LibreBooking](https://github.com/LibreBooking/librebooking)**  
  The most established open-source resource scheduling system. Originally Booked Scheduler (formerly phpScheduleIt), now community-maintained as LibreBooking. **802 stars, 377 forks, GPL-3.0, actively maintained** . PHP/MySQL application for managing and reserving shared resources (rooms, equipment) with recurring bookings, access control, notifications, and reporting . Supports waitlists, quotas, and role-based permissions. Used by universities including Saarbrücken and Osnabrück libraries for group study room reservations .

- **[MRBS (Meeting Room Booking System)](https://github.com/MeetingRoomBookingSystem/mrbs)**  
  A classic, widely deployed open-source meeting room booking system. PHP/MySQL-based with a straightforward interface for room reservations. Used by Technische Universität Hamburg as a replacement for other solutions . Provides recurring bookings, multiple locations, and basic reporting.

- **[Indico Room Booking](https://github.com/indico/indico)**  
  Room booking module within **Indico**, CERN's open-source event management platform. Indico is a comprehensive platform for managing events, meetings, workshops, and conferences with tools for registration, abstract submission, reviewing, and scheduling. **Includes optional room booking module** . Deployed at CERN since 2002, adopted by the United Nations in 2014, and used by Max-Planck-Institute for Physics with 10,000+ events hosted . Python-based, community-driven, backed by CERN's IT department .

- **[Biletado](https://github.com/biletado)**  
  Open-source booking platform developed for Amt Süderbrarup's Digital Centre in Germany's Smart Cities model project. Enables users to book rooms, resources, and equipment (laser cutters, co-working spaces, workshops) centrally. **GNU GPL licensed** . Features reactive frontend components that integrate into existing websites without redirects, multi-mandate support, and online user handbook. A community of municipalities has formed a working group to optimize and extend the platform .

- **[Study Room Booking (bis-uni-oldenburg)](https://github.com/bis-uni-oldenburg/study-room-booking)**  
  Open-source study room booking system developed for university libraries. Originally designed for group study rooms, configurable for individual workspace booking. Deployed at Universität Rostock with 100+ workspaces .

- **[MArs (UB Mannheim)](https://github.com/UB-Mannheim/MArs)**  
  Open-source workspace reservation solution developed by Universitätsbibliothek Mannheim. Also deployed at Universitätsbibliothek Stuttgart .

- **[bibroomz](https://github.com/bibroomz)**  
  Open-source room booking system developed for university libraries. Originally deployed at TU Berlin (as roomz), now at Humboldt-Universität zu Berlin .

- **[tx-booking (ubleipzig)](https://github.com/ubleipzig/tx-booking)**  
  TYPO3 CMS extension for managing room bookings for frontend users. Created for Leipzig University Library's group study rooms. **Anonymous visitors** get an overview of room occupation; **logged-in users** can book timeslots with configurable maximum bookings per day and location . Features opening hours and closing day management with inheritance rules. PHP 7.4+, TYPO3 11.x .

- **[Room-reservation-management-system](https://github.com/Nu11Cat/Room-reservation-management-system)**  
  Modern meeting room reservation system with intelligent conflict detection and visual booking. Features multi-role management (normal user, admin, super admin), intelligent time selection (hourly/half-hourly), quick recurring bookings, custom booking rules, holiday configuration, and responsive design . Vue 3 + Spring Boot + WebSocket + Redis. Chinese-language project with claimed 95% reduction in meeting room conflicts and 60% improvement in employee satisfaction in a 500-person enterprise deployment .

- **[simple-desk-booking](https://github.com/opariltay/simple-desk-booking)**  
  Easy-to-use desk booking software allowing users to reserve a full-day seat at the workplace. **10 stars** .

- **[WARP (Workspace Autonomous Reservation Program)](https://github.com/sebo-b/warp)**  
  System for managing hybrid office space (assigned desks, hot-desks, parking stalls). Features mobile PWA, admin interface for maps/zones/groups, per-zone booking constraints, assigned seats, disabled seats, auto-book, iCal feed subscriptions, per-zone reminders, configurable booking windows, SAML/LDAP/Azure AD/OIDC authentication, and translations (English, German, French, Spanish, Polish) . Python-based.

- **[OpenDesk](https://github.com/kanwalnainsingh/OpenDesk)**  
  Open-source system for optimizing office desk utilization. Employees reserve desks when planning to work from office. **65 stars, 45 forks** . Features site/building setup with desk capacity, employee reservation management, and booking confirmation alerts. Future plans include SSO, desk map configurations, and organization dashboards .

### Additional Strong Open-Source Options

- **General Booking**: **MRBS** (classic, widely deployed), **Booked Scheduler/LibreBooking** (most mature, GPL-3.0) .
- **Event + Room Booking**: **Indico** (CERN, UN-deployed, room booking module) .
- **Municipal/Public Sector**: **Biletado** (German Smart Cities, GPL) , **Espace sur Demande** (French ANCT, for communal halls) .
- **Desk Booking**: **WARP** (hybrid office, comprehensive features) , **OpenDesk** (65 stars, desk optimization) .
- **Library/Study Room**: **Study Room Booking** (Oldenburg), **MArs** (Mannheim), **bibroomz** (Berlin), **tx-booking** (Leipzig) .

**Frameworks for building custom systems**: Combine **LibreBooking** for general resource scheduling, **Indico** for event management with room booking, **WARP** for hybrid desk and parking reservations, and **Biletado** for municipal/public sector resource booking. Add **PostgreSQL/MySQL** for persistence and **Docker** for deployment.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Conference room scheduling platforms handle potentially sensitive booking and occupancy data; ensure compliance with internal policies and data protection regulations.
- Self-hosted open-source solutions require proper security hardening, regular updates, and backup strategies. The license is free; the operational cost is yours.

---

**Made for facilities managers, workplace experience teams, office administrators, and hybrid workplace strategists.**
Let's make conference room scheduling more open, transparent, and efficient.
