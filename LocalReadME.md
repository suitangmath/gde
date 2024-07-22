# Environment Setup

1. It is always recommended to setup a virtual env. 
  - Initialize ```python -m venv <your_env_name>```
  - activate ```source <your_env_name>/bin/activate```
  - deactivate (not required) ```source deactivate```
2. Install dgl following instructions from [link](https://www.dgl.ai/pages/start.html). Note to choose the approiate version.
```pip install  dgl -f https://data.dgl.ai/wheels/torch-2.3/cu121/repo.html```
3. Run the remaining packages listed in `requirements.txt`.
```pip install -r requirements```
