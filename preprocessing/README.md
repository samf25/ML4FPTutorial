Once inside the container:
```
pip install --target=/tmp/pylib h5py
export PYTHONPATH=/tmp/pylib:$PYTHONPATH
python create_hdf5_pixelhits.py -i input.edm4hep.root -o output.h5 --max-r 32
```