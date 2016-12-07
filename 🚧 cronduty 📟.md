![WIP](https://img.shields.io/badge/status-work_in_progress-yellow.svg)

https://github.com/siddharthkp/cronduty-cli

`cron monitoring with minimal configuration`


```
npm install -g cronduty

cron
```

Pick crontab by default. Can give file name as well. `cron filename`

_What does the command do?_

- Add curl requests to monitor cron: `curl cronduty.sh/start/ue3i || command && curl cronduty.sh/done/ue3i`
- Upload cron time to server ([API on aws lambda](https://github.com/siddharthkp/cronduty-api))
- Run periodic checks and raise alerts
