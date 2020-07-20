```python
from dataclasses import dataclass


@dataclass(frozen=True)
class AboutMe:
    name: str = 'Vladimir Yahello'
    location: str = 'Ukraine, Lviv'
    age: int = 27
    experience: float = 4.5
    profile: str = 'python, network, test automation engineer'
    hobbies: str = 'bots, automation, open source, clean code'


@dataclass(frozen=True)
class Skills:
    languages: str = 'python, shell, groovy'
    operation_systems: str = 'linux, cisco, windows'
    test_frameworks: str = 'pytest, pyats, unittests, doctest, behave, selenium, robot framework'
    web_frameworks: str = 'flask-like, django, pyramid, aiohttp.web'
    code_quality: str = 'flake8, mypy, pylint, black, pydocstyle'
    devops: str = 'jenkins, travis, docker, elk'
    version_control: str = 'git, gerrit'
    approaches: str = 'object oriented, solid, micro services, agile'
    ongoing: str = 'backend/web development, javascript'


@dataclass(frozen=True)
class Social:
    codewars: str = 'https://www.codewars.com/users/vyahello'
    twitter: str = 'https://twitter.com/vyahello'
    linkedin: str = 'https://www.linkedin.com/in/volodymyr-yahello-821746127'
    blog: str = 'https://vyahello.github.io'
    email: str = 'vyahello@gmail.com'
```
