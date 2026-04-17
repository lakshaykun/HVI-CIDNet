# changing version of python in colab
!pip install -q condacolab
import condacolab
condacolab.install()
### After install, run:
!conda create -n my_env python=3.10
