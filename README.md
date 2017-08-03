# Command Line Parser
**This is a practice project.** Project Ouline/Problem Statment can be found [here](http://pythonpracticeprojects.com/command-line-parser.html).

## Parce
Parse is the name I gave to this option parsing module. This option parse is very basic and is only made to cover the requirements listed in the link at the top of this page.

### Usage
```python
from parce import OptionParser

parser = OptionParser()
parser.add_option('r')
parser.add_option(('f', 'file'), required=True, argument=True)
```
