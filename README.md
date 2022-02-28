# Utils sample package

just a small test of a python private package

### install:

```bash
pip install git+ssh://git@github.com/henriquemsouza/utils-sample-package.git
```

### Use

```python
import utilsSample

utilsSample.sample()
```

### Working with requirements.txt
<p>pip freeze > 'requirements.txt' </p>

the pip freeze will generate something like this:

```.txt
...
utilsSample @ git+ssh://git@github.com/henriquemsouza/utils-sample-package.git@42194c021e207363f9e5a78d7ebfa885ef50743c
...
```

after 'git@' is the commit hash or git tag to specify the code version that you wanted


if the freeze gives an error in the installation change the line to


```.txt
...
git+ssh://git@github.com/henriquemsouza/utils-sample-package.git@42194c021e207363f9e5a78d7ebfa885ef50743c
...
```

