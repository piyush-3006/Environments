Setingup the environment for machine learning and spark

Create .yml. Running this command will create a new conda environment that is provisioned with all libraries listed above.

``` .sh```
```conda env create -f <name.yml>```

Verify that the bdap environment was created in your environments:

```conda info --envs```

Cleanup downloaded libraries (remove tarballs, zip files, etc):

 ```conda clean -tp```

Uninstalling

To uninstall the environment:

 ```conda env remove -n <name.yml>```
