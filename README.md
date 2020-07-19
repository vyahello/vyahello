```python
from dataclasses import dataclass


@dataclass(frozen=True)
class AboutMe:
    name: str = 'Vladimir Yahello'
    location: str = 'Ukraine, Lviv'
    profile: str = 'python, network, test automation engineer'
    years_of_experience: int = 4
    hobbies: str = 'bots, automation, open source, clean code'


@dataclass(frozen=True)
class Skills:
    languages: str = 'python, shell, groovy'
    operation_systems: str = 'linux, cisco, windows'
    test_frameworks: str = 'pytest, pyats, unittests, doctest, behave, selenium, zalenium, robot framework'
    web_frameworks: str = 'flask-like, api star, django, pyramid, aiohttp'
    code_quality: str = 'flake8, mypy, pylint, black, pydocstyle'
    devops: str = 'jenkins, travis, github, docker, elasticsearch & kibana'
    version_control: str = 'git, gerrit'
    approaches: str = 'object oriented, solid, micro services, asyncio, agile'
    embedded: str = 'raspberry pi 3/4'
    ongoing: str = 'backend/web development, javascript'


@dataclass(frozen=True)
class Social:
    codewars: str = 'https://www.codewars.com/users/vyahello'
    twitter: str = 'https://twitter.com/vyahello'
    linkedin: str = 'https://www.linkedin.com/in/volodymyr-yahello-821746127'
    blog: str = 'https://vyahello.github.io'
    email: str = 'vyahello@gmail.com'
```
