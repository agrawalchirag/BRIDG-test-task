# BRIDG-test-task
# Web Crawler Service

This project is a scalable web crawler that fetches and extracts metadata from given URLs. It is designed to handle a large volume of URLs efficiently and is optimized for cost, performance, and reliability.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
  - [Local Setup](#local-setup)
  - [Running Locally](#running-locally)
- [Testing](#testing)
  - [Local Testing](#local-testing)
  - [Deployed Version Testing](#deployed-version-testing)
- [Deployment](#deployment)
- [Additional Documentation](#additional-documentation)
- [Contributing](#contributing)
- [License](#license)

## Prerequisites

- Node.js 20.x

Ensure that Node.js is installed on your system. You can download it from [Node.js official website](https://nodejs.org/).

## Getting Started

### Local Setup

To set up the project locally on your machine, follow the steps below:

1. Clone the repository:
```bash
git clone https://github.com/agrawalchirag/BRIDG-test-task.git
```

2. Navigate to the project directory:
```bash
cd BRIDG-test-task
```

3. Install the necessary packages:
```bash
npm install
```

### Running Locally

To run the server locally, execute the following command:
```bash
node server.js
```

The server will start and listen on the default port 3000 or on the port specified in your environment settings.

## Testing

### Local Testing

To test the functionality of the web crawler locally, use the following URL in your web browser or API testing tool like Postman:
```bash
http://localhost:3000/metadata?url=https://edition.cnn.com/2013/06/10/politics/edward-snowden-profile/
```

### Deployed Version Testing

The web crawler is also deployed to AWS Elastic Beanstalk. You can test the deployed version using the following base URL:

**Base URL:**
```bash
http://web-crawler-env.eba-iqi73zxp.ap-south-1.elasticbeanstalk.com/
```

**Sample Test URL:**
```bash
http://web-crawler-env.eba-iqi73zxp.ap-south-1.elasticbeanstalk.com/metadata?url=https://edition.cnn.com/2013/06/10/politics/edward-snowden-profile/
```


## Deployment

The project is deployed on AWS Elastic Beanstalk. For details on deploying updates to the environment, refer to the AWS Elastic Beanstalk documentation.

## Additional Documentation

- For detailed design and operational strategies, refer to [documentation.md](./documentation.md).
- For implementation details and project breakdown, refer to [implementation.md](./implementation.md).
