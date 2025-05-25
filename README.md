# TaxoGo

**TaxoGo** is a dual-purpose tool for exploring the NCBI Taxonomy database, offering both a command-line interface (CLI) for querying and manipulating taxonomic data and a web-based browser for visualizing the Tree of Life. Built with Go for high-performance data processing and a lightweight HTML/JS frontend with D3.js for interactive visualizations, TaxoGo is an educational and practical tool for life sciences enthusiasts and bioinformaticians.

## Features

### CLI Tool
- Query taxonomic details by TaxID (e.g., name, rank, parent).
- Navigate the taxonomic hierarchy (e.g., list children or lineage).
- Random taxon generator to discover species with details.
- Fast parsing of NCBI's `nodes.dmp` and `names.dmp` files using Go.

### Web Browser
- Interactive Tree of Life visualization using D3.js.
- Search taxa by TaxID or name with detailed information.
- Random taxon feature to explore species interactively.
- Responsive UI for exploring taxonomic relationships.

## License
MIT License. See [LICENSE](LICENSE) for details.
