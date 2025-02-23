# Sign Recognition Example

[Python Virtual Environment Guide](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/)

1. Cloning this source
2. Init Python Virtual Environment
3. Install requirements package for the project (must change to virtual environment first)
```
pip install -r './requirements.txt'
```
4. Install [Train](https://btsd.ethz.ch/shareddata/BelgiumTSC/BelgiumTSC_Training.zip) dataset, [Test](https://btsd.ethz.ch/shareddata/BelgiumTSC/BelgiumTSC_Testing.zip)
5. Extract all Test zip, Train zip to Testing, Training folder, the final structure must be `dataset/Testing/00000`, `dataset/Testing/00001`,...

Ref: https://medium.com/@hilluri/image-classification-with-good-old-simple-neural-networks-6c2e2ed38cc1