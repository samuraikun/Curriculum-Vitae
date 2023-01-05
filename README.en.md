# My Resume

# Basic Information

| key | value|
|-----|------|
| Name | Yuichi Kojima |
| https://github.com/samuraikun | Qiita | https://github.com/samuraikun | https://github.com/samuraikun
| Qiita | https://qiita.com/samuraikun |
| Zenn | https://zenn.dev/samuraikun |

# Skills

## Programming Language, Tools
Ruby, Ruby on Rails, JavaScript, TypeScript, Vue.js, React.js, AWS, Terraform, CircleCI, Github Actions

## Cloud Computing

### AWS (Certifications)
- AWS Solution Architect Associate, March 2020
  - Online certificate: https://www.credly.com/badges/1d2b0dfe-7360-4449-b9de-68d050a92683/public_url
- May 2022 AWS Solution Architect Professional
  - Online Certificate: https://www.credly.com/badges/24dbed30-f1d5-4eb9-9af5-94a85e761a72/public_url

## Language

### Japanese
- Native level

### English
- Daily conversation level
- English level to be able to read official documents in English
- TOEIC L&R 790
  - CEFR B1 level
    - https://www.efset.org/ja/cefr/b1/

# Job History

## 2019/01/7 - 2023/01/31 Crevo Inc.
- Working as a Software Engineer.

### Main Responsibilities.
- Development, maintenance and operation of video production management tool (Saas)
- Server side development with Rails
- Front-end development with Vue.js, Vuex
- Design and implementation of maintainable CSS using BEM and Grid Layout
- Component design and implementation based on Atomic Design
- Management and operation of UI components using Storybook
- Improvement of front-end build environment using Webpack and Webpacker (Webpack wrapper for Ruby on Rails)
- Construction and modification of infrastructure using AWS
- Selection and implementation of monitoring Saas and monitoring of each infrastructure resource
  - Deployment of Mackerel
  - Monitoring and alert settings for each server
  - Monitoring and alert settings for each AWS service
- Construction of video transcoding infrastructure using AWS MediaConvert
  - Design and implementation for delivery of video files uploaded by clients in HLS and MPEG-DASH formats
  - Migration from ElasticTranscoder to MediaConvert

## 2021/03 - 2022/12 pipon inc.
- Working part time
- Building and operating the infrastructure of a presentation material retrieval system for pharmaceutical R&D for a large German pharmaceutical company.
  - https://prtimes.jp/main/html/rd/p/000000006.000061053.html
- Built all AWS infrastructure from scratch by myself using Terraform

<details>
<summary>Architectural overview of the built infrastructure</summary>.

! [image](https://user-images.githubusercontent.com/7115171/183028236-3daefdaa-27fd-4942-be45-7d2e18ef8332.png)
</details>

## 2019/02/01 - 2019/04/03 Giraffe Inc.
- Development of a free market service specializing in used smartphones.
- Development by remote with 2 weekends per week operation.
- Responsible for front-end development with React, TypeScript.

## 2016/04/01 - 2018/08/31 Sansan Corporation
- https://jp.corp-sansan.com/
- Worked as a Web Application Engineer

### Main Responsibilities.
- Development and operation of business card databasing service using Ruby on Rails
  - Divide business card databasing into several processes, isolate each process as a microservice, and perform API integration
  - Input system specialized for business cards using human operator input of each item (name, company name, address, etc.) from actual business card images, image recognition using OCR, and automatic input using machine learning.
  - Input system for business cards in a variety of languages
    - Japanese, English, Chinese, Korean, French, German, Spanish, Portuguese, Thai, etc.
  - Normalization process for various business card patterns
  - Implementation of name matching logic using some information on business cards

# Activities outside of business

- Investigating and experimenting with serverless and front-end technologies that I am personally interested in.
- Participating in events related to web technology, and outputting my experience and knowledge.

### Golang
- I attended a 3 month Go language training course organized by CyberAgent, Inc.
  - https://www.cyberagent.co.jp/news/detail/id=26667

### Vue.js

- Wrote an article about Vue.js while developing a TODO app composed of Vue.js & Electorn
  - https://qiita.com/samuraikun/items/bb2939296bbead341293

### React.js

- Created a full stack (MongoDB, Express, React, Node.js) JavaScript application for learning
  - https://github.com/samuraikun/node_with_react_app
- React application combining React Hooks and GraphQL
  - https://github.com/samuraikun/appsync-amplify-sample-app-for-techbookfest7

### Nuxt.js & Rails on Docker
- https://github.com/samuraikun/rails-nuxt-typescript-docker-example

### Serverless
- https://qiita.com/samuraikun/items/bf0936a5d3386c4914fa

### Firebase
- https://qiita.com/samuraikun/items/dfe7d1081f62359b0dcd
- https://qiita.com/samuraikun/items/ce5d977d63bcafa43d0e

### Book Author
- I wrote a book "Serverless Single Page Application with Firebase" at Tech Book Fest 5.
  - https://techbookfest.org/event/tbf05/circle/47080001
  - Later published as a commercial journal
    - https://amzn.asia/d/fAUCoJa
- Wrote a book (coterie magazine) titled "Introduction to Serverless Development with Amplify and AppSync" at Tech Book Fest 7.
  - https://booth.pm/ja/items/1574736

## What I want to do in the future

## While focusing on backend development, architectural design of cloud-native systems, and infrastructure construction and operation monitoring using IaC.

### Perspective of backend development
- Development and refactoring of backend API except frontend using Ruby on Rails
  - Refactoring based on PORO (Pure Old Ruby Object) by dividing Fat Model, Fat Controller implementation into different responsibilities, etc.
- Backend development, test-driven development and refactoring with Go language
- Modeling and development based on CQRS (Command Query Responsibility Separation) as well as ActiveRecord pattern as represented in Rails
- Design and implementation of systems based on domain-driven design

### Cloud (infrastructure) perspective
- Architectural design of systems using AWS, etc.
- System construction and operation using AWS or GCP cloud computing with Terraform
- Construction and improvement of web application infrastructure using container technology
- Construction and improvement of DevOps environment using CircleCI and Github Actions
- KPI development and operation from a system performance perspective
- Establishment and regular monitoring of system monitoring system using monitoring tools such as Datadog, Prometheus, Grafana, etc.
- Establishment and operation of analysis infrastructure based on Service Level Indicators (SLI) and Growth Hack perspective.

## What we want to do/experienced
- System design based on AWS Well Architected, combining AWS services
- Build and manage infrastructure using Terraform or other IaC tools
- Development of infrastructure-related plug-ins using Go language
- Establishment of metrics monitoring system for each resource using monitoring tools (Mackerel, Datadog, Prometheus), SLOs and SLIs.
- Building and improving CI/CD infrastructure using CircleCI and Github Actions
- Use of some GCP services
  - BigQuery
  - Cloud Run
  - StackDriver
