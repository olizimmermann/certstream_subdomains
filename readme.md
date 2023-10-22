# CertStream Subdomains Repository

![GitHub License](https://img.shields.io/badge/license-MIT-blue.svg)

**CertStream Subdomains** is a repository that provides lists of registered subdomains obtained from CertStream. These subdomains can be used for various purposes, such as bruteforcing, discovery, penetration testing, and more. CertStream is a service that monitors SSL/TLS certificates for changes, making it a valuable source for discovering new subdomains as they are registered.

This repository is designed to assist security professionals, researchers, and enthusiasts in their efforts to uncover and analyze subdomains associated with a target domain.

## Table of Contents

- [About CertStream Subdomains](#certstream-subdomains-repository)
- [Getting Started](#getting-started)
- [Data Sources](#data-sources)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

To get started with **CertStream Subdomains**, follow these steps:

1. Clone the repository to your local machine:
   ```shell
   git clone https://github.com/olizimmermann/certstream_subdomains.git
   ```

2. Navigate to the project directory:
   ```shell
   cd certstream_subdomains
   ```

3. Start exploring the subdomain lists available in the repository.

## Data Sources

The subdomains in this repository are collected from CertStream, a real-time certificate transparency log monitoring service. CertStream continuously monitors SSL/TLS certificates and logs the information about newly registered certificates. This data is then processed to extract subdomains, making it a valuable source for subdomain discovery.

## Usage

You can use the subdomain lists in this repository for various purposes, including:

- **Subdomain Discovery:** Use these lists to discover subdomains related to a target domain.

- **Bruteforcing:** Utilize the subdomains for brute-force attacks and testing the security of these subdomains.

- **Penetration Testing:** Incorporate the subdomains into your penetration testing efforts to identify potential security vulnerabilities.

- **Research:** Study the subdomains for research and analysis related to domain usage and certificate changes.

Please ensure that you use these subdomains responsibly and ethically, adhering to all applicable laws and regulations.

## Contributing

We welcome contributions to this repository. If you have additional subdomains to share or would like to make improvements, please follow these steps:

1. Fork the repository.

2. Create a new branch for your changes:
   ```shell
   git checkout -b feature/your-feature
   ```

3. Make your changes, add subdomains, or implement new features.

4. Commit your changes:
   ```shell
   git commit -m "Added new subdomains"  
   ```

5. Push your changes to your forked repository:
   ```shell
   git push origin feature/your-feature
   ```

6. Create a pull request in the main repository. Please provide a clear description of your changes.

Contributions will be reviewed and, if appropriate, merged into the main repository to benefit the community.

## License

This repository is open-source and released under the [MIT License](LICENSE). You are free to use the subdomains for various purposes, but please adhere to ethical and legal standards when doing so.

Happy subdomain discovery and testing! If you have any questions or suggestions, feel free to reach out.

For more information, visit the official CertStream website: [CertStream](https://certstream.calidog.io/).