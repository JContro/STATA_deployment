# STATA_deployment

This is for Anca's PhD

# Codespaces

in codespace you can run the following commands

```docker run -it --rm   -v $(pwd)/STATA.LIC:/usr/local/stata/stata.lic   -v $(pwd)/code:/code   -v $(pwd)/data:/data   -v $(pwd)/results:/results  dataeditors/stata17:2023-01-10  -b helloworld.do```