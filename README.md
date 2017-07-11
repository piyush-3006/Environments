Setup the environment.

git clone <link>
cd learn-spark-python

    You should already have a GitHub account, and should have installed git in your system to be able to clone the repo in the last instruction. If not, you can download the repository here, extract the folder, cd into it, and then continue.

If you are on Windows, rename meta_windows_patch.yml to meta.yml.

Create .yml. Running this command will create a new conda environment that is provisioned with all libraries listed above.

conda env create -f environment.yml

Verify that the bdap environment was created in your environments:

conda info --envs

Cleanup downloaded libraries (remove tarballs, zip files, etc):

conda clean -tp

Uninstalling

To uninstall the environment:

conda env remove -n <.yml>
