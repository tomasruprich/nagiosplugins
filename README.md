# nagiosplugins

Repository for various nagiosplugins. 

## check_file_owner

Plugin for checking file owner or group settings.

Usage:
  check_file_owner -f <file> [-u <uid>|-g <gid>]
  check_file_owner [-h | --help]
  check_file_owner [-V | --version]

Example: 
  /usr/lib64/nagios/plugins/check_file_owner -f /tmp -u 0 -g 0
