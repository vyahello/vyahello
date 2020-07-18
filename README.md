```python
from dataclasses import dataclass
from typing import Sequence


@dataclass(frozen=True)
class Portfolio:
    name: str = 'Vladimir Yahello'
    location: str = 'Ukraine, Lviv'
    profile: str = 'python, network, aqa engineer'
    experience: str = '4+ years'
    hobbies: Sequence[str] = 'bots', 'automation', 'open source', 'clean code'


@dataclass(frozen=True)
class Skills:
    languages: Sequence[str] = 'python', 'shell', 'groovy'
    operation_systems: Sequence[str] = 'linux', 'raspbian', 'cisco', 'mac', 'windows'
    test_frameworks: Sequence[str] = 'pytest', 'pyats', 'unittests', 'doctest', 'selenium'
    web_frameworks: Sequence[str] = 'flask-like', 'django', 'pyramid', 'aiohttp'
    code_quality: Sequence[str] = 'flake8', 'mypy', 'pylint', 'black', 'pydocstyle'
    devops: Sequence[str] = 'jenkins', 'travis', 'docker', 'elasticsearch'
    version_control: Sequence[str] = 'git', 'gerrit'
    approaches: Sequence[str] = 'object oriented', 'micro services', 'asyncio'
    ongoing: Sequence[str] = 'backend/web development', 'c', 'javascript'


@dataclass(frozen=True)
class Social:
    codewars: str = 'https://www.codewars.com/users/vyahello'
    twitter: str = 'https://twitter.com/vyahello'
    linkedin: str = 'https://www.linkedin.com/in/volodymyr-yahello-821746127'
    blog: str = 'https://vyahello.github.io'
    email: str = 'vyahello@gmail.com'
```
