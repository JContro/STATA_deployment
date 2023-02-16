# STATA_deployment

This is for Anca's PhD

# Codespaces

in codespace you can run the following commands

```docker run -it --rm   -v $(pwd)/STATA.LIC:/usr/local/stata/stata.lic   -v $(pwd)/code:/code   -v $(pwd)/data:/data   -v $(pwd)/results:/results  dataeditors/stata17:2023-01-10  -b helloworld.do```


# Singularity


```sudo apt-get update && \
sudo apt-get install -y build-essential libssl-dev uuid-dev libgpgme11-dev squashfs-tools libseccomp-dev wget pkg-config git cryptsetup
```

```mkdir singularity 
   30  cd singularity/
   31  wget https://github.com/apptainer/singularity/releases/download/v3.8.7/singularity-3.8.7.tar.gz 
   32  tar -xzf singularity-3.8.7.tar.gz 
   33  cd singularity-3.8.7/
   34  ./mconfig &&     make -C builddir &&     sudo make -C builddir install
   35  singularity --version
```



