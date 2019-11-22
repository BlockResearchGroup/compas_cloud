# compas_cloud
compas_cloud is the further development of `compas.rpc` module. It uses websocktes instead of RESTful APIs to allow bi-directional communications between various front-end programs like Rhino, GH, RhinoVault2, blender or web-based viewers that are implemented in different enviroments including CPython, IronPython and Javascript. It also allows to save certain variables to backend inside a user session to avoid overheads created by redundant data transfers.



### install from source
`pip install -e .`


### install for Rhino
`python compas_rhino.install -p compas_cloud`
