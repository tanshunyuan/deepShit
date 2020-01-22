# Using pyenv
Install a version of python for this project
```bash
pyenv install 3.6.3
```

# Create virtual environment for this project
```bash
pyenv virtualenv 3.6.3 deepShit
```

# Activate my virtual environment
```bash
pyenv local deepShit
pyenv activate deepShit
```

# Remove my virtual environment
```bash
pyenv uinstall deepShit
```

# Configure poetry to create virtual environments inside the project's root directory
```bash
poetry config virtualenvs.in-project true
```
