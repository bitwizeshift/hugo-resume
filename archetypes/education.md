---
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
institution: ''
address: ''
from-date: '{{ .Date | time.Format "2006-01" }}'
to-date: '{{ .Date | time.Format "2006-01" }}'

# List skills that were associated with this job
skills:
  - "" # skill 1

type: education
---

<!-- Summarize what you did in point-form notation -->
