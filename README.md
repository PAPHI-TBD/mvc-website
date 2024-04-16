# Mingley

## Project Description
Mingley aims to help people find friends, events, and a community in new areas. We hope to foster safe and spontaneous hangouts for it's users.

Tech Stack: 
- Website
  - HTML + CSS (Bootstrap)
    - Plan to migrate to React later
  - Azure Cloud Hosting
- App
  - SwiftUI
  - Firebase

## Dependencies
- Download C# and C# Dev Kit in VS Code Extensions
- Download .NET SDK 6.0.0 for your OS
- Create a trusted security certificate
- Run and debug

## Development and CI/CD Pipeline

## Branches Overview
The development pipeline is structured around the branches within the repository. Each branch represents a stage of development, allowing for parallel workstreams and controlled integration.

## Initial Development
At the outset, development is segmented into four main branches, each corresponding to a key aspect of the application:

- `home-screen`
- `goals-screen`
- `careers-screen`
- `roadmap-screen`

## Development Integration
The `development` branch consolidates changes from the initial four branches, representing the first iteration of the complete application. QA procedures, including sanity and regression testing if necessary, are executed to identify and resolve bugs.
All modifications originate from the lower-level feature branches and are subsequently merged into `development` to ensure alignment.

## Staging
Once all identified bugs are resolved and the iteration reaches a stable state, changes are merged into the `staging` branch. This branch mirrors the production environment, with the inclusion of committed functionalities ready for deployment.

## Production Deployment
Upon decision, the `staging` branch is merged into the `production` branch, marking the release for deployment. With each push to the `production` branch, the CI/CD process is automatically initiated. This triggers deployment to the live destination, ensuring seamless updates to the production environment.

## Credits
Founders:
- Joshua De Chavez (Full Stack Developer + Project Manager)
- Clare Shen (Backend Developer)
- Joshua Sam Badshah (Business Team Lead)

Members: 

## Licenses
You can not use any code from the Mingley organization. 
