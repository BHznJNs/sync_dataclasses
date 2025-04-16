# sync_dataclasses

A library for creating thread safe data classes.

## Getting started

### Install

```bash
pip install sync_dataclasses
```

### Usage

```python
from dataclasses import dataclass
from sync_dataclasses import SyncDataClass

@dataclass
class Data(SyncDataClass):
    value1: int = 0
    value2: str = ""
```
