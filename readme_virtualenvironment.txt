To create a virtual environment in a local directory:
1. Launch anaconda prompt
2. go to the file directory you want your virtual environment to be in
3. python -m venv cuda
4. cuda\scripts\activate
5. pip3 install matplotlib numpy pylzma ipykernel jupyter

To initiate the CUDA virtual environment on jupyter:
1. open anaconda prompt 
2. go to the directory with the virtual environment installed
3. python -m ipykernel install --user --name cuda --display-name CUDA