# sandia.aolabs.io

Static AO Labs showcase for Alan Pham's Sandia National Laboratories NOMAD internship research.

The source deck `NOMAD Final Presentation.pptx` is larger than GitHub's normal file limit, so the live page links the PPTX as a GitHub release asset and hosts the PDF export in the site repo.

## DNS

GitHub Pages is configured with `CNAME=sandia.aolabs.io`.

Porkbun needs one record:

| Type | Host | Answer |
| --- | --- | --- |
| CNAME | sandia | nalalalan.github.io |

After DNS resolves, enable HTTPS enforcement for the GitHub Pages site if GitHub has not enabled it automatically.
