---
name: Bug
description: Something not good happened
labels: bug
body:
- type: dropdown
  id: download
  attributes:
    label: How did you download the software?
    options:
      - Homebrew
      - MacPorts
      - apt-get
      - Built from source
  validations:
    required: true
---

## Report

_Add a high level, human readable description for public facing release notes_

### :fire: or :face_with_head_bandage: or :snail:

1. List the steps to reproduce

2. Include errors or screenshots

```
Paste any relevant console error in this code block
```

3. If applicable, add device information or paste the link from [whatismybrowser.com](https://www.whatismybrowser.com).

- OS: [e.g. Windows, macOS, iOS]
- Browser: [e.g. Chrome, Safari]
- Browser Version: [e.g. 23]


