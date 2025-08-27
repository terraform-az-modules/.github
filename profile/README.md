# terraform-az-modules
<img width="1024" height="292" alt="Untitled design" src="https://github.com/user-attachments/assets/f8d028c6-070d-4b66-a93f-8ab3b63d3e60" />




![Terraform](https://img.shields.io/badge/Terraform-Azure-blue?logo=terraform)
![Azure](https://img.shields.io/badge/Microsoft-Azure-0078D4?logo=microsoft-azure)

## 🌍 Open Source Terraform Azure Modules

Welcome to the **terraform-az-modules** organization!  
We provide a collection of reusable, production-ready **Terraform modules for Microsoft Azure** to help you deploy secure, scalable, and compliant infrastructure quickly and consistently.

All modules in this organization are **open source** and maintained by the community.

---

## 📦 Available Modules

Below are the Terraform modules published under this organization.  
Click the links to explore and use them directly:

- [terraform-az-modules/vm](https://github.com/terraform-az-modules/vm)  
- [terraform-az-modules/vnet](https://github.com/terraform-az-modules/vnet)  
- [terraform-az-modules/storage](https://github.com/terraform-az-modules/storage)  
- [terraform-az-modules/aks](https://github.com/terraform-az-modules/aks)  
- [terraform-az-modules/keyvault](https://github.com/terraform-az-modules/keyvault)  
- [terraform-az-modules/sql-database](https://github.com/terraform-az-modules/sql-database)  
- [terraform-az-modules/app-gateway](https://github.com/terraform-az-modules/app-gateway)  
- [terraform-az-modules/load-balancer](https://github.com/terraform-az-modules/load-balancer)

> ℹ️ The above list is just a sample. Please update it with all the repositories from your organization.

---

## 🚀 Why use these modules?

- **Standardized**: All modules follow best practices and naming conventions.  
- **Reusable**: Designed for multiple projects, environments, and use cases.  
- **Secure**: Implements Azure security recommendations wherever possible.  
- **Tested**: Modules are regularly tested with the latest Terraform and Azure provider releases.  
- **Open Source**: Contributions and improvements are always welcome!  

---

## 📖 Usage Example

```hcl
module "vnet" {
  source  = "github.com/terraform-az-modules/vnet"
  version = "x.y.z"

  name                = "my-vnet"
  address_space       = ["10.0.0.0/16"]
  location            = "eastus"
  resource_group_name = "rg-networking"
}
```

## 🤝 Contributing

We ❤️ contributions from the community!

1. Fork the repo you want to improve  
2. Create a new branch (`git checkout -b feature/my-feature`)  
3. Commit your changes (`git commit -m 'Add my feature'`)  
4. Push to the branch (`git push origin feature/my-feature`)  
5. Open a Pull Request  

Please check our [CONTRIBUTING.md](CONTRIBUTING.md) (if available) for guidelines.

---

## 🛠️ Support

- For questions, open a [Discussion](https://github.com/orgs/terraform-az-modules/discussions) in this organization.  
- For bugs and feature requests, open an [Issue](https://github.com/terraform-az-modules) in the relevant module repo.  

---

## 📜 License

All modules in this organization are released under the [MIT License](LICENSE).  
You are free to use, modify, and distribute them in your projects.

---

## 📢 Stay Connected

- ⭐ Star this organization to get updates on new modules.  
- 📝 Follow our [Releases](https://github.com/orgs/terraform-az-modules/repositories?q=&type=all&language=&sort=stargazers) to stay up-to-date.  
- 💬 Share feedback and suggest improvements in [Discussions](https://github.com/orgs/terraform-az-modules/discussions).
