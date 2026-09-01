# QuickEV

QuickEV (Quick Environment Volunteer) is a prototype web application that centralizes information about natural disasters in Indonesia and connects the public with volunteering opportunities, volunteer communities, and donation channels. It was developed as a final project for COMP6100001 – Software Engineering and COMP6884001 – Agile Software Development courses.

## Table of Contents

- [Overview](#overview)
- [Background](#background)
- [Objectives](#objectives)
- [Key Features](#key-features)
- [Project Links](#project-links)
- [Group Members](#group-members)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Documentation](#documentation)

## Overview

Indonesia is highly prone to natural disasters. According to Indonesia's National Disaster Management Agency (BNPB), 2022 alone recorded 3,544 disaster events, resulting in 858 deaths, 37 missing persons, 8,733 injuries, and over 6.1 million people affected or displaced. Despite widespread public willingness to help through donations or volunteering, information about disaster locations, victims' needs, and how to volunteer remains scattered and poorly organized.

QuickEV addresses this gap by providing a centralized digital platform where volunteers can find relevant opportunities, join volunteer communities, and where the public can easily contribute donations, either as money or goods, to disaster victims.

## Background

The project aims to develop a functional prototype that supports disaster response coordination through technology. The core problem identified is the lack of a unified platform connecting volunteers, communities, and donors with real disaster relief needs.

## Objectives

- Provide a digital platform that makes it easy for the public to contribute to social and humanitarian activities, particularly disaster response, in Indonesia.
- Optimize public participation in helping disaster victims, whether through material donations or volunteering, by offering centralized information and accessible registration features.
- Build a solid, geographically distributed volunteer community capable of fast, effective, and well-targeted disaster response.
- Reduce the impact of natural disasters on affected communities, in terms of casualties, material loss, and psychological trauma, through responsive and adequate volunteer support.
- Support government disaster mitigation and post-disaster recovery programs through accessible information technology.

## Key Features

- **Cari Kegiatan (Find Activities)**: Volunteers can register to help directly at disaster locations based on their skills and preferences.
- **Cari Komunitas (Find Communities)**: Volunteers can join volunteer communities spread across different regions to take real, collective action.
- **Donasi (Donation)**: The public can easily channel monetary or material donations according to victims' needs.
- **Sign In**: User authentication for volunteers and organizations accessing the platform.

## Project Links

- Web application design (Figma): [View on Figma](https://www.figma.com/design/ESKGFw69cYc9wHIHeJqhBp/QuickEV?node-id=0-1&t=5UM8WOBYt8iO7QFw-1)
- GitHub repository: [View on GitHub](https://github.com/jonathanafernandi/QuickEV)
- Presentation slides: [View Presentation Slides](https://drive.google.com/file/d/1Heq-5c0tkb6TKeoZ56HU3VEDEqYx2xDq/view?usp=sharing)

## Group Members

| Name | Student ID |
|---|---|
| Tisha Jillian | 2602078410 |
| Tara Nirmala Kusuma | 2602084893 |
| Jonathan Alvindo Fernandi | 2602089143 |
| Vinson Luckianto | 2602091066 |
| Efran Nathanael | 2602151891 |

**Supervising Lecturers**: Ghinaa Zain Nabiilah, S.Kom., M.Kom. & Anderies, B.Eng., S.Kom., M.Kom.

## Tech Stack

| Layer | Technology |
|---|---|
| Backend | ASP.NET |
| Frontend | HTML, CSS |
| Database | SQL Server |
| UI/UX Design | Figma |
| Version Control | GitHub |

**ASP.NET** was selected for its ease of development, strong performance (compiled to CLR rather than interpreted), built-in security features (cookie authentication and URL authorization modules), and cross-platform support. **Figma** enables real-time collaborative design of the interface and interactive prototypes for the Home, Cari Kegiatan, Cari Komunitas, Donasi, and Sign In pages. **GitHub** serves as the central repository for version control, branching, and pull request-based collaboration among team members.

## Getting Started

### Prerequisites

- .NET SDK
- SQL Server
- A code editor such as Visual Studio or Visual Studio Code

### Setup

```bash
git clone https://github.com/jonathanafernandi/QuickEV.git
cd QuickEV
dotnet restore
dotnet ef database update
dotnet run
```

## Documentation

Full project documentation, including background, literature review (ASP.NET, Figma, GitHub), implementation stages, budget justification, activity schedule, and team biodata, is available in the PKM-KC proposal PDF included in this repository's `docs/` folder. Software development documentation, including Scrum requirements, product backlog, sprint backlog, and sprint activities, is maintained separately as part of the team's Agile process artifacts.
