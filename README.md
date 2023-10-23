## Info
```python
class AnArchitectApparently:
    """I find beauty in ever new places."""

    def __init__(self):
        self.name = "Marcin Cichocki"
        self.language = "Python"
        self.since = 2019
        self.prerequisites = "CS50, Hyperskill, Udemy"
        self.tools = "Pandas, Django"

    def __repr__(self):
        return " - ".join((self.name, self.language, self.tools))

    def __str__(self):
        bio = """Hi, I'm Marcin. I'm a curious individual. I've been consuming code for a few years..
        Initially applied it to automate the hard and boring or cut design & construction related corners, currently (like everyone) peeking into ML and web.
        I find the beauty of engineering soothing."""
        return bio

    @property
    def contact(self):
        """For enquiries, plase contact me via:"""
        return {
            "email": "bS5hLmNpY2hvY2tpQGdtYWlsLmNvbQooZm9yIGxlZ2l0aW1hdGUgcHVycG9zZXMgb25seSk=",
            "phone": "KCs0NCkgMCA3ODI1NzU4MTY4Cihmb3IgbGVnaXRpbWF0ZSBwdXJwb3NlcyBvbmx5KQ=="
        }
```

## GitHub

<a href="https://github.com/cinkovic">
  <img align="center" src="https://github-readme-stats.vercel.app/api?username=cinkovic&show_icons=true&line_height=27&count_private=true&theme=radical&hide=contribs" alt="GitHub" />
</a>
