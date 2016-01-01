# src/python/multi-platform/BUILD
python_binary(name='multi-platform',
  source = 'main.py',
  dependencies = [
    ':psutil',  # defined in requirements.txt
  ],
  platforms=[
    'linux-x86_64',
    'macosx-10.7-x86_64',
  ],
)

# Defines targets from specifications in requirements.txt
python_requirements()
