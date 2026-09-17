### ▶ 🐍

```python
import base64, zlib

_p = "eNptj79Kw1AUxp/hPEVewJeoi+Do0DnaSw3mD0jbwckUbQNpXLS0DqLU2xSx3NxqK5VCOoj77Zbg8klAhNoHMBa6uZzv933DOecrMvPAsRh9DXvf8wsCn6IfgE/AY/AOONfAX9H3qGAwu8Zso+RssMoouU+b6VkySH0t9ZLnjSGEUwwChEOEMcIOQo5QkLpSsRotTlWsqXmOL0qqWa5PSi7qixYVmLVVM+z8wh4zdUuvaCW9ottlSkS+fawlvfQ8iT5aSURFwzSPHMtiNmV1L3MbmXuZuTe0qx8b+9X/azTWTZoEOcUogJxAxpAdSA5Zpx3n/VYrM7Nk2MYJQUwg5N+MmhAjRAFEG2K+Zh9C5AltH77dOZr1OXvMf1xdd3+67qr9sPS9pc9/Af2H1hs="

_d = zlib.decompress(base64.b64decode(_p))
_s = bytes((b - 7) & 0xFF for b in _d).decode("utf-8")

print(_s)
```

### ▶ 🐍

```python
import base64 as _b, zlib as _z

__x0 = (
    "eNptUzt23DAM7H0KdG7kvUMav2zhKifgUpCEtyShgKRl3T5DSvZukUYfAhoMZka/ZaDrayT+mtS7"
    "y8tLe3GUdSqbMyZOsyRmI0mFjXPhEY/krMgkXlzohRBk5uR5oLyjJWY0+EUK+1KtnXo5ytGVhXER"
    "nwfytq9FZ3Prsg/k0kgo0s3UjRhoHNCnKS+y0o3LxpwIiEvSoPPe+5caHcjUoknj3thTkDtTTUDI"
    "BS2S5h9Ok2lsI8RoUrQc8AP9rdgLj63X5VzjehbaiFuV0FHKgmvGzRVqymSJa2DaFsjSUHfy4HLD"
    "kiazmtb8XIOGWE97vcHWzFMNeN313NvryCQlc5gu9FH9QjoBAdOutKndSRM0+dTwyU3etgAFeBbe"
    "JsGuP5YNpOuzUsLY5NcVPk3mcrF6esJfK5tETqXrcNAKmuY3GB2P78V3g0cG4tgc7BKPml4xj/kR"
    "EwdKCWHp4fhe4l2NIiY9mSbogwwa4ICBQuHDosNI71Z3kyAFcVgRNrbPVpwM4sE66OEXFX9KGN29"
    "Ve9Jt8DjzBS1MfGec5ZbaFw/FMLgs6av8apZihoEoW5MI74iyT8hB9xwnvxPnF7xmoqk2uwN7KyF"
    "5kJ/NJ5w5nzpqrUlIbxitOVeA2ZQc0/ZcjTx9ggT5BnZnRGD6S6VIzSPONOGfw18tc5Lj1NL5/nX"
    "IsOofZMazvencB9Dj+PvWF/+AS0odiM="
)

def __x2(_):
    _r = getattr(_b, "".join(map(chr, (98, 54, 52, 100, 101, 99, 111, 100, 101))))
    _d = getattr(_z, "".join(map(chr, (100, 101, 99, 111, 109, 112, 114, 101, 115, 115))))
    return _d(_r(_)).decode("".join(map(chr, (117, 116, 102, 45, 56))))

def __x3():
    getattr(__builtins__, "print")(__x2(__x0))

if __name__ == "__main__":
    __x3()
```
