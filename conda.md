## Conda Cheat Sheet
| what                | command       
| ------------------- |:-------------
| **new**  environment|   `conda create --name env_name python=3.7`
| **delete**  environment|   `conda env remove -n env_name`
| **new from file**  environment|   `conda create -f file.yml -n env_name`
| **export to file** current environment| `conda env export -f filename.yml`
| **activate**  environment |   `source activate env_name`
| **list all** environments |   `conda env list`
| **list packages** of current env, of xy_env| `conda list`, `conda list xy_env`
| **clone** from existing environment| `conda create --clone my_env -n my_env_copy`
| **install packages**| `conda install package_x`, `conda install package_x=1.1` 
| **update** package, all| `conda update package_x`, `conda update --all`

