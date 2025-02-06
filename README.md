<a id="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/saigonchildren/docs">
    <img src="./docs/assets/icons/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Saigonchildren M2M Project Documentation</h3>

  <p align="center">
    Official documentation for development and deployment
  </p>
</div>

## Documentation

This documentation is built using [Mkdocs Material](https://squidfunk.github.io/mkdocs-material/), a modern documentation framework that generates beautiful and responsive documentation sites.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Getting Started

Ensure you are in the root directory before proceeding with the installation steps.

### Clone the Repository

```sh
git clone git@github.com:saigonchildren/docs.git
cd docs
```

### System Requirements

- Python 3.12 or higher
- pip (Python package installer)
- Git

### Installation Steps

1. Create and activate a virtual environment (recommended):

```sh
python -m venv .venv

# On Windows
.venv\Scripts\activate

# On macOS/Linux
source .venv/bin/activate
```

2. Install required packages:

```sh
pip install mkdocs mkdocs-material
```

3. Verify installation:

```sh
mkdocs --version
```

### Development

1. Start the development server:

```sh
mkdocs serve
```

2. Open your browser and visit `http://localhost:8000`

### Building Documentation

To build the static site:

```sh
mkdocs build
```

The built documentation will be available in the `site` directory.

### Deployment

The documentation is automatically deployed through CI/CD pipeline when changes are pushed to the main branch.

## Contributing

1. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
2. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
3. Push to the Branch (`git push origin feature/AmazingFeature`)
4. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>
