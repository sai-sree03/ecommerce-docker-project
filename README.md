# Dockerized E-Commerce Application with Razorpay and Grafana

## Project Overview

This project aims to develop and deploy a basic e-commerce application using Docker containerization. The application will provide product browsing, shopping cart, checkout, and order management functionality, along with test payment integration and infrastructure monitoring.

## Objectives

* Deploy an e-commerce platform using WooCommerce and WordPress.
* Configure the application and its database using Docker containers.
* Add sample products and verify shopping cart and checkout functionality.
* Integrate Razorpay in Test Mode to simulate payments without real transactions.
* Configure Grafana to monitor CPU usage, memory usage, disk usage, and container status.
* Document the deployment process and demonstrate the working application.

## Proposed Technology Stack

| Component            | Technology                |
| -------------------- | ------------------------- |
| E-commerce platform  | WooCommerce               |
| Content management   | WordPress                 |
| Database             | MySQL                     |
| Containerization     | Docker and Docker Compose |
| Payment gateway      | Razorpay Test Mode        |
| Metrics collection   | Prometheus                |
| Monitoring dashboard | Grafana                   |
| Container metrics    | cAdvisor                  |

## Proposed Architecture

The application will run as a collection of Docker services. WordPress and WooCommerce will provide the storefront and shopping functionality, while MySQL will store application data. Razorpay Test Mode will support simulated checkout payments. Prometheus and Grafana, together with a container metrics exporter, will provide infrastructure monitoring.

## Implementation Plan

1. Prepare the development environment.
2. Configure the e-commerce application and database.
3. Add sample products and test cart functionality.
4. Integrate and verify Razorpay test payments.
5. Configure monitoring and Grafana dashboards.
6. Test the complete setup and document the results.

## Project Status

**Phase 1: Planning and repository setup**

The project scope, proposed technology stack, and implementation plan have been documented. Environment setup and application deployment are the next steps.

## Safety Note

Only Razorpay test credentials and test transactions will be used. No real payment transactions will be performed.
