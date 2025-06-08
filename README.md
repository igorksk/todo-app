# todo-app #
This repository hosts a simple todo application API built using the latest features of .NET 8 and ASP.NET Core 8, focusing on the lightweight and streamlined development experience provided by Minimal APIs. The app utilizes an PostgreSQL database for storing todo items.

## Table of Contents

- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Architecure Overview](#architecure-overview)
- [Design Patterns](#design-patterns)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)
- [Support](#support)

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

- [.NET 8 SDK](https://dotnet.microsoft.com/download/dotnet/8.0)
- Docker

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/poorna-soysa/todo-app.git
   ```
2. Navigate to the project directory
   ```sh
   cd grpc-demo
   ```
3. Restore dependencies:
   ```sh
   dotnet restore
   ```
   
# Architecure Overview

This template follows the Vertical Slice Architecture, which organizes code by features rather than technical concerns. Each feature is self-contained, promoting high cohesion and low coupling.

# Design Patterns
* CQRS

## Features

- **Built with .NET 8**: Utilizes the latest features for efficient development.
- **Docker**: Facilitates containerized deployments
- **PostgreSQL**: Powerful relational database for data storage.
- **Health Check**: Standardized approach for monitoring and assessing the operational status of systems.

## Technologies Used

- **.NET 8**
- **Docker**
- **PostgreSQL**
- **EF Core**

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Creat a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Support

If you find this project helpful, consider buying me a coffee!

[![Buy Me a Coffee](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/poorna.soysa)


