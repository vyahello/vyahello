```python
from dataclasses import dataclass as portfolio


@portfolio(frozen=True)
class AboutMe:
    name: str = 'Vladimir Yahello'
    location: str = 'Ukraine, Lviv'
    age: int = 27
    experience: float = 4.5
    profile: tuple = 'python engineer', 'AQA engineer'
    hobbies: tuple = 'bots', 'automation', 'open source', 'clean code'


@portfolio(frozen=True)
class Skills:
    languages: tuple = 'python', 'shell', 'groovy'
    operation_systems: tuple = 'linux', 'cisco', 'windows'
    test_frameworks: tuple = 'pytest', 'pyats', 'unittests', 'doctest', 'behave', 'selenium', 'robot framework'
    web_frameworks: tuple = 'flask-like', 'django', 'pyramid', 'aiohttp'
    devops: tuple = 'jenkins', 'travis', 'docker', 'elk'
    ongoing: tuple = 'backend/web development', 'javascript', 'embedded'


@portfolio(frozen=True)
class Social:
    codewars: str = 'https://www.codewars.com/users/vyahello'
    twitter: str = 'https://twitter.com/vyahello'
    linkedin: str = 'https://www.linkedin.com/in/volodymyr-yahello-821746127'
    blog: str = 'https://vyahello.github.io'
    email: str = 'vyahello@gmail.com'
```
