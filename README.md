## Info
```python
class AnArchitectApparently:
    """Discovering beauty in ever new places."""

    def __init__(self):
        self.name = "Marcin Cihocki"
        self.since = 2019
        self.languages = "Python, JavaScript"
        self.tools = "Pandas, Django, Vue, Git, Docker"
        self.prerequisites = "Harvard CS50, Hyperskill, Udemy"

    def __repr__(self):
        return "\n".join((self.name, self.languages, self.tools))

    def __str__(self):
        bio = """
        Hi, I'm Marcin. I'm a curious individual. I've been consuming code for a few years.
        I initially applied it to automate the hard and boring or cut design & construction related corners.
        Currently (like everyone) peeking into ML and web. 
        I find the beauty of engineering soothing..
        """
        return bio

    @property
    def contact(self):
        """For enquiries, plase contact me via:"""
        return {
            "email": "bS5hLmNpY2hvY2tpQGdtYWlsLmNvbQooZm9yIGxlZ2l0aW1hdGUgcHVycG9zZXMgb25seSk="
        }
```

## GitHub

<a href="https://github.com/cinkovic">
  <img align="center" src="https://github-readme-stats.vercel.app/api?username=cinkovic&show_icons=true&line_height=27&count_private=true&theme=radical&hide=contribs" alt="GitHub" />
</a>
