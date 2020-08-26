# my-conda-pip-envs
Contains my pip and conda environments.

#### Create yml file from env.
`conda env export --no-builds > environment.yml`

#### Recreate env from yml file
`conda env create -f environment.yml`

Recreates the environments using the yaml file.

Ref: https://stackoverflow.com/questions/41274007/anaconda-export-environment-file
