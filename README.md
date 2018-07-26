# animeplanet CLI

## Usage

### CLI

```console
python3 animeplanet.py set-episodes elfen-lied 2
```

The CLI uses credentials stored in `~/.animeplanet.conf` in form `USERNAME,PASSWORD`.

### python module

```python
from animeplanet import AnimePlanetSession

session = AnimePlanetSession()
session.login('user', 'password')

session.set_episodes('elfen-lied', 2)

session.logout()
```
