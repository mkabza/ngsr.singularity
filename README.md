# ngsr.singularity
Singularity image recipes for NGS data analysis

## Building images

```bash
# Build a Singularity image from a recipe
sudo singularity build image_name.simg recipes/image_name.def
```

## Available recipes

| Recipe              | Description                                          |
|---------------------|------------------------------------------------------|
| sratools            | NCBI SRA Tools                                       |
| rnaseq              | Tools for basic RNA-Seq analysis                     |
