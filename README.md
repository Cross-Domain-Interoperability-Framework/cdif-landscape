# CDIF Landscape

**Note:** This is a prototype for internal review.

This repository hosts the landscape project for the CODATA CDIF (Cross Domain Interoperability Framework), showcasing the ecosystem of tools, standards, organizations, and projects supporting interoperable cross-domain data and machine intelligence.

Visit the website at [https://landscape.cdif.org/](https://landscape.cdif.org) to explore the rich and rapidly evolving world of CDIF. 

If you are a developer or implementer, join our community Discord server around Data and Machine Intelligence.

## Contributing

We welcome improvements to data, logos, and documentation.

If you need access or have questions, open an issue or contact the maintainers.

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

Logos used by the landscape tools must be in SVG format. 
The following tools are available for conversion.

### Free
- https://www.freeconvert.com/svg-converter
- https://new.express.adobe.com/home/tools/convert-to-svg

### Paid
- https://vectorizer.ai/
- https://vectormagic.com/


The following websites provide access to generic SVG images and logos:
- https://www.svgrepo.com/
- https://seeklogo.com/

