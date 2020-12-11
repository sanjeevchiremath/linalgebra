# Linear Algebgra
> Project to experiemnt nbdev and learn Linear Algebra


This is README and also the index of your documentation.

## Install

Following steps are Pre-requesits:
<ul>
    <li> Create Project specific Environment, <code> conda env crete linalgebra</code></li>
    <li>Activate the environment using <code>conda activate linalgebra</code></li>
    <li>Install [fastai nbdev] (https://www.fast.ai/2019/12/02/nbdev/ "fastai") - <code>conda install -c fastai nbdev</code></li>
    <li> Create new project / module template <code> nbdev_new</code></li>
    <li> install nb dev it hooks <code>nbdev_install_git_hooks </code></li>
</ul>

When budling docs using <code>nbdev_build_docs</code> I encountered error "No such ernel named python3", to avoid this install conda_kernels <code> conda install nb_conda)kernels</code> credit: (https://stackoverflow.com/questions/38257138/jupyter-no-such-kernel-named-python3)
    
conda install nb_conda_kernels

## How to use

```python
say_hello("Sanjeev!")
```




    'Hello Sanjeev!!'


