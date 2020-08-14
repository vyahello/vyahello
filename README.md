<a href="https://sourcerer.io/vyahello" title="code breakdown"><img src="https://sourcerer.io/assets/avatar/vyahello" width="32"/>Python | Shell | Git | Docker | CI/CD</a>

```python
from dataclasses import dataclass as portfolio


@portfolio(frozen=True)
class AboutMe:
    name: str = 'Vladimir Yahello'
    location: str = 'Ukraine, Lviv'
    age: int = 27
    experience: float = 4.5
    profile: tuple[str] = 'python engineer', 'AQA engineer'
    hobbies: tuple[str] = 'bots', 'automation', 'open source', 'clean code'


@portfolio(frozen=True)
class Skills:
    languages: tuple[str] = 'python', 'shell', 'groovy'
    operation_systems: tuple[str] = 'linux', 'cisco', 'windows'
    test_frameworks: tuple[str] = 'pytest', 'pyats', 'unittests', 'doctest', 'selenium', 'robot framework'
    web_frameworks: tuple[str] = 'flask-like', 'django', 'pyramid', 'aiohttp'
    devops: tuple[str] = 'jenkins', 'travis', 'docker', 'elk'
    ongoing: tuple[str] = 'backend/web development', 'javascript', 'embedded'


@portfolio(frozen=True)
class Social:
    codewars: str = 'https://www.codewars.com/users/vyahello'
    twitter: str = 'https://twitter.com/vyahello'
    linkedin: str = 'https://www.linkedin.com/in/volodymyr-yahello-821746127'
    blog: str = 'https://vyahello.github.io'
    email: str = 'vyahello@gmail.com'
```
![vyahello's github stats](https://github-readme-stats.vercel.app/api?username=vyahello&show_icons=true&hide_border=true&count_private=true)
