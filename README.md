# Odoo CE Developer Workspace for Creation of Modules

>This project implements a workspace to develop modules for Odoo Community Edition in different versions.

## How to Install

- Install Visual Studio Code in your computer.
- Install Docker Desktop in your computer.
- Clone this repository using **git clone**.
- Run docker compose file: **``docker compose up -d --build --force-recreate``**
- Install extensions for VS Code: "Mono Kai Pro", "Python Indent", "Python Envinronments", "Pylance", "Python", "Python Debugger" and "Dev Containers".
- Open VS Code with a remote connection to Docker, attaching the correct container (depends on the version of Odoo).
- After running Odoo, to start debugging mode, in VS Code select the Debugger, press **F5** and set breakpoints in the code (for Python or Javascript).

## Odoo Versions

- Odoo 17 Community Edition
- Odoo 18 Community Edition
- Odoo 19 Community Edition

## Important Files in Every Version

- **dockerfile**: Most important file to create an Odoo image.
- **docker-compose.yml**: Compose that creates all the basic infrastructure for Odoo.
- **odoo.conf**: For the configuration of Odoo, starting with DB connection, data and addons.
- **.env**: Environment variables for containers.
- **requirements.txt**: All libraries that you can requires additionally for your modules.

## Example of Modules Used

- [Factura Electronica](https://apps.odoo.com/apps/modules/18.0/l10n_pe_edi_odoofact) by OPeru.
- [Open HRMS Core](https://apps.odoo.com/apps/modules/19.0/ohrms_core) by Cybrosys Techno Solutions.

## Author

**Sergio Zambrano** 👤

- GitHub: [@sergiomauz](https://github.com/sergiomauz)
- X: [@sergiomauz](https://x.com/sergiomauz)
- Linkedin: [Sergio Zambrano](https://www.linkedin.com/in/sergiomauz/)

## Contributing 🤝

Contributions, issues and feature requests are welcome!. Feel free to check the [issues page](../../issues/).

## Show me your support

- Give a ⭐️ if you like this project.
- If you found this project helpful and would like to buy me a coffee, you can do so using Paypal:

[![Donate](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/donate?business=sergio.mauz88@gmail.com&currency_code=USD)

## License 📝

Check [Odoo License](https://www.odoo.com/documentation/19.0/legal/licenses.html).
