# Task Creator ALG

A portable workspace for independent software engineering practice. The starter is [schedule 1.2.2](https://github.com/dbader/schedule/tree/1.2.2) at commit `82a43db1b938d8fdf60103bd41f329e06c8d3651`. The original source and license are in `starter/`. `schedule-1.2.2-starter.zip` is the original archive prepared for the exercise.

## Run the starter tests

From the repository root on macOS or Linux, with Python 3 available:

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install pytest pytz
cd starter
python -m pytest -q test_schedule.py
```

The clean starter has 81 tests. On Windows, use these commands from WSL because the upstream suite uses `time.tzset()`.

## Practice context

The exercise explored removing tags from a scheduled job while preserving its callback and next execution time. Use the clean source to inspect the existing tagging APIs, reproduce edge cases, and practice evaluating an agent's claims against its changes and test output.
