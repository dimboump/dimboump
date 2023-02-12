# Dimitris Boumparis — @dimboump

```python
class Dimitris(Boumparis):

    def __init__(self):
        self.first_name = self.__class__.__name__
        self.last_name = super().__class__.__name__
        self.birth_year = 1997
        self.role = "Master's Student"
        self.locations = {'hometown': ('Nafplio', 'Greece'), 'currently': ('Luxembourg', 'Luxembourg')}
        self.skills = {
            'Programming': ['Python', 'R', 'HTML', 'CSS', 'SCSS', 'JavaScript'],
            'Languages': {'EL': 'native', 'EN': 'proficient', 'DE': 'advanced', 'ES': 'intermediate'},
            'Translation': [('EN', 'EL'), ('DE', 'EL'), ('ES', 'EL'), ('EL', 'EN')],
            'Creative': ['Photoshop', 'Lightroom', 'Figma']
        }
        self.tools = ['Visual Studio Code', 'GitHub', 'Azure', 'Smartcat', 'RWS Trados Studio']
        self.research_interests = ['Natural Language Processing', 'Computational Stylometry', 'Large Language Models']
        self.hobbies = ['Photography', 'Sudoku', 'Tech']

    def __repr__(self):
        return f"""\
            Hi there 👋. I'm {self.first_name} — a {self.role.lower()} of
            Digital Text Analysis at the University of {self.locations['currently']}.
        """
```

## 🔜 Currently working on...

- [x] Mikros, G.K. & **Boumparis, D.** (submitted). _Cross-linguistic Authorship Attribution and Author Profiling. Is Machine Translation the Solution?_, 14 October 2022, PREPRINT (Version 1) available at Research Square [https://doi.org/10.21203/rs.3.rs-2129774/v1](https://doi.org/10.21203/rs.3.rs-2129774/v1)
- [x] **Boumparis, D.** & Giannoutsos, C. (submitted). _Quantitative and Qualitative Evaluation of Human and Machine-Translated EU Economic Texts in the English-Greek Language Pair_.
- [ ] **Boumparis, D.** (2023). _Native Language Identification of Greek in English-Written texts_, Master's Thesis, University of Antwerp. [https://github.com/dimboump/GreekNLI](https://github.com/dimboump/GreekNLI)

## 📄 Publications

- **Boumparis, D.** & Yannoutsos, C. (2021). _Defining translation strategies based on differences between machine and human translation of initialisms and acronyms from minor into major languages_. In K. Valeontis, P. Krimpas, M. Pantazara, K. Toraki, & G. Tsiamas. Hellenic Language and Terminology: 13th Conference Papers. (pp. 328-340). Athens: Hellenic Society for Terminology.
- Adam, E., Valsami, V., Yannoutsos, C., & **Boumparis, D.** (2019). _Designing and Compiling a Greek-German Glossary for Academic Websites: The Case of DFLTI_. In K. Valeontis, P. Krimpas, M. Pantazara, K. Toraki, & G. Tsiamas. Hellenic Language and Terminology: 12th Conference Papers. (pp. 275-288). Athens: Hellenic Society for Terminology.
- Adam, E., Valsami, V., Yannoutsos, C., & **Boumparis, D.** (2019). _Translation and Localisation of Academic Websites in German and Study of Information Architecture: The Case of DFLTI_. Corfu: Department of Foreign Languages, Translation and Interpreting (DFLTI), Faculty of Humanities, Ionian University.

## 💬 Get in touch!

- Email: [dimitris@dimboump.dev](mailto:dimitris@dimboump.dev)
- Twitter: [@dimboump](https://twitter.com/dimboump)
- Stack Overflow: [@dimboump](https://stackoverflow.com/users/6748361/dimboump)
