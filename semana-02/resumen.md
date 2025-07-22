# Week 02 - Cron Jobs and Log Monitoring

## Topics Covered
- Scheduling recurring tasks using `cron`
- Setting up crond in a WSL environment without systemd
- Redirecting command output to log files
- Monitoring task execution with `tail`
- Reading basic system logs from `/var/log/messages`

## Practical Exercises
- Created a cron job that logs the current date and time every minute
- Configured crond to auto-start on each terminal session
- Used `tail -f` to monitor cronjob execution in real time
- Validated `crond` with `ps aux` and confirmed log activity

## Reflection
Automating recurring tasks using cron is a fundamental skill for any Linux admin or DevOps engineer. Understanding how to make it work in constrained environments like WSL reinforces practical problem-solving and system awareness.
