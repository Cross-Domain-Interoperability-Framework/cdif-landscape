# CDIF Landscape

**Note:** This is a prototype for internal review.

This repository hosts the landscape project for the CODATA CDIF (Cross Domain Interoperability Framework), showcasing the ecosystem of tools, standards, organizations, and projects supporting interoperable cross-domain data and machine intelligence.

Visit the website at [https://cross-domain-interoperability-framework.github.io/cdif-landscape/](https://cross-domain-interoperability-framework.github.io/cdif-landscape/) to explore the rich and rapidly evolving world of CDIF. 

If you are a developer or implementer, we encourage you to join our community [Discord](https://discord.gg/v8e5AMtshT) server around Data and Machine Intelligence.

## Contributing

We welcome contributions! Here's how to get started:

### Adding an Entry to data.yml

Before submitting your contribution, gather the following information:

- **Name**: The official name of the tool, standard, organization, or project
- **Category**: The landscape category it belongs to
- **Description**: A brief description (2-3 sentences)
- **Website URL**: Link to the official website or repository
- **Logo**: SVG file (see [SVG Resources](#svg-resources) section)
- **Organization/Repository**: GitHub organization or repository link (if applicable)
- **Founded Year**: Year the project or organization was established

Refer to the existing entries in `data.yml` for examples of the required format.

**For contributors familiar with GitHub:**
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/your-contribution`)
3. Make your changes (update data.yaml and add images under logos directory)
4. Submit a pull request with a clear description of your changes

**For everyone else**
File a [GitHub issue](https://github.com/cross-domain-interoperability-framework/cdif-landscape/issues) with:
- Your name and affiliation
- Description of the addition or change you'd like to make
- Relevant links or documentation

## Run Locally

The CDIF landscape is built with the [CNCF Landscape2](https://github.com/cncf/landscape2) platform.
See the project documentation for installation instructions and additional information.

**Building the Website:**

The build process creates the website from data files. Run this command in your terminal:

```bash
landscape2 build \
  --data-file data.yml \
  --settings-file settings.yml \
  --guide-file guide.yml \
  --logos-path logos \
  --output-dir build
```

**Running the Website Locally:**

Once built, use Landscape2 to serve the website locally:

```bash
landscape2 serve --landscape-dir build
```

This starts a local server and opens the website in your web browser at http://127.0.0.1:8000.

## SVG Resources

Logos used by the landscape tools should preferably be in SVG format. 
The following tools are available for conversion.

Free:
- https://www.freeconvert.com/svg-converter
- https://new.express.adobe.com/home/tools/convert-to-svg

Paid:
- https://vectorizer.ai/
- https://vectormagic.com/


The following websites provide access to generic SVG images and logos:
- https://www.svgrepo.com/
- https://seeklogo.com/


## License

This project is licensed under the Creative Commons Attribution 4.0 International License (CC BY 4.0).