<h2 align="center">About Me </h2>

```python
from typing import Tuple, List, Dict

class Fivex:
    pass

class Attributes(Fivex):
    @property
    def contact(self) -> Tuple[str, str, str]:
        telegram = "t.me/justfivex"
        email    = "fivex.vn@gmail.com"
	    
        return telegram, email

    @property
    def life(self) -> Tuple[List[str], int]:
        langs = ['Vietnam', 'English']
        age   = 21
		
        return langs, age
	
    @property
    def coding(self) -> Tuple[Dict[str, List[str]], List[str], List[str], Dict[str]]:
        langs = {
            'expert'      : ['python'],
            'intermediate': ['c#', 'js'],
            'learning'    : ['c', 'c++', 'go', 'java']
        }
        specialities  = ['web/app reverse engineering', 'fullstack', 'ai']
        ide           = ['vscode']
        laptop            = {
            'Windows': {
                'custom': {
                    'processor': 'Intel(R) Core(TM) i7-12700H | 14 cores',
                    'ram'      : '16gb',
                    'gpu'      : 'NVIDIA GeForce RTX 3070 Ti Laptop GPU'
                }
            }
        }

	return langs, specialities, ide, laptop
```

<h2 align="center">Skills </h2>

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=python,golang,vscode,androidstudio,c,cs,cpp,js,css,html" />
  </a>
</p>

<p href="https://discord.gg/onlp" align="center">
    <img alt="" src="https://github-readme-stats.vercel.app/api?username=lnvdth&theme=tokyonight&show_icons=true">
</p>
