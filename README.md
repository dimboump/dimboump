## Dimitris Boumparis — @dimboump

```python
class Dimitris(Boumparis):

    def __init__(self):
        self.first_name = self.__class__.__name__
        self.last_name = super().last_name
        self.birth_year = 1997
        self.role = "Master's Student"
        self.locations = {'hometown': (Nafplio, Greece), 'currently': (Antwerp, Belgium)}
        self.skills = {
            'Languages': {'EL': 'native', 'EN': 'proficient', 'DE': 'advanced', 'ES': 'intermediate'},
            'Programming': ['Python', 'R', 'JavaScript'],
            'OS': {'Windows': 11.0, 'Linux': 20.04},
            'Web': ['HTML', 'CSS', 'SCSS', 'WordPress', 'Drupal'],
            'Tools': ['Visual Studio Code', 'GitHub', 'Azure', 'Microsoft Office'],
            'Translation': ['Smartcat', 'RWS Trados Studio'],
            'Creative': ['Photoshop', 'Lightroom', 'Figma']
        }
        self.research_interests = ['Natural Language Processing', 'Machine Translation', 'Website Localization']
        self.hobbies = ['Photography', 'Sudoku', 'Tech']
        
    def __repr__(self):
        return f"""\
            Hi there 👋. I'm {self.first_name} — a {self.role.lower()} of
            Digital Text Analysis at the University of {self.locations['currently']}.
        """
```

### 🔜 Currently working on...

- [x] Mikros, G.K. & **Boumparis, D.** (submitted). _Cross-linguistic Authorship Attribution and Author Profiling. Is Machine Translation the Solution?_
- [x] **Boumparis, D.** & Giannoutsos, C. (submitted). _Quantitative and Qualitative Evaluation of Human and Machine-Translated EU Economic Texts in the English-Greek Language Pair_.

### 📄 Publications

- **Boumparis, D.** & Yannoutsos, C. (2021). _Defining translation strategies based on differences between machine and human translation of initialisms and acronyms from minor into major languages_. In K. Valeontis, P. Krimpas, M. Pantazara, K. Toraki, & G. Tsiamas. Hellenic Language and Terminology: 13th Conference Papers. (pp. 328-340). Athens: Hellenic Society for Terminology.
- Adam, E., Valsami, V., Yannoutsos, C., & **Boumparis, D.** (2019). _Designing and Compiling a Greek-German Glossary for Academic Websites: The Case of DFLTI_. In K. Valeontis, P. Krimpas, M. Pantazara, K. Toraki, & G. Tsiamas. Hellenic Language and Terminology: 12th Conference Papers. (pp. 275-288). Athens: Hellenic Society for Terminology.
- Adam, E., Valsami, V., Yannoutsos, C., & **Boumparis, D.** (2019). _Translation and Localisation of Academic Websites in German and Study of Information Architecture: The Case of DFLTI_. Corfu: Department of Foreign Languages, Translation and Interpreting (DFLTI), Faculty of Humanities, Ionian University.

### ☑️ Past Work

- Website of [DFLTI](http://dflti.ionio.gr/)
- Website of [PEM](https://pem.gr)
- Website of [Translation & Interpreting Events](https://ti-events.org)
- Website of [dimetra.academy](https://dimetra.academy).

### 💬 Get in touch!

- Email: [dimboump@pm.me](mailto:dimboump@pm.me)
- Twitter: [@dimboump](https://twitter.com/dimboump)
- Stack Overflow: [@dimboump](https://stackoverflow.com/users/6748361/dimboump)
